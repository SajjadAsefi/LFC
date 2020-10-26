# Controller parameters tuning of differential evolution algorithm and its application to load frequency control of multi-source power system
#### Controller parameters tuning for load frequency control (matlab code)

You are allowed to use this code for educational purposes and for citation use the following paper:

+ SeyedShenava, S., and Asefi, S. "Tuning controller parameters for AGC of multi-source power system using SCA algorithm." Delta 2.B2 (2018): B2.

### YouTube link of the project
+ Project's YouTube link: https://youtu.be/VTQJRqmlZ3o 

### Code files discription:
Controller parameters tuning for load frequency control (matlab code) 

The main paper I started my LFC simulation is:
Mohanty, Banaja, Sidhartha Panda, and P. K. Hota. "Controller parameters tuning of differential evolution algorithm and its application to load frequency control of multi-source power system." International journal of electrical power & energy systems 54 (2014): 77-85.
I recommend it (in addition to my own paper) for anyone who wants to start simulation in this area.

I have simulated a multi-area system and applied SCA optimization algorithm for controller parameter selection. 
I have analyzed controller's robustness by change in two different parameters of the system, R (governor speed regulation) and B (frequency bias parameter). In addition to HVDC link, I have considered SMES.
A novel population-based optimization algorithm called Sine Cosine Algorithm (SCA) has been adopted to solve optimization of automatic load frequency control (LFC) of a realistic power system with multi-source power generation is presented.
The sensitivity analysis reveals that the proposed controller is quite robust and optimum controller gains once set for nominal condition need not to be changed for ±25% variations in the system parameters and operating load condition from their nominal values. The dynamic performance of proposed controller is investigated by integral of time multiplied absolute error (ITAE) cost function.

Files contain the following results:

- First we are going to compare DE and SCA algorithms in respect to 1 percent step change in load of area one and compare the results with the obtained results in main paper. 
- Next we are going to investigate effectiveness of using SMES instead of HVDC in our system. 
- And finally we are going to analyze a situation in which we use only one PID controller instead of three controllers, while using SMES for area 1. 

Our comparison contains two stages. Stage 1 is comparing system with and without SMES and stage 2 is to compare system with SMES for using 3 and one PID for all areas. And finally we have analyzed system robustness considering system with SMES while using three PID controllers

By running m.files compaire_1 and compare_2 you will obtain the needed results (based on parameters obtained seperately from simulation and stored in an excel file). If you are interested to run each stage seperately, the files with detailed codes are provided. 

#### In case of further questions please contact: sajjad.asefi1992@gmail.com
All the best


