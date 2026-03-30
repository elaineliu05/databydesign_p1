# Predicting Primary Productivity: Helping Forecast Climate Change Using Our Oceans

## Hook

You've definitely heard that climate change is a big deal. A problem at this massive scale is going to involve complicated climate models, extensive computation, and tons of data. But what if we zoom in on just one piece of the puzzle? More specifically, narrowing it down to a specific problem area - the ocean - makes things a lot more manageable. This is possible using primary productivity, aka the photosynthesis done by phytoplankton, making forecasting climate change a lot more measurable. 

## Problem Statement

You might not have known this, but the oceans have a pretty significant influence on climate change and help mitigate it. For instance, through primary productivity, the oceans help capture a large portion of atmospheric carbon and turn it into energy. So the big question you might be thinking is - how much carbon will the ocean keep absorbing in the future?

If you can forecast primary productivity values, you can see how much carbon the oceans will continue to absorb and help us mitigate climate change. But to do this, you need long-term time series datasets. In this work, we will use data from the Bermuda Atlantic Time Series study. They are one of the longest-running programs gathering data on oceanic variables such as primary productivity, making it suitable for this research question. 

In this work, we will try to answer the question: Can we use historical ocean data and machine learning models to predict primary productivity values? Answering this question will help solve one aspect of your overarching goal of trying to forecast global climate change.

## Solution Description

To investigate this question, I used data from the Bermuda Atlantic Time Series dataset. They have long-term measurements of primary productivity in the Atlantic Ocean, as well as other measurements such as date-time, depth, chlorophyll, and other nutrients. Using historical data of these environmental variables, we can use machine learning models to predict future primary productivity values. 

Why might this important to you? The goal of this analysis is to see whether we can use machine learning to reveal patterns or cycles that might be difficult to pick up otherwise. We found that the machine learning models were able to predict primary productivity values pretty accurately. This is important because it will help us better understand how ocean ecosystems will respond to future climate conditions. You can also get a better picture of overall climate change, starting with looking at just the oceans. If you want to expand this work even further, you could apply this research to the atmosphere and land effects on climate change.


## Chart

<img width="1075" height="558" alt="image" src="https://github.com/user-attachments/assets/a2185d4a-9a7c-412c-be8f-f721a710b1bc" />


In the scatterplot above, we can see primary productivity values over time. The dotted red line marks the separation between the train and test set. Specifically, the last 15% of the data was reserved for the test set, since this is a forecasting problem. We can see there are no obvious trends in primary productivity over time just looking at this plot, so hopefully, further data analysis will help us better understand trends in primary productivity.
