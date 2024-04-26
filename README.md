# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-
## Name : DINESH KUMAR M
## Date : 22-04-2024
## Register Number : 212221220011
## Department : INFORMATION TECHONOLOGY
### Aim :
To understand linear and joint interpolation of industrial manipulator and develop a program for the same

      
### Equipment Required: 
Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
![7r1](https://github.com/Prajin19/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979377/a950e516-46b4-43e4-8e39-679568b39608)
![7r2](https://github.com/Prajin19/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979377/1faf0da8-b4fb-4006-bce9-e293ad86b835)








### Robot movements 

![7r3](https://github.com/Prajin19/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979377/788b197a-fa30-44fd-bff3-bf8e646c0e2a)

![7r4](https://github.com/Prajin19/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979377/8a339023-c1de-46db-aed1-008aa84a208b)


![7r5](https://github.com/Prajin19/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144979377/ee7e6834-2639-40ff-9127-5a4a23d19605)










### Results:  
 A program is developed for understanding linear and joint interpolation of industrial manipulator and is ran sucessfully.
