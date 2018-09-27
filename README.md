# Alibaba-challenge-2018
# Problem Description:

The scenario is set in the future—in the year of 2050, a world where the invention of “anti-gravity engines” has led to the creation of unmanned balloons as the preferred logistics solution. However, because of the UK’s complex meteorological conditions, the balloons are occasionally delayed, damaged or even destroyed by extreme weather conditions causing disruption and loss. The contestants will be challenged to create algorithms that can plan flight routes for these balloons to navigate the endless variation and changeable nature across the UK to optimize their delivery schedules and costs.







# Objectives:

## Develop an efficient navigation algorithm for cargo balloons while avoiding volatile weathers

### 

10 balloons set out daily from Hyde Park London to 10 destination cities in Britain. However,if the wind is too strong, cargo balloons will be destroyed (wind speed >= 15)



### 

The Met Office runs 10 different forecast models every day, However, the accuracy of these predcitions is not perfect



### 

For simplification,we divided the coverage area into blocks,Each block is expressed by an x-axis coordinate and a y-axis coordinate (x,y)



### 

The travel time across each block is fixed by two minutes



### 

Balloons can move up, down, left, and right from the current block or stay at the current block, but cannot move diagonally.



### 

The travel duration is restricted to 18 hours [03:00-21:00)



### 

The final score on the leaderboard will be the total amount of travel time in minutes for all successful balloon flights, plus the total amount of penalties. The lowest score wins the leaderboard. 



### 

The objective function = 24 ![$\times$](https://render.githubusercontent.com/render/math?math=%5Ctimes&mode=inline) 60 ![$\times$](https://render.githubusercontent.com/render/math?math=%5Ctimes&mode=inline) number of crashes + total travel minutes of successfully arrived balloons







# PATH FINDING
1. path_finding.py : this is the main code for finding optimal path. Simply import this class.
2. example for using path finding function.ipynb : this file shows how to use the functions from path_finding.py
