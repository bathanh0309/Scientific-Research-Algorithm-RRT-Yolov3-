:bangbang: See a small portion of the code

:bangbang: All important code is deleted from the old computer 
### Research results
https://github.com/user-attachments/assets/0acbe8e5-27cd-4544-8ecd-db77a4d0f766

### RRT (Rapidly-exploring Random Tree) Navigation Algorithm
https://github.com/user-attachments/assets/82ad11ab-8727-4e50-9716-ae98289eeb89

### Purpose: 
RRT is an optimization algorithm for finding paths in high-dimensional space, which is very useful for autonomous vehicles  to navigate through obstacles.
### How it works:
Starting from the initial position, the algorithm expands the search tree by generating random points in space.

Each new point is checked to ensure that it does not collide with obstacles. If possible, it connects to the current tree.

As the tree grows, the algorithm finds a path from the starting point to the destination, while also being able to adapt to changes in the environment.

### Yolo (You Only Look Once) Algorithm
https://github.com/user-attachments/assets/fd2ad832-704b-4afa-b705-331a26b53cc7

### Purpose: 
Yolo is one of the fastest object recognition algorithms available today, allowing autonomous vehicles to recognize and classify multiple objects in real time.
### How it works:
Yolo divides the image into a grid and predicts the bounding box for each object in each grid cell.

Each bounding box comes with a probability of the presence of an object, which helps the autonomous vehicles recognize and classify what it sees.

Yolo is capable of processing hundreds of frames per second, making it ideal for applications that require fast response.

## When combining RRT and Yolo on Jetson Nano, the autonomous vehicles can:
Recognize and determine the distance to objects: Yolo helps the robot detect surrounding objects, while RRT calculates the optimal path to avoid collisions.

Smart path planning: Based on information from Yolo, RRT can adjust its path to safely and efficiently overcome obstacles.

Adapt to dynamic environments: The autonomous vehicles can automatically adjust its behavior based on new objects appearing in the environment, thanks to Yolo's real-time recognition capabilities.

<img src="https://github.com/bathanh0309/Scientific-Research-RRT-Yolov3/blob/main/Picture1.png"> 

<img src="https://github.com/bathanh0309/Scientific-Research-RRT-Yolov3/blob/main/Picture2.png"> 



