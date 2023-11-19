# Multi touch attribution modeling with Google analytics data
Understanding the sources that contribute to a high conversion rate is crucial for effective decision-making in resource allocation. It's essential to gain insights into the channels where investments are made and the returns generated. This project aims to analyze various channels using different models, providing valuable information to optimize our credit system. Kindly find the detailed Kaggled notebook [here](https://www.kaggle.com/code/vijayabhaskarmandla/attribution-modeling-with-goole-analytics-data), In this we will explore and evaluate diverse channels to enhance our understanding of their impact on conversion rates.

To familiarize yourself with Channel [Channel Attribution](https://channelattribution.io/pdf/ChannelAttributionWhitePaper.pdf), it's essential to understand various attribution models:

* **First Touch Conversion:** This model attributes user conversion credit to the first touchpoint from which the user initially arrived.
* **Last Touchpoint Conversion:** User credit is attributed to the last touchpoint before conversion.
* **Linear Touchpoint:** Conversion credit is evenly distributed across all touchpoints that the user interacted with.
* **Markov Model:** A probabilistic model that assigns credit based on the paths most conversions have taken. Refer to the graph below for a visual representation.


## Conversion credits by Channel
![Visul 1](https://github.com/vijaybhaskar98/Google-analytics-/blob/b2ae5878c4408b8b7a1e9336d3e25f48ed0e482d/Multi%20touch%20attribution%20modeling%20with%20google%20analytics%20%20data/Visuals/v%202.png)


## Revenue Credit by channel
![Visual 2](https://github.com/vijaybhaskar98/Google-analytics-/blob/b2ae5878c4408b8b7a1e9336d3e25f48ed0e482d/Multi%20touch%20attribution%20modeling%20with%20google%20analytics%20%20data/Visuals/v%203.png)

## Transition matrix
![Visual 3](https://github.com/vijaybhaskar98/Google-analytics-/blob/b2ae5878c4408b8b7a1e9336d3e25f48ed0e482d/Multi%20touch%20attribution%20modeling%20with%20google%20analytics%20%20data/Visuals/v%204.png)

📊 Analysis from the Graph: Understanding Attribution Models 🤔

Upon examining the graph, it becomes evident how various models allocate conversion credit to different channels. Notably, the Markov attribution model appears to assign higher credit to the paid search channel based on our observations.

# 🔍Conclusions
The insights derived from the heat map and plots provide a comprehensive understanding of each marketing channel's contribution to conversions. Beyond individual channel performance, we've gained crucial insights into the interplay between channels, uncovering the paths that guide users from one channel to another.

In today's landscape, where users encounter multiple touchpoints, this information holds immense value. It empowers us to optimize our multi-channel customer journeys effectively. The Markov Chain approach, as detailed in this article, enhances the accuracy of attributions, ensuring a more precise reflection of how users interact with our marketing efforts. 🚀📈
