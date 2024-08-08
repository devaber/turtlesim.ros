# turtlesim.ros
Manipulating turtlesim package in ros noetic
Start by opening the ubuntue terminal window and running the command "roscore", <br>
then open another terminal window -don't close the first one-, <br>
now run the turtlesim package by the command: "rosrun turtlesim turtlesim_node",<br>
<h5>Background Color</h5> <br>
to change the bachground color, open new terminal window and follow the steps:
1. reset each color chanel as you like (blue,green,red) using the commands shown in picture <br>
2. use "clear" service to apply changes.

![ros color](https://github.com/user-attachments/assets/0dea7add-26ef-4ae5-82a5-b482b52ff1e0) <br>

<h5>Motion</h5> <br>
open a new terminal window to create a path for the turtle using the arrow keys on your keyboard.<br>
1. run the command: "rosrun turtlesim turtle teleop key"
2. now draw your path using your arrow keys <br>

![ros turtlesim3](https://github.com/user-attachments/assets/40801f92-1427-4a3f-8d69-0dd8e76ca91b) <br>

<h5>Using rqt_graph</h5> <br>
1. in new terminal window, run the command: "rosrun rqt_graph rqt_graph" <br> to show your nodes and their communication <br>

![ros turtlesim4](https://github.com/user-attachments/assets/6d942fb5-3898-44d9-abad-6477431b0016) <br>

<h5>Add a New Turtle</h5> <br>
open a new terminal and use this command to add a new turtle: "rosservice call /spawn 2 2 0.2 "" " <br>
you cam name it as you like <br>

![ros turtlesim5](https://github.com/user-attachments/assets/1c68f13d-090c-4593-aebe-4a7018ad60b4) <br>

<h5>ROS Topic</h5> <br>
in a new terminal window, run the command: "rostopic lis" <br>
it will list all your currently subscribed and published topics <br>

![ros topics](https://github.com/user-attachments/assets/adc82180-9a6d-4b6e-b051-2eea9cd2ab3c) <br>

<h5>ROS Service</h5> <br>
in a new terminal window, use the command: "rosservices list" <br>
to list currently available services <br>

![ros list](https://github.com/user-attachments/assets/1cd966cc-66ab-48f7-8a33-4c336a5f01a1)
