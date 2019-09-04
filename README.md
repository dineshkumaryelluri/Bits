# Assignment 2–PS3-[SHIPMENT PROBLEM]

## Problem Statement:
Amazon Warehouse in Bangalore was expecting a freight shipment at 10 am on a Monday. However,  the  company  responsible  for  the  shipment  mistook  the  destination  as  Amazon Development Centre, Bangalore. In order to save the extra cost of transportation back to the warehouse, the warehouse manager wants to help them find the fastest route from the DC to warehouse. He has the location map available which is given below (the weightage given is the distance in km between each location). However, as he did not takeDSAD course he turns to you for help.

![Warehouse route map](https://github.com/dineshkumaryelluri/Bits/blob/master/AssignmentGraph.png) 

### Algorithm for finding shortest path:
To find the fastest route between to points in a map(graph provided), we essentially have to find the shortest weighed path between those 2 points. This can be acheived by BFS traversal of graph choosing the edge with lowest weight.
We can use `Dijkstra’s Algorithm` to find the shortest path in a weighed graph
