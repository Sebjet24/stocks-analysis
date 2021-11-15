# stocks-analysis

## Overview of Project

### Purpose

 - Steve wants to expand the dataset I previously made for him to encompass the entire stock market over the years 2017 and 2018 in order to undertake some further study for his parents. So I refractored the macro I had previously created to loop through all the date in a much smoother and quicker way than previously. Essentially I am going to be rewriting some portions of the code to work more effectively than previously before. By changing the code to 

![Capture_2](https://user-images.githubusercontent.com/91230277/141708359-67dfe875-e187-4d52-8d9c-33a1f6d77b6a.PNG)

## Results

### Refractored Code Process

 - I refactored the code in the module so you can loop through the data one time and collect all of the information. The code runs much faster than the original. First I made the 3 arrays:tickerVolumes, tickerStartingPrices, and tickerEndingPrices. Next, I made the tickerVolumes set to 0.

![Capture](https://user-images.githubusercontent.com/91230277/141710891-d8ee1429-e388-49a2-814f-ed2e313eb3eb.PNG)
 - I then created a for loop that will loop over all the rows in the spreadsheet.

![Capture_2](https://user-images.githubusercontent.com/91230277/141711443-b735062f-f3e4-4006-9c9d-4f1cb5ff3ad4.PNG)
 - Afterward I wrote a script that increases the current tickerVolumes (stock ticker volume) variable and adds the ticker volume for the current stock ticker.

![Capture_3](https://user-images.githubusercontent.com/91230277/141711514-9285293a-d6e3-4464-adf4-7fba9386a792.PNG)
 - Then I finished the code by printing out onto the "All Stocks Analysis" the finished results for each category.

![Capture_3](https://user-images.githubusercontent.com/91230277/141711575-23fa3c72-1493-4187-9d72-ebab56301668.PNG)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/91230277/141711723-224f0c61-8e83-4851-b87d-f0238a33dca9.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/91230277/141711724-265b94ad-a7ef-4bf0-a970-d9cd25ef8812.png)

## Summary

 - Code refactoring is an excellent approach to make your code more readable, understandable, and less difficult. The disadvantages of refactoring is you may have no clue how long the procedure will take to finish. It might also put you in a scenario where you don't know where to go from there.
 - The advantages of refactoring this code was that the code loops through everything once. It also processes much quicker because it is going through the data less times. It is about as easy to ready as the code before though. The disadvantages of refactoring this code is honestly that it took a bit more time to code than the first. I don't see any other disadvantage than that.
