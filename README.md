# Stock-Analysis

## Overview of Project
In this module we are looking to make the module 2 stock vba code more efficient and measure the performance compared to the original.

## Results

To make this more efficient, we start by creating arrays to store our outputs and clearing them when the code starts in case we are analyzing multiple years.

![arrays.png](https://github.com/1fatpanda1/stock-analysis/blob/main/Resources/Arrays.png)

From there we calculate the ticker volume, start and end price similar to our original code but changing where the data is stored. Once those are  all calculated and stored in their respective arrays, we output the data similarly to the previous code. Then we tested and compared times to the previous version

### Refract

![Original.png](https://github.com/1fatpanda1/stock-analysis/blob/main/Resources/Refract%20results.png)

### vs Original

![Original.png](https://github.com/1fatpanda1/stock-analysis/blob/main/Resources/Original%20results.png)


## Summary

When ran compared to the normal code, the refract code is significantly faster than the original. The refract code runs faster than the original due to eliminating the need for a nested for loop each time we switch tickers. On the other hand, I think it would use more storage memory than the original version due to storing the data before posting each result. 
