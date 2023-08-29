# ***Welcome!***

Hi all, I’m Jakeb Chouinard! I'm a 4th Year Mechatronic Engineering student at the University of Waterloo, and I'm looking to extend my work and learning into a Masters/PhD program. I've previously worked as a part-time Research Assistant at UW as well as a Software Development Intern for MathWorks, developing novel persistent memory algorithms using transactional memory, implementing parallelized ray-tracing scenario-solution algorithms, and expanding application UI functionality.

This GitHub exists to show off some of the independent projects that I have worked on as a means of improving my technical abilities. This involves MATLAB, C++, and Python based projects with some using Object-Oriented Programming.

## **Mathworks Engineering Innovation Project 208: Raceline Optimization**
| Oblong Test | Kidney Bean Test |
:--------------:|:--------------:
![Raceline Optimizer Example Oblong](https://github.com/borealis31/MW208_AUTON_RACECARS/blob/main/ExampleMedia/OblongTestEXAMPLE.gif) | ![Raceline Optimizer Example KidneyBean](https://github.com/borealis31/MW208_AUTON_RACECARS/blob/main/ExampleMedia/KidneyBeanTestEXAMPLE.gif)

This project's inspiration comes from the [Mathworks EI Project 208](https://github.com/mathworks/MathWorks-Excellence-in-Innovation/tree/main/projects/Path%20Planning%20for%20Autonomous%20Race%20Cars) and uses a localized mathematical approach to optimizing the curvature of a raceline around a track. Extensive literature was reviewed to gain inspiration for how to approach this problem, and I settled on a localized approach due to its simplicity and effectiveness in implementation. The raceline is optimized iteratively until a certain threshold is met; at which point, the program begins to develop a velocity profile. This velocity profile is optimized for the curvature of the optimized raceline and is constrained by maximum tangential and centripetal forces. This output can be returned as a real-time video of the "car" going around the track as well as a plot PNG of the velocity profile colorized to indicate high speed and low speed regions. If you're interested in learning more, [check out the code here](https://github.com/borealis31/MW208_AUTON_RACECARS) as well as some of the videos [here](https://www.youtube.com/playlist?list=PL4JPcckwBugJQonUbjWYa-0Lu1W8ki1SL).

## **Matlab Port Sorting Simulator**
![Port Simulator](https://github.com/borealis31/The_Shipyard/blob/main/matlab/testCases/testCase1Output.PNG)

This project's inspiration comes from my interest in learning more about Object-Oriented Programming as well as Recursive Function design. This code contains three classes and three functions — one of which is a recursive merge sort function designed to sort objects of a certain class by two different properties depending on the application. The code is well documented and uses built-in MATLAB functions to identify errors in function and class implementation. If you're interested in learning more, [check out the code here](https://github.com/borealis31/The_Shipyard).

## **RasPi Zero W Rover**
![RPZWCar](https://github.com/borealis31/borealis31/blob/main/20210318_171800.jpg)

The inspiration for this project comes from my previous experience in the FIRST Robotics Competition. This is a fairly simple project with complex wiring. Since I didn't have any modules or drivers for DC motors, I used two L298D H-Bridge components, a breadboard, and a whole lot of wires. This project is powered by a RasPi Zero W which receives IR signal and iteratively acts based on received signal to control direction. It is capable of moving forward-backward, turning, and strafing. See [the code for this here](https://github.com/borealis31/robo_rpi0w).

## **Matlab .txt Analyzer (Statistical Data Analysis)**
![Statistical Text Analyzer](https://github.com/borealis31/stats_analytics_school_project/blob/main/pride_and_prejudice_results.png)

The inspiration for this project comes from a Statistics course taken during my second year of university. I created a MATLAB script to analyze public domain text files hosted by Project Guttenberg and to find statistical characteristic values for word length. See [the code for this here](https://github.com/borealis31/Engineering-Statistics_Term-Project).

📫 You can reach me at jakeb.chouinard@gmail.com or jakeb.chouinard@uwaterloo.ca

<!---
borealis31/borealis31 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
