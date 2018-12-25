# Observations

At first, we examine the following scatter plots:-

**1.** **Plot of Energy Consumption vs GDP**

![Image1](https://github.com/this-is-batman/Smart_grid/blob/master/Plots/energyvsGDP.png)

**2.** **Plot of Energy Consumption vs Population Density**

![Image2](https://github.com/this-is-batman/Smart_grid/blob/master/Plots/energyvspop.png)

Now if we do **Linear regression** using `Energy Consumption` as **dependent** variable and `Population density` and `GDP` as **independent** variables, we get the following results:-

![analysis_stage0](https://github.com/this-is-batman/Smart_grid/blob/master/Images/analysis_stage0.png)

Here we see the **correlation coefficient** is **0.4604** which is bad and the **root mean squared error** is very high which suggests that for the next attempt we should go for a different set of factors or that the factors considered do not really affect the energy consumption.

Now, for the second attempt, we can see that by removing the **outliers**(one extreme in `GDP` value and one exterme in `energy consumption` value) the **correlation coefficient** improves to **0.6858** as is visible in the following results:-

![analysis_stage1](https://github.com/this-is-batman/Smart_grid/blob/master/Images/analysis_stage1.png)

**After removing the outliers:-**

**Plot of energy Consumption vs GDP**

![Image3](https://github.com/this-is-batman/Smart_grid/blob/master/Plots/energyvsGDP1.png)

**Plot of energy consumption vs Population Density**

![Image4](https://github.com/this-is-batman/Smart_grid/blob/master/Plots/energyvspop1.png)

**Thus we can clearly see that the value of correlation coefficient improves by removing the outliers.**

```This data is only for the year 2013, the data for years 2014, 2015, 2016 are yet to be added.```
