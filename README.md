# Stock-Analysis

## Overview of Project
In this module we are looking to make the module 2 stock vba code more efficient and measure the performance compared to the original.

## Results

To make this more efficient, we start by creating arrays to store our outputs and clearing them when the code starts in case we are analyzing multiple years.



From there we calculate the ticker volume, start and end price similar to our original code but changing where the data is stored. Once those are  all calculated and stored in their respective arrays, we output the data similarly to the previous code. Then we tested and compared times to the previous version
![Original.png]([https://github.com/1fatpanda1/stock-analysis/blob/main/Resources/Refract_results.png])
![Original.png]([https://github.com/1fatpanda1/stock-analysis/blob/main/Resources/Original_results.png])
## Summary

When ran compared to the normal code, the refract code is significantly faster than the original. This is due to eliminating the need for a nested for loop each time we search for the next ticker using the refracted code.  I imagine though that compared to the normal code, the refracted code uses more memory due to storing the data as it runs through each ticker while the normal code clears that memory each iteration. 

