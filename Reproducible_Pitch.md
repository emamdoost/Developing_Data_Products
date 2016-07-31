Developing Data Products Course Project: Shiny Application and Reproducible Pitch
========================================================
author: Alireza Emam Doost
date: 31 July 2016

Overview
========================================================

This was built for the course Developing Data Products as part of the Coursera Data Science Specialization.

The shiny app developed for this assignment is avalilable at: https://doost.shinyapps.io/shinyapp/

The source codes of ui.R and server.R and also Rpresentation are available on the GitHub repo: https://github.com/emamdoost/Developing_Data_Products

BMI Model
========================================================

The body mass index __(BMI)__ is calculated based on the following formula:  

Bodyweight in kilograms divided by height in meters squared  
  
BMI = x KG / (y M * y M)  

Where:  

x=bodyweight in KG  
y=height in M  


BMI Result
========================================================

__Example:__  

For 178 cm height und 75 kg weight: 

BMI = 75 / (1.78 * 1.78) = 23.67  

- BMI <18.5       : Underweight    
- BMI [18.5-24.9] : Normal weight    
- BMI [25-29.9]   : Overweight    
- BMI >=30        : Obesity    
 
Shiny App: Interactive BMI Calculator
========================================================

* Sidebar panel  

 - numericInput: Value of Weight in KG   
 - numericInput: Value of Height in M   

* Main panel   

 - Short description of BMI value
 - Make calculation on server side
 - Display the calculated BMI
 - Display Diagnostic
 
 
