# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consists of multiple steps:

Applying a color mask
Performing edge detection
Selecting regions to search for lane lines
Using the Hough transform to find line segments
Extrapolating the lane from the line segments provided by the Hough transform


### 2. Identify potential shortcomings with your current pipeline

Highly sensitive to color
Requires hard coded regions
Highly dependent on lane location

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

Use information from past frames
Better tuned hough transform and edge detection
Automatically calculate region
Automatically calculate color mask range
