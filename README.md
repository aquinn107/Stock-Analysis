# Stock Analysis

## Overview of Project
Performing analysis on 2017 and 2018 stock data to help determine the best stock options.
### Purpose
  This analysis was completed because Steve's parents have recently shown interest in investing in some stock options. After taking a look at their first choice of the "DQ" stock, Steve agreed that the stock had not performed as well as he'd like to see; there was a 63% drop in 2018 that was alarming. I wanted to review all the stock data to compile a list of some better options for Steve to present to his parents.
## Results of Analysis

### 2017 Analysis
   In reviewing the 2017 data, I was able to determine a few viable stock options that may suit Steve's parents well. While "DQ" did have the highest overall increase of 2017 at almost 200%, a few other options did stick out. In the below chart we can see that "SEDG" and "ENPH" had amazing returns, both well over 100%; "SEDG" at 185% and "ENPH" at 130%!

![2017_All_Stocks](https://raw.githubusercontent.com/aquinn107/Stock-Analysis/main/Resources/2017_All_Stocks.png)


### 2018 Analysis
   Based on the 2018 stock data, we can review the stocks that stood out in the 2017 data. Here we can clearly see the 63% loss that "DQ" had experienced. "SEDG" did return with an 8% decrease from the previous year, but "ENPH" continued to have a great year at almost an 82% increase in return! This certainly seems like a great option for Steve's parents to invest in that seems to be consistent based on the data reviewed. 

![2018_All_Stocks](https://raw.githubusercontent.com/aquinn107/Stock-Analysis/main/Resources/2018_All_Stocks.png)

### Future Opporunities
   The code that was used to create this analysis was pretty complex. I was able to reuse the same code we used to analyze just the DQ data, but provided a function that would allow it to be used continuously. Since stocks frequently change, new companies are formed, and years pass, this analysis can be reworked to provide you insight for years to come. This will help you keep an eye on your stocks and assets and make necessary moves based on the data entered.

In this code, we were also able to include a "Run" and "Clear" button. This makes it easy whether you'd like Steve to review your stocks, or if Steve's parents want to crunch the numbers themselves! Another feature that was added, was a nice popup that states how long the analysis took to complete. With this, you can determine how long each run takes as the data continue to grows over time.
<img src="https://raw.githubusercontent.com/aquinn107/Stock-Analysis/main/Resources/VBA_Challenge_2017.png" width="400" height="200"/> <img src="https://raw.githubusercontent.com/aquinn107/Stock-Analysis/main/Resources/VBA_Challenge_2018.png" width="400" height="200"/>

## Summary

   In conclusion, because we were able to refactor the original code used to run analysis on the "DQ" stock we know we are able to piece the code apart to watch particular stocks more carefully which can help catch any potential losses or celebrate substantial gains. As we all know, the market does change over time, and as new businesses come and go, the advantage we have is that we can easily refactor this same code again to be able to incorporate them into this analysis without issue. While the original code we used did have its advantages by looking a bit cleaner and more straightforward, the refactored code was able to do the same amount of work, if not more, at a quicker rate than the first version.
