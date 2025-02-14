# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

1. Open the roboanalyzer software.
2. Select the robot and its degrees of freedom.
3. Change the values of X and Y wherever necessary.
4. Stimulate the model for inverse kinematics.
5. Plot the graph between the joints.
6. Update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 

RPR ROBOT:

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/abda3d19-1fab-4dbd-90dc-4bff17a7e041)

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/e6fad59c-d5e0-4b84-b01d-5db054b7f438)

3R ROBOT:

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/fc280ba0-f14b-449b-8b6d-593f3a9c743c)

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/125ad973-2f1d-485b-a1af-ab76608d6464)
 
 
 
 ### PLOT 
 RPR ROBOT:

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/02cde84d-7fe7-49fd-9aca-fe7af8b418e9)
 
![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/43f40d3e-59b4-47dc-9218-408b8ea7b097)
 
3R ROBOT:

![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/93d597ca-331d-43d9-a605-874f55ef3d5c)
 
![image](https://github.com/Naadira/Inverse-kinematic-modeling-using-robo-analyzer-/assets/128135126/2e17d962-2d51-4ac7-87c1-f56253e8dde8)
 
 

### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
