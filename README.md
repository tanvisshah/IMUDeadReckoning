# IMU Dead Reckoning

This project aims to build a dead-reckoning based indoor localization system. Data from a phone's IMU (specifically, accelerometer and gyroscope is collected and processed.
There are three major modules needed to determine the user's trajectory:
 
__1. Step Count Module__

__2. Walking Direction Module__

__3. Step Length Module__

Once these three variables are determined, the trajectory plot of the user can be easily estimated. The data used is from 6 different walking routes aroung the University of Illinois,
Urbana-Champaign campus. The repository contains Accelerometer and Gyroscope readings for these 6 routes and a Jupyter Notebook File which reads and processes the data and
plots the estimated trajectories.
