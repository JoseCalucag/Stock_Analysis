<h1 align = "center"> Stock Analysis
</h1>

<p align = "center">
<img src = "https://raw.githubusercontent.com/JoseCalucag/stock_analysis/master/Resources/stock.jpeg">
 </p>

# Overview of the Project
I wanted to see if there is an alternative to an established method that runs analysis of a dozen stocks. Although this method does work and shows accurate results, is it possible to do the same task but more efficiently that takes less time and less resource intensive. To do this, I refactored the code and created a macro that will track the time for the code to run to then compare results. 

# Preprocessing
At first glance of the original code results, the output has three columns: 1) the Stock in it's abbreviated name, 2) the Total Daily Outcome and 3) it's return for the day based upon it's starting price to it's closing price.  

**2017 Original Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20Original%20Sheet.png" width="300" height="300">

**2018 Original Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20Original%20Sheet.png" width="300" height="300">

With the original code, the macro runs through a single If statement to get this outcome. And, because it goes through one pass, it will come with one total income; which would be it's closing price. 

# Results

### The Refactored Code 
So, in knowing with we have, how can we make more impactful numbers in a more efficient way? By refactoring the code by utlizing 3 nested If statements within the original If statement, we can see the total outcomes of the day for each stock and not just the closing price. Albeit inflated, this  shows how much was invested in each stock and if it's worth it to buy in based upon it's daily outcomes.

**2017 Refactored Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20sheet.png" width="300" height="300">

**2018 Refactored Results** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20sheet.png" width="300" height="300">

### Time
More importantly, we do see there was a performance efficiency. I created a macro that times how long it would take VBA to run the code for each year and for the the origial code and for the refactored code. By looking at the macro result pop-ups, the refactored code is running 1/6 of the time it takes for the original code to run.

**2017 Original Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20-%20Original.png" width="600" height="230">

**2017 Refactored Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2017%20-%20Challenge.png" width="600" height="230">

**2018 Original Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20-%20Original.png" width="600" height="230">

**2018 Refactored Code** <br/>
<img src = "https://github.com/JoseCalucag/stock_analysis/blob/master/Resources/2018%20-%20Challenge.png" width="600" height="230">

# Summary
There's always another way to crack an egg. By refactoring a working code, I found an alternative to relay the same results, but in a more impactful and a more efficient way. By knowing this is possible, we can expand its application to process a whole bigger dataset. And why stop here? Why  wait for data when you can impliment methods to make it work even faster to provide quicker and even real time up-to-the-minute results? We should not accept what can just be done when the resources are out there to create something better.
