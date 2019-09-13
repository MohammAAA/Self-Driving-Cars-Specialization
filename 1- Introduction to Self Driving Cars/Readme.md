# ^In the name of Allah the Merciful^

# Introduction to Self-Driving Cars

## Course Objectives
> This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars. By the end of this course, you will be able to: - Understand commonly used hardware used for self-driving cars - Identify the main components of the self-driving software stack - Program vehicle modelling and control - Analyze the safety frameworks and current industry practices for vehicle development For the final project in this course, you will develop control code to navigate a self-driving car around a racetrack in the CARLA simulation environment. You will construct longitudinal and lateral dynamic models for a vehicle and create controllers that regulate speed and path tracking performance using Python. You’ll test the limits of your control design and learn the challenges inherent in driving at the limit of vehicle performance. This is an advanced course, intended for learners with a background in mechanical engineering, computer and electrical engineering, or robotics.

## Table of Contents
* Introduction to Self-Driving Cars
  * [Welcome to The Course](#Welcome to The Course)
  * [The Story of Autonomous Vehicles](#Story of autonomous vehicles)
  * [Glossary of Terms][#Glossary of terms]
* [Driving Taxonomy, Perception and Driving Decisions](# Driving Taxonomoy)
  * [Lesson 1: Taxonomy of Driving](#Taxonomy of Driving)
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
### Welcome to The Course
By the end of this course you will:
- Learn about the elements of driving: perception, prediction, decision making
- Understand how to design the software and hardware stack to do autonomous driving
- Understand common safety practices for autonomous driving
- Learn the basics of vehicle modeling and control, and design controllers to do speed regulation, path following, etc...
- Use the above concpets to help navigate a self driving car in CARLA.

### The Story of Autonomous Vehicles
- The dream of SDC is almost old as the automobile,
  - In 1925, someone has demonstrated a remote control car to frighten passerby with a car an empty driver seat
  - In 1956, GM has made a promotional video claiming that SDC would arrive by 1976, this SDC would take full control on the highway and the driver can interact with the car by voice control features.

- There is no doubt that one of the most dangerous things we do on a rigular basis is driving our cars.
- Over 94% of the nowadays accidents are caused by human error.
- SDC objective is to minimize or completely eliminate driving deaths by taking human error out of the picture, and another objective is increasing luxury in our cars as we can reply to our mail, eat or relax instead of focusing on lanes, turns, cars, etc..

- The SDC industry has reached many milestones starting from 1990 until now
- The first SDC accident has occured in Florida by a *Tesla Model S* in 2016, This was caused by a simultaneous failure of both camera and radar sensors to correctly identify a *left turning transport truck* and the driver was inattentive, but this accident didn't affect the progress continuity.
- In 2016, the autonomous taxi fleets started to become popular, two startups (Zoox, nuTonomy) were leading this way
- In 2018, the first death accident has occurred by an *Uber vehicle*, This incident has affected the autonous vehicle testing community, and Uber has also stopped testing until they fully investigate the accident details

- There are some challenges still facing the SDC systems during testing:
  - Nowadays, the number of miles being driven by SDC in hard-conditions is exploding, so that the number of accidents are is predicted to also go up (Waymo announced that in fall 2018, they have completed over 10 million miles of autonomous driving!).
  - Human interventions are continously growing
  - The SDC performance is now very near to the human performance, and this is the reason why this industry needs more support than ever to meet and exceed this ambitious goal.
  
 - Nowadays, there are many newly established companies pushing to bring truly driverless cars to market as early as 2020.
 - The techonology is still quietly expensive, but prices will fall quickly when there is a market need for this solution.
 - There is so much to be done to bring about the expected transformational change to bring autonomous cars to society, and the industry is in continous need for outstanding engineers to produce innovative solutions for driving.
 
 
### Glossary of Terms

##### ACC: Adaptive Cruise Control
A cruise control system for vehicles which controls longitudinal speed. ACC can maintain a desired reference speed or adjust its speed accordingly to maintain safe driving distances to other vehicles.

##### Ego
A term to express the notion of self, which is used to refer to the vehicle being controlled autonomously, as opposed to other vehicles or objects in the scene. It is most often used in the form ego-vehicle, meaning the self-vehicle.

##### FMEA: Failure Mode and Effects Analysis
A bottom up approach of failure analysis which examines individual causes and determines their effects on the higher level system.

##### GNSS: Global Navigation Satellite System
A generic term for all satellite systems which provide position estimation. The Global Positioning System (GPS) made by the United States is a type of GNSS. Another example is the Russian made GLONASS (Globalnaya Navigazionnaya Sputnikovaya Sistema).

##### HAZOP: Hazard and Operability Study
A variation of FMEA (Failure Mode and Effects Analysis) which uses guide words to brainstorm over sets of possible failures that can arise.

##### IMU: Inertial Measurement Unit
A sensor device consisting of an accelerometer and a gyroscope. The IMU is used to measure vehicle acceleration and angular velocity, and its data can be fused with other sensors for state estimation.

##### LIDAR: Light Detection and Ranging
A type of sensor which detects range by transmitting light and measuring return time and shifts of the reflected signal.

##### LTI: Linear Time Invariant
A linear system whose dynamics do not change with time. For example, a car using the unicycle model is a LTI system. If the model includes the tires degrading over time (and changing the vehicle dynamics), then the system would no longer be LTI.

##### LQR: Linear Quadratic Regulation
A method of control utilizing full state feedback. The method seeks to optimize a quadratic cost function dependent on the state and control input.

##### MPC: Model Predictive Control
A method of control whose control input optimizes a user defined cost function over a finite time horizon. A common form of MPC is finite horizon LQR (linear quadratic regulation).

##### NHTSA: National Highway Traffic Safety Administration
An agency of the Executive Branch of the U.S. government who has developed a 12-part framework to structure safety assessment for autonomous driving. The framework can be found [here](https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/documents/13069a-ads2.0_090617_v9a_tag.pdf)

##### ODD: Operational Design Domain
The set of conditions under which a given system is designed to function. For example, a self driving car can have a control system designed for driving in urban environments, and another for driving on the highway.

##### OEDR: Object and Event Detection and Response
The ability to detect objects and events that immediately affect the driving task, and to react to them appropriately. 

##### PID: Proportional Integral Derivative Control
A common method of control defined by 3 gains.
1. A proportional gain which scales the control output based on the amount of the error
2. An integral gain which scales the control output based on the amount of accumulated error
3. A derivative gain which scales the control output based on the error rate of change

##### RADAR: Radio Detection And Ranging
A type of sensor which detects range and movement by transmitting radio waves and measuring return time and shifts of the reflected signal.

##### SONAR: Sound Navigation And Ranging
A type of sensor which detects range and movement by transmitting sound waves and measuring return time and shifts of the reflected signal.


  
  
  
  



