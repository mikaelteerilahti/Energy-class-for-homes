# Energy-class-for-homes
Building AI solution for energy class for homes

# The idea in a nutshell

I decided to investigate how energy consumption affects the market price of detached houses.

# Background

When choosing a construction solution for my new detached house, I wanted to find out whether the energy efficiency class of the house affects its resale value. Energy efficiency has a significant impact on living costs and is particularly important in terms of climate change. At the same time, I was interested in learning about artificial intelligence methods in general and wanted to find out if any AI technology could help me answer my question.

# Data and artificial intelligence techniques

During the planning phase, I began collecting house sale listings from online search services. I narrowed down my search according to my goal: detached houses in Espoo that were 0–30 years old. Over two years, I collected several hundred observations. I also edited the data by removing outliers, i.e., deviations that I considered too large.

I completed all the course assignments at the intermediate level. Finally, I applied the "Training Data" exercise to analyze the data set I had collected. I divided the data into training and test sets in a ratio of 80/20. I tried different parameter values, such as 3–10 network layers. I used a maximum of 100 epochs for hyperparameter optimization and a maximum of 500 epochs for training.

# Challenges

The result was a prediction accuracy of MAE = 0.7623. I do not consider this sufficient, and I did not find a solution where the model would have recognized the energy efficiency class as a significant factor affecting the price.

I also tested the database using traditional regression analysis, logarithmically transforming the price variable. In this analysis, the difference between energy efficiency classes A and B was clearly evident, with an impact of approximately 10% on price.

In addition, Perplexity, Claude, and Gemini all showed a clear 5–15% impact of the energy class on the price. Although general AI models recognize the impact of the energy class, the price ranges they provide are too wide for professional use.

I interpret these results to mean that the data I collected was insufficient to produce clear and stable results. My conclusion is that a much larger data set is needed for a neural network-based approach. However, the resources available to me do not allow for this.
The TensorFlow library I used is very comprehensive and apparently quite effective. However, I used it rather cautiously, and my neural network skills need to be developed considerably.

# Next steps

This project could be successful in collaboration with an organization that has easy access to the necessary data, such as a widely used real estate web portal.
