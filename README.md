# Tableau - Customizing Worksheet

## Introduction
Creating visualizations is just one part of drawing insight from data. Your visualizations, or in the world of Tableau, __"Vizes"__ need to have descriptive information as well as formatting that makes them easy to read and understand. As we learned in the previous lesson, Tableau will generate a basic _"viz"_, but it is up to you to make that viz easy to understand and find the information your audience will be seeking. In this lesson, we will dive deeper into the formatting and coloring of your vizes so that your audience and stakeholders will be able to quickly and easily find and understand the information you are attempting to highlight for them.

## Objectives
You will be able to: 
* Locate the Marks Card and identify the various components and their use
* Add descriptive detail using _Label_ and _Tooltip_
* Customize the viz by changing the color, size, and font of various components of the viz

## The Marks Card
We have already taken a look at the _Marks Card_ and briefly looked at the functions it holds. Now we will dive deeper into the many uses for the elements inside.  
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/marks_card.png" alt="Image of the marks card which contains five elements: Color, Size, Text, Detail, and Tooltip" height="150px">

## Color
Lets first take a look at the _Color_ card. You may already know that changing the color of something is one of the most effective ways to make it more interesting. Tableau allows you to change the color based on values of the data, which can make it easier for the viewer to mentally separate different categories of data. To add color detail to your viz, simply drag the measure or dimension and drop it on the _Color_ card. Once you have applied the color to the data, you can customize it by clicking on the _Color_ card. 

#### Colors
To edit the color palette, you can click on the button that reads __Edit Colors__. Here you will see a few options:
* __Select Data Item__ - Selecting a data item will allow you to select the color for that specific point
* __Select Color Palette__ - The drop-down menu will allow you to select from many color palettes, which are themed color groups and different combinations of colors. When selecting from these color palettes, the colors will be assigned by Tableau and can be changed if you wish. Groups of different colors are generally used for discrete data which has no specific order, such as a category or department. Toward the bottom of the list you will color palettes which are better suited for data which has an order such as dates or times. If your data is continuous, Tableau will assign a continuous color spectrum which can be edited further by adjusting the various number parameters.
* __Assign Palette__ - Clicking on the _Assign Palette_ button will simply assign the selected color palette to the data.

Once you have configured the colors the way you want them to look, you will want to click on _Apply_ and _OK_ to save the changes.

#### Opacity
The opacity slider allows the user to adjust the color to be more or less "see-through." To make this change simply click on the slider and adjust to the level you desire, or you can type the value in directly if it is known. This can be useful when the vis is overlapping another item and you need to make the color see through to allow for the hidden information to be seen.


#### Effects
The effects section will allow you to add a color border to the items the color is applied to. The border helps to increase the visibility of the edges of the viz's components. You can also apply a _Halo_ to some items which will a give a secondary border to some shape components.

## Size
The _Size_ card has a slider which will allow you to adjust the size of the viz components. For example, if you have generated a bar chart, the _Size_ slider will adjust the width of the bars. The _Size_ slider will also adjust the size of shapes in a scatter plot. Additionally, you can drop a measure in to the _Size_ card, and the size of the components in the viz will be dependent on the value of the data.

## Label
The _Label_ card


```python
## content for topic title 3
```

## Summary
Summary goes here
