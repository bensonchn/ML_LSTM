# Machine Learning Time Series (Group project)

## What does it do?
Attempts to predict bitcoin prices using LSTM model.

I attempt to predict 7 days ahead (168 hours) using the hourly closing price.

The LSTM hyperarameters were tuned with Random Search

Things that were considered:

Features, Number of Neurons, Epoch, Batch Size, TimeSteps, and Layers


*More depth will be explained in the pdf document in comparison to SVM (did by Gwendolyne Legate)*

## Needed Improvements
The predicted curves that were very similar to the real curve which is a cause for concern for overfitting
Due to limitations, the number of epochs were kept relatively low. There are many tools available to allow for faster training that might have allowed the LSTM model to do more testing.

## How to run it
You simply run the whole code

## Results
In my findings, it would seem that the model is perhaps overfitting

![image](https://user-images.githubusercontent.com/25267825/113523754-db6e0700-9577-11eb-8ea2-2b252c493377.png)

But at the same time, we can see at a closer view, the predictions are indicating an uptrend

![image](https://user-images.githubusercontent.com/25267825/113523766-eaed5000-9577-11eb-8784-1253b82a6097.png)

