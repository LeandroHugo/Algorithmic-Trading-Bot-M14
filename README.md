# 📈 Machine Learning Trading Bot 🤖
![Alt text](Resources/MLTB1.png)
In this challenge, we'll put on the hat 🎩 of a financial advisor at one of the top five financial advisory firms in the world. Our firm is in a fierce competition with other major firms, managing and auto-trading assets in a highly dynamic environment. We've reaped hefty profits in recent years, thanks to computer algorithms that trade faster than human traders. 

The transaction speed brought an early competitive advantage to our firm. But these systems still need human programming, which hampers their adaptability to new data. Hence, we plan to refine our existing algorithmic trading systems and preserve our competitive market advantage by infusing them with machine learning algorithms that can adapt to new data 📊.

## 🎯 Instructions

### 🏁 Establish a Baseline Performance 📈

In this phase, we run the provided starter code to establish a baseline performance for the trading algorithm. Here are the steps:

1. Load the OHLCV dataset into a Pandas DataFrame 🐼.
2. Generate trading signals using short- and long-window SMA values 📊.
3. Partition the data into training and testing datasets 💽.
4. Use the `SVC` classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions using the testing data. Take a moment to review the predictions 🔍.
5. Review the classification report related to the `SVC` model predictions 👀.
6. Create a DataFrame that includes columns for "Predicted" values, "Actual Returns", and "Strategy Returns".
7. Plot a cumulative return that shows the actual returns vs. the strategy returns. Save a PNG image of this plot 🖼️. This will be our baseline to compare the tuning effects of the trading algorithm.
8. Write conclusions about the baseline trading algorithm performance in the `README.md` file. Support your findings with the PNG image saved in the previous step.

### 🛠️ Tune the Baseline Trading Algorithm 🔧

In this phase, we tune, or adjust, the model’s input features to find the parameters that result in the best trading outcomes.

1. Tune the training algorithm by adjusting the size of the training dataset. Slice your data into different periods, rerun the notebook with the new parameters, and record the results in your `README.md` file 📝.
2. Tune the trading algorithm by adjusting the SMA input features. Adjust one or both of the windows for the algorithm, rerun the notebook with the updated parameters, and record the results in your `README.md` file.
3. Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusions in your `README.md` file.

### 🕵️‍♀️ Evaluate a New Machine Learning Classifier 🔍

In this section, we use the original parameters provided by the starter code and apply them to the performance of a second machine learning model.

1. Import a new classifier, such as `AdaBoost`, `DecisionTreeClassifier`, or `LogisticRegression`.
2. Use the original training data as the baseline model, fit another model with the new classifier.
3. Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file.

### 📝 Create an Evaluation Report 📊

In the final phase, we provide a summary evaluation report at the end of the `README.md` file. This report will state our final conclusions and by the PNG images that we created in the previous steps. This comprehensive report should serve as a clear reflection of our process, our findings, and the steps we took in enhancing our trading algorithm 🚀.

Good luck on your journey to improve and adapt existing algorithmic trading systems with the power of Machine Learning! Remember, the essence of this challenge is not just about creating a more profitable model, but learning, experimenting, and having fun along the way! 💡💰🚀
![Alt text](Resources/MLTB2.png)
