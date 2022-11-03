# Map-Project
![map full screen](https://user-images.githubusercontent.com/109006994/193184076-7a29cbc1-7d50-448c-bd2e-cda07f008785.png)

The map is developed in C++ using ezgl and GTK, built based on OpenStreetMap data. This was a full term project for ECE297. 

## Disclaimer of the code

This project is an academic project for ECE297, University of Toronto. Due to Academic Integrity concerns, we are unable to share our code in oreder to prevent students from copying.

## Contributors
Zhichen Lei

Tracy Sun

Angela Yu

## Features of the map

The map supports maps of 19 different locations. Maps can be selected using the drop down menu.
![select map](https://user-images.githubusercontent.com/109006994/193500005-7b53796a-0656-449d-a937-8aa443799860.png)

### Path Finding and Route Direction System

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

### Point of Interest (POI) Display

POIs are searchable features, the icons of all POIs matching the searched key word will show up upon hitting <Enter> in the search bar. The search function allows partial name search.

There are four displaying modes for POIs, which allows the user to customize the UI based on their needs.

* POI display can be completely turned off
* Show one POI from each category in the user's vincinity (default)
* Show all POIs in the user's vincinity
* Show all POIs on the current map

Default display:

![image](https://user-images.githubusercontent.com/71286356/195718267-3d6ec00b-1820-4388-85a3-524d549b4d3d.png) 


Show all nearby POI:

![image](https://user-images.githubusercontent.com/71286356/195718285-851acc77-a318-4dbc-aa9d-4cb2aec615e3.png) 

#### Detail expansion on POIs
Detailed information of POIs are available upon clicking:

![image](https://user-images.githubusercontent.com/71286356/195718398-e2e6300a-fe6c-41a0-93a5-9fa2de888b3d.png) 

Clicking a POI will result in surrounding POIs of the same type to show up on the map.
For example: The map will show all surrounding restaurants if the user expands the details on one of them.

![image](https://user-images.githubusercontent.com/71286356/195720817-ea5fe445-89df-4bc9-bbed-e052e0efaf6f.png)

![image](https://user-images.githubusercontent.com/71286356/195721463-3b2f8356-38cc-48f9-9e5a-93d1ec85d754.png)








