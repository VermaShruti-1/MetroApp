It is a Java implementation of a Metro App that uses HashMap for station storage and Graph for calculating the shortest path. This example uses Dijkstra's algorithm for finding the shortest path between stations.
1. Graph Representation:
The metro network is represented using a HashMap where each key is a station name, and the value is a list of Edge objects representing connections to other stations and their distances.
2. Adding Stations:
Stations are added using the addStation method.
3. Adding Routes:
Routes between stations are added with distances using the addRoute method. Each route is bidirectional.
4. Shortest Path Calculation:
Dijkstra's algorithm is implemented in the shortestPath method. It uses a priority queue to explore the shortest paths incrementally and updates the distance for each station.
5. Output:
The program prints the shortest paths from a starting station to all other stations.
