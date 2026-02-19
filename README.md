# -Automated-Warehouse-Robot-Simulation-System
Discrete-event simulation of autonomous warehouse robots using A* pathfinding and graph-based routing in Python.


Simulates a fleet of autonomous robots fulfilling orders across a weighted warehouse graph over a 24-hour cycle
Uses A* pathfinding (NetworkX) to route robots to stations and back to dispatch via shortest weighted paths
Dynamic order generation (8–10 orders/tick) with proximity-based assignment to the nearest available robot
Models robot state: in-tray/out-tray queues, weighted-edge wait counters, and capacity-triggered dispatch returns
Scales from small fixed graphs (2 robots, 10 stations) to randomized topologies (40 robots, 100 stations)
Reports per-robot and fleet-wide KPIs: total orders completed and average processing time per 24-hour simulation
