# Narrative-visualization
Interactive slideshow using d3.js

View visualization by clicking here : https://pratyushkr9420.github.io/Narrative-visualization/

### About the Visualization

The visualization shown is an Interactive Slideshow. User can view the full data and interpret it based on the categories of vehicles for which the emission study was done. The visualization is based on a dataset from the Environment Protection Agency which contains horsepower, CO2 emission and vehicle type information vehicles manufactured in 2017. The visualization serves the purpose of user to interact data in order to make the decision regarding purchasing your next vehicle with an effort to make the balance between horsepower and environment damage by carbon dioxide emission. 

### Scenes

There are three scenes in the narrative visualization. They follow the same template and layout for visual consistency. The visualization displays data consistently with frame of height 510px, width 980px.The axes used in the plot were made in linear scale. The ticks used in the plot are uniform in size and color for entire visualization. The scenes were designed for smoot transitions without any instance when the user gets disoriented. The first scene highlights the overall trend of the data, second shows the trend in the data being consistent based, and finally in scene 3 ask the user to reflect on this trend and perhaps consider it when making his next 

### Annotations

Annotations are used highlight trends and gain further in-depth insights and conclusions from the data. They have been made bold and have uniform font size across the entire narrative visualization. Visualization’s scene 1 has annotation to highlight the general trend in the data that increase in horsepower will increase the carbon dioxide emission. Visualization’s scene 2 allows for mouseover the data to see the trends for Cars, Trucks or both. Visualization’s scene 3 has annotation which helps user interact and decide about future purchase decisions. 

### Parameters

Parameter about category of the vehicle can be obtained by mousing over any data point. With this mouseover action you can see the trend of increase in horsepower of the vehicle with carbon dioxide emission. When the current state of the vehicle type changes, and the data points of other vehicle categories opacity is set to 0.01 and when mousing off the data point the current state changes again and opacity reverts for data points to 1.

### Triggers

The buttons are situated at the top of the visualization which act as triggers to change scenes. Clicking one of these buttons marks a user event which changes the current state of the visualization by changing the visualization scene. Movement of the mouse over the other buttons makes them highlighted which indicates that you can click on them which allows for switch of slides. Triggers are also used on data points as user event of "mouse over" a data point to change current state of the chart by applying opacity of 0.01 to all data that is not of the current mouse over vehicle data type. Upon "mouse off" the opacity of all data points goes back to 1. 


### References

Tutorial for building a stepper page used as reference:
http://vallandingham.me/stepper_steps.html


