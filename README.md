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
Let's first take a look at the _Color_ card.

You may already know that changing the color of something is one of the most effective ways to make it more interesting. Tableau allows you to change the color based on values of the data, which can make it easier for the viewer to mentally separate different categories of data. To add color detail to your viz, simply drag the measure or dimension and drop it on the _Color_ card. Once you have applied the color to the data, you can customize it by clicking on the _Color_ card.  

#### Colors
To edit the color palette, you can click on the button that reads __Edit Colors__. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/color_card.png" alt="Image of the marks card which contains three elements: Color, Opacity, and Effects" height="150px"> 

Here you will see a few options:  

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/edit_colors.png" alt="Image of the Edit Color window which contains the color selections to apply to the elements of the viz" height="350px"> 


* __Select Data Item__ - Selecting a data item will allow you to select the color for that specific point
* __Select Color Palette__ - The drop-down menu will allow you to select from many color palettes, which are themed color groups and different combinations of colors. Some of the color palettes are sequential, while others are divergent giving you many options to represent the data with color.
* __Assign Palette__ - Clicking on the _Assign Palette_ button will simply assign the selected color palette to the data.  

> Editing colors in a viz is somewhat intuitive. Take a little time and play with the colors and look at the result to get familiar with the many options. Once you have configured the colors the way you want them to look, you will want to click on _Apply_ and _OK_ to save the changes.

Other attributes of a vizes color which can be customized are:
* __Opacity__ - The opacity slider allows the user to adjust the color to be more or less "see-through." This can be useful when the viz is overlapping another item and you need to make the color see through to allow for the hidden information to be seen.  
* __Effects__ - The effects section will allow you to add a color border to the items the color is applied to. The border helps to increase the visibility of the edges of the viz's components.  

## Size
The _Size_ card has a slider which will allow you to adjust the size of the viz components. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/size_slider.png" alt="Image of the slider used to adjust the size of the elements of the viz" height="100px"> 

For example, if you have generated a bar chart, the _Size_ slider will adjust the width of the bars. The _Size_ slider will also adjust the size of shapes in a scatter plot. Additionally, you can drop a measure in to the _Size_ card, and the size of the components in the viz will be dependent on the value of the data.

## Label
The _Label_ card allows you to display labels in the viz to make it easier to identify the components of the viz. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/label_attributes.png" alt="Image of the label attributes that you can customize" height="350px">

You can change the attributes of the labels such as _Font_, _Justification_, and which labels to display. You can also add custom text to make it more informative like adding a dollar sign before a numeric value to denote currency.

## Detail  
The _Detail_ card allows you to add more detail to the viz, as the name suggests. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/detail_card.png" alt="Image of the slider used to adjust the size of the elements of the viz" height="100px">

This is helpful to identify sub categories of a field. In the case of a bar chart, the bar will be divided into the sub-categories to illustrate the distribution of that particular category.

## Tooltip  
The _Tooltip_ card allows you to control the information in the pop-up box when the viewer hovers over an element of the viz. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/tool_tip.png" alt="Image of the controls used to adjust the tooltip details of the viz" height="450px">

You can customize the information with standard text tools like _Font_, _Size_, _Color_, etc. You can also customize the labels and field names so if your field names are not clear, you can rename them to make it easier for the viewer to understand what the data represents.  

## Summary
Now that we have a good idea of the tools Tableau has to customize our viz's, we are ready to test out what we have learned and try the tools to see how they can affect the way we convey the information about the data we are presenting.
