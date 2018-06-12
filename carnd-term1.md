# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report



### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 6 steps like below:
1. Color Selection
 - To make image to gray scale
2. Blur
 - To make image in smooth.
3. Canny Edge Detection
 - To get edge of object
4. Region Masking
 - To reduce region for calcuating
5. Hough Transform
 - To get lane
6. Add to original...
 - To add lane to original image

Additionally, I add some code to enlarge lane which is shorter than other side.


### 2. Identify potential shortcomings with your current pipeline

It works but not good.

There are some paramters to improve performace but I couldn't find the best solution.


### 3. Suggest possible improvements to your pipeline

I think that I need to understand that algorithms of Canny and Hought Transform in deeply.

I make code to enlarge lane I thought I could control min, max values to get good lane.

I think Min/Max algorithms should be changed.

