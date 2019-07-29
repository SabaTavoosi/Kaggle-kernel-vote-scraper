# Kaggle kernel vote scraper  

*Note: This app is not endorsed by Kaggle.*

This web application estimates the number of valid votes towards medals [Kaggle kernels](https://www.kaggle.com/kernels) have. It will also give some additional information such as how many more votes you need for medals, votes by each tier, as well as some summary statistics. You only need to to input the kernel URL that you want to extract information from and the app will take care of the rest. 

You can test the app <font size = '3'> **[here](https://sabatavoosi.shinyapps.io/kaggle-vote-scraper/)**</font> or download the **.Rmd** code and run it in R. 

Demo picture:
[![Imgur](https://i.imgur.com/N44uH9q.png)](https://sabatavoosi.shinyapps.io/kaggle-vote-scraper/)

#### How the app calculates valid votes
The app derives the number of valid votes using an oversimplified process of deducting votes by novices from total votes and should, thus, not be taken as being completely accurete as it does not take into account any other rules (such as self-votes, old votes, or any other secret voting rules Kaggle has). If you appear to have enough votes but not a medal it is because the app does not take into account these other rules in its calculations and has derived at a wrong valid vote estimate.

The app should just be used for fun and there is no guarantee of accuracy.
