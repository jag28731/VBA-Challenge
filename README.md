# VBA of Wallstreet

## Overview of Project
Steve is looking to analyze the stock market over the last couple of years for his parents.
  
### Purpose
The purpose of my analysis was to visually show which stocks would be the best option for Steve's parents by comparing the stocks for the last couple of years.  Having all the data in a spreadsheet allows Steve to quickly compare which stocks would be the best option for Steve's parents.
  
## Results
Steve asked to compare stocks for his parents over multiple years. I was able to create a program to compare stocks for whichever year Steve would like to see the stock results. 
 
### Analysis of 2017 Stocks
- For 2017, I ran the program I made to compare the stock total daily volume as well as the return on the stocks. Any stocks that came back with a positive return, I change the cell to green to make it easy to analyze. Any stock that had a negative return was changed to red. By comparing the results for 2017, I determined that DQ had the best return followed by SEDG.

![2017](https://github.com/jag28731/VBA-Challenge/blob/main/Resources/VB_Challenge_2017.png)

### Analysis of 2018 Stocks
- For 2018, I used the same program but changed the year to 2018. The results of 2018 return was very different. Only two stocks had a positive return, ENPH and RUN. Based on my analysis, for 2018, RUN had the highest return followed by ENPH. 

![2018](https://github.com/jag28731/VBA-Challenge/blob/main/Resources/VB_Challenge_2018.png)

### Analysis of 2017 and 2018 Stocks
- After looking at both 2017 and 2018 separately, I wanted to compare which stocks would be the best overall for Steve's parents by looking at the returns together for 2017 and 2018. Only ENPH and RUN has a positive return for both 2017 and 2018. In 2017 ENPH had a return of 129.5% and RUN had a return of 5.5%. In 2018 ENPH had a return of 81.9% and RUN had a return of 84%. I recommended to Steve's parents that ENPH would be the best stock as it had a positive return in both years and overall highest return percentage.

## Summary
- What are the advantages of refactoring code?
1. Quicker result feed back time.
2. Can analyze a larger database. 
3. Not reinventing the wheel, using previous code for larger datasets 

- What are the disadvantages of refactoring code?
1. Understanding which code needs to be refactored.
2. Ensuring all code is complete and in the right section.

- How do these pros and cons apply to refactoring the original VBA script?
1. I was able to analyze multiple years of stocks is a faster manner. The multiple years contained more datasets which the refactored code allowed me to analyze quickly. 
2. I initially had a single line of code in the wrong section, which led to a run time error and alot of debugging until I figured out the answer.
3. There was new code that I didn't completely understand, I had to research code to ensure I was using it correctly, which took time. 

