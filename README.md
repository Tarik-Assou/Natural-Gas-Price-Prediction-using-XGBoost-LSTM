# Natural-Gas-Price-Prediction-using-XGBoost-LSTM

FORECASTING cost model is a prerequisite to the development and validation of new optimization methods and control tools. Here, I will show a simple yet powerful approach of forecasting using machine learning algorithms.

Here, I will use machine learning algorithms to train my machine on historical price records and predict the expected future price. Let’s see how accurately our algorithms can predict. I will use —
1. eXtreme Gradient Boosting (XGBoost) which is a scalable and accurate implementation of gradient boosting machines and it has proven to push the limits of computing power for boosted trees algorithms. The algorithm was developed to efficiently reduce computing time and allocate an optimal usage of memory resources.
2. Long short-term memory (LSTM) which is a Recurrent Neural Network and a state of the art algorithm for sequential data. It is the first algorithm that remembers its input, due to an internal memory, which makes it perfectly suited for Machine Learning problems that involve sequential data. It is one of the algorithms behind the scenes of the amazing achievements of Deep Learning in the past few years.
We have to be careful about the Input / Output shapes in each category. Though both algorithms have their own set of advantages and both are quite powerful, here, we will compare and select the best of the two for prediction of future price.

I have used Natural Gas Daily Spot Price which can be accessed at https://www.eia.gov/dnav/ng/hist/rngwhhdM.htm. So, we upload the data and do some processing to clean the data and to make the data ready for machine learning.
