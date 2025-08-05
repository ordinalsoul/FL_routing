# FL_routing
Project3 COP3530

##Prerequisites
Python 3.12

##Libraries needed to install
osmnx
matplotlib
pickle
networkx


##How to Run
The application is run by the florida_routing.py file
If you want to download a new map and save it for use later there are 2 lines of code that need changing:
1. Line 13 in florida_routing.py changes the name of the file that would be accessed or saved once downloaded
2. Line 29 in florida_routing.py chnage the name to the one you want with format:
   (City, State, Country) or (State, Country)

##Warning
If the file needs to be downloaded, the time it will take for the code to run will be longer for that first time when it is downloaded. Ex. the florida.pkl file with around 900k nodes took 20-30 minutes to run the first time.
After that first time the time is significantly reduced, but still depends on the size of the graph that needs to be built

#How to Use
Once the application is running the first click inside the map will be the start of the path and the second will be the target location.
You can zoom in and out of the map and can move with the the arrows or by clicking the hand icon you can drag the map.
There is also a save button which will take a screenshot of the application including path and results if ther are present.
