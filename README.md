Machine Learning in Financial Forecasting
The objective of this project is to predict the price direction of Bitcoin in the upcoming time frame by using machine learning classification. We will compare different models and experiment with variations in retraining size, retraining frequency, and number of features. The models output the predicted trend as a percentage probability which will be interpreted as up, down, or non conclusive.

The idea is to provide an actionable information piece that is an input to a decision process on when, how much and what type of trade (short vs long).

This project was inspired by a previous work performed at the Northumbria University in Newcastle*. We are using the idea of the methodology (sliding-windows and re-training strategy) and applying it to different instruments, testing a different set of technical indicators and different time-frames for the sliding windows and re-training periods.

The inputs to the models include past quote data (OHLCV) as well as technical indicators.

Part of the project consists in testing different types of indicators by creating sets of indicators covering different areas, such as trending indicators, volume indicators, etc.

Our plan is to complete an MVP for this project consisting of creating a software solution that: Creates different sets of indicators to test a group of predictive models (dataset creation) Models each of the datasets using processing windows and frequent re-training (sliding window durations and re-training periods to be defined) - (model creation) Summarizes the findings Presents the outcome to the end-user (GUI)

Link to Presentation

Group 4 - Team Members
William Chance
Pablo (Martin) Rasumoff
Jorge Sira
Juan Carlos Castaneda
