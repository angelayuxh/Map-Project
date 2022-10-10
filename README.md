# Map-Project
![map full screen](https://user-images.githubusercontent.com/109006994/193184076-7a29cbc1-7d50-448c-bd2e-cda07f008785.png)

The map is developed in C++ using ezgl and GTK, built based on OpenStreetMap data. This was a full term project for ECE297. 

## Disclaimer of the code

This project is an academic project for ECE297, University of Toronto. Due to Academic Integrity concerns, we cannot share the full version of the code to prevent students from copying.

## Contributors
Zhichen Lei

Tracy Sun

Angela Yu

## Features of the map

The map supports maps of 19 different locations. Maps can be selected using the drop down menu.
![select map](https://user-images.githubusercontent.com/109006994/193500005-7b53796a-0656-449d-a937-8aa443799860.png)

**Path Finding and Route Direction System**

![path finding and direction screenshot](https://user-images.githubusercontent.com/109006994/193185113-7f9417a5-4546-45e1-b837-dc23156bd57f.png)

The path finding feature of the map can be used to find the legal path with the minimum travel time between two intersections. 

There are 2 ways of using the path finding feature
1. Entering the names of a pair of intersecting streets to the search box "Start Location" and another pair of intersecting streets to the search box "Destination". Then, click "Find Path". 
2. Click "Select With Mouse" to enable mouse selection mode. Left click directly on the map will selection intersection for "Start Location", then intersection for "Destination". "Start Location" will be highlighted in black and "Destination" will be highlighted in red. Then, click "Find Path".

![input methods](https://user-images.githubusercontent.com/109006994/193187090-a0ca24f9-4ec2-470c-ac3d-09f5ea623997.png)

The path found will be highlighted in light purple. Use "Clear Result" to remove the highlighted path.

![path find highlight](https://user-images.githubusercontent.com/109006994/193189139-70a5af30-e34d-4d4b-ae85-0964b48ca199.png)

When a path is found, the Route Direction System on the bottom right of the map will display the travel directions and instructions. 

![direction](https://user-images.githubusercontent.com/109006994/193185500-dcbad71f-681c-40a5-aeea-391e3d88bf4f.png)

### Closable Search Window
A closable search window is used to keep the UI uncluttered while implementing the path-finding function. 

* The user can keep changing the destination and start until the most ideal one is selected. 

* the searching panel can be hidden anytime to get a broader view of the map

    * The hide/display button is at the leftmost panel of the UI

* User can choose to clear the previous path before conducting a new search. 
![select](https://user-images.githubusercontent.com/100390810/194931273-c0809d61-51b6-4c82-a50d-d8a637ecf772.gif)

