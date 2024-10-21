# UsedVehiclePrice_Prediction
Predicting the selling price of Used vehicles 
In this project, I developed predictive models to accurately forecast the selling price of used vehicles. I experimented with a range of regression models to identify the most effective approach. Initially, I implemented a basic linear regression model and then advanced to more complex models, including a log-transformed regression model and a model utilizing one-hot encoding to handle categorical features such as vehicle make, model, and specifications.

Additionally, I applied L1 regularization (Lasso) to manage overfitting by penalizing less important features, and I also implemented Random Forest to capture non-linear relationships within the data. Each model’s performance was evaluated using the R² value, ensuring an accurate and well-fitted model.

When accuracy was the primary focus, Model 4, which used OneHotEncoder, emerged as the best performer. However, when considering a balance between model complexity and performance, Model 2, the log-transformed regression model, proved to be the optimal choice, offering a simpler approach while maintaining a high level of accuracy.
