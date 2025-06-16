Machine learning project to predict body fat percentage using R for data cleaning and exploratory analysis, and Python for neural network modeling with Ray Tune for hyperparameter optimization.
In this project, I aimed to predict body fat percentage using machine learning techniques, combining the strengths of R and Python. Here’s how I approached it:

Data Preparation in R
I started with a dataset containing variables like body density, age, weight, and height. Using R, I cleaned the data by handling missing values, removing outliers, and ensuring consistency. Then, I conducted exploratory data analysis (EDA) with tools like ggplot2 to visualize relationships between features and body fat percentage, helping me select the most relevant variables for modeling.
Initial Modeling in R
I built a preliminary neural network in R using a package like neuralnet or caret. This involved splitting the data into training and testing sets, defining the network architecture (e.g., one hidden layer with a few neurons), and training the model to predict body fat percentage. I evaluated its performance with metrics like Mean Squared Error (MSE) and R-squared (R²).
Advanced Modeling in Python
To improve accuracy, I switched to Python and implemented a more sophisticated neural network using libraries like tensorflow or keras. I used Ray Tune, a hyperparameter optimization tool, to fine-tune the model by testing different configurations—such as the number of neurons and layers—automatically finding the best setup.
Evaluation
After training, I tested the final model on a holdout set, calculating MSE and R², and visualized the results with a scatter plot of actual vs. predicted values to assess performance visually.
This project showcases a full machine learning pipeline, blending R’s data analysis capabilities with Python’s advanced modeling tools, optimized via Ray Tune.
