# Stock Analysis

<p align = "center">
<img src = "https://raw.githubusercontent.com/JoseCalucag/stock_analysis/master/Resources/stock.jpeg">
 </p>

## Overview of the Project
### Explain the purpose of this analysis.
The purpose of this analysis is to see if there are alternatives to a tried and tested method. I have worked on a macro where I'm able to see the progess of a dozen stocks over the course of a year. Albeit it does work and does it's job with accurate results, I was presented with the challenge of refactoring the code. By doing so, is it possible to find another way of doing the same task, but more efficiently and maybe even more less time consuming and less resource intensive?

## Results
### Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

### What we got
First let's take a look at the Original Code results. On first glance, we see three columns: 1) the Stock in it's abbreviated name, 2) the Total Daily Outcome and 3) it's return for the day based upon it's starting price to it's closing price.  

**2017 Original Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20Original%20Sheet.png" width="300" height="300">

**2018 Original Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20Original%20Sheet.png" width="300" height="300">

And on first glance, we see some deliverables that we can use. However, we can always do better. With the original code, the macro runs through a single If statement to get this outcome. And, because it goes through one pass, it will come with one total income; which would be it's closing price. 

### What we can do
So, in knowing with we already have, how can we make more impactful numbers in a more efficient way? I went back to the drawing board to see what can be refactored and what I came up with to use 3 nested If statements within the original If statement so that we can go collected the daily outcomes of the stock to create a total sum. That way, instead of just looking at the closing price, we can see the total outcomes of the day for that stock. Albeit inflated, this can show how much was invested in a stock and if it's worth it to buy in based upon it's daily outcomes.

**2017 Refactored Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20sheet.png" width="300" height="300">

**2018 Refactored Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20sheet.png" width="300" height="300">

## Time
More importantly, we do see that was a performance efficiency. Within the code, I coded in a timer to see how long it would take VBA to run the code for each year, before and after the refactoring. You can see by these macro pop-ups, that the refactored code is running 1/6 of the time it takes for the original code to run.

**2017 Original Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20-%20Original.png" width="600" height="230">

**2017 Refactored Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20-%20Challenge.png" width="600" height="230">

**2018 Original Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20-%20Original.png" width="600" height="230">

**2018 Refactored Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20-%20Challenge.png" width="600" height="230">


## Summary
So, to conclude simply, there's always another way to crack an egg. By refactoring a working code, we can find different ways to relay the same results, but in a more impactful and a more efficient way. Why look at just one thread of data when you can see a whole days worth of data? Why just wait for data when you can impliment methods to make it work faster to provide quicker and up-to-the-minute results? We should not accept what can just be done when the resources are out there to create something better.

