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

1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values of X and Y wherever necessary.
4. simulate the model for inverse kinematics.
5. plot the graph between the joints.
6. update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 
 
 #### RPR ROBOT:
![Capture55](https://user-images.githubusercontent.com/75234588/170752418-c67eb75f-b86b-4239-bec5-5038f98ef168.PNG)


![Capture49](https://user-images.githubusercontent.com/75234588/170745733-b77491aa-53a1-44be-8a6b-bd6f47b1be2a.PNG)



  #### RRP ROBOT:
  
  ![Capture54](https://user-images.githubusercontent.com/75234588/170747712-ab1e9848-9222-4b9e-8df9-ab46127ef9f5.PNG)


![Capture50](https://user-images.githubusercontent.com/75234588/170747365-0231d81a-3f18-44a6-b8f1-6e922f0a9749.PNG)

![Capture51](https://user-images.githubusercontent.com/75234588/170747447-33b31aed-a8a0-4061-a65f-d5b1964c956e.PNG)


 ### PLOT 
 
  #### RPR ROBOT:
  
  ![Capture57](https://user-images.githubusercontent.com/75234588/170753678-75790efb-3658-4cda-84c3-c0a600e568a5.PNG)

  
![Capture56](https://user-images.githubusercontent.com/75234588/170753203-d2d8b058-7cc0-4bea-80f8-9b9e97f822b2.PNG)


  #### RRP ROBOT:
  
 ![Capture52](https://user-images.githubusercontent.com/75234588/170748234-f8d78c46-dcc7-4d03-9cab-e42ee7122e14.PNG)

![Capture53](https://user-images.githubusercontent.com/75234588/170748277-d03204f7-383f-4e02-84a1-33c40d738b67.PNG)

 

### RESULTS :  

Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given  input end effector position is plotted.
