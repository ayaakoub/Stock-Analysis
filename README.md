# An Analysis of Stocks Data for 2017 and 2018 

## Overview of Project

Our friend Steve has just graduated with his Finance degree and he is asking for our help with his first client, his parents. Steve's parents are passionate about green energey and want to invest in DAQO New Energy Corp "DQ". Steve thought it would be a good idea to diversify their funds and analyse a handful of green energy stocks from 2017 and 2018.

The challange can be easily achived by understanding concepts suchs as for loops, nested for loops and arrays, all within VBA. The code was further refactored to elimiated the nested for loops. 


## Results

The results show that DAQO/DQ had the highest return in 2017, 199%, but in 2018 it had gone down significantly and the 2018 return was -62%. Although most stocks seemed to have negative returns in 2018, ENPH was the 3rd highest reutrn of 2017 at 129% and a very good return in 2018 at 82%. Going with DQ would have been a mistake.

The full results from 2017 and 2018 analysis can be seen below:

![2017 Results](https://github.com/ayaakoub/stock-analysis/blob/main/Resources/2017_Results.PNG)
![2018 Results](https://github.com/ayaakoub/stock-analysis/blob/main/Resources/2018_Results.PNG)


## Summary

Refactoring code made the analysis run more than 10 times faster as can be seen from the below run times showing the orignal and refactored code run times, 1.187 seconds and 0.176 seconds, respectively.

![2017 Original](https://github.com/ayaakoub/stock-analysis/blob/main/Resources/2017_Original_Run_Time.PNG)
![2018 Refactored](https://github.com/ayaakoub/stock-analysis/blob/main/Resources/2017_Refactored_Run_Time.PNG)

Both codes had their advantages and disadvantages. Although the refactored code runs faster, using a ticker index like we did may have not been as intuitive. The nested for loops from the original analsyis can also be confusing at times when trying to fully understand them. The refactored code flowed really easy and did not have a lot of else ifs and was mostly straight to the point. The original code did not require building arrays and was simple enough when it was overwriting the same variable over and over. 
