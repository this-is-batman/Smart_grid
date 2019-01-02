# Observation stage 1
Now we have added `Average temperature` as a probable factor for calculating energy consumption.

We first represent the relation between `Energy Consumption` and `Average Temperature` in a scatter plot.
The scatter plot is shown below:-

![Image5](https://github.com/this-is-batman/Smart_grid/blob/master/Plots/energyvstemp.png)

Now, we are doing **Linear Regression** by using `Energy consumption` as the **dependent variable** and `Population Density` , `GDP`, `Average temperature`as the **independent** variables. The results are:-

![Analysis_stage2](https://github.com/this-is-batman/Smart_grid/blob/master/Images/analysis_stage2.png)

Here, we can see that the **correlation coefficient** is **0.5678**, which gives a better result than the previous phase of experiments. As evident from the previous trials, we can **improve** the correlation coefficient by **removing** the **outliers**.

After removing the **outliers** from the `average temperature` data, we get the following results:-

![Analysis_stage3](https://github.com/this-is-batman/Smart_grid/blob/master/Images/analysis_stage3.png)

The **correlation coefficient** increases to **0.6603** and the **root mean squared error** is much less compared to previous.Thus we can see an overall improvement.

### Note

If we use `Random Tree` classifier, the **correlation coefficient** is **0.922**, for `REP tree` the **correlation coefficient** is **0.8522**, for `Random Forest` classifier, the **correlation coefficient** is **0.9126**.Thus, these classifiers can also be used in the future.

As uploaded in the [Ipynb file](https://github.com/this-is-batman/Smart_grid/blob/master/Observations/observations.ipynb), we can see that there is strongest **correlation** between `Energy Consumption` and `GDP`, which clearly suggests that GDP is one of the most important determining factors when predicting future **Energy Consumption** values. The **correlation** between `Energy Consumption` and `GDP` is `0.72`.
