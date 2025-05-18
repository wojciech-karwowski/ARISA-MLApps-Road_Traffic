Optimizing urban road traffic using AI - assignment
Termin: 22 czerwca 2025 23:59
Instrukcje
Download the dataset from https://drive.google.com/file/d/1m5xgNXp3vv5zzH4JHfE9983cLiSR3IPp/view

In the file, you have 105336 rows. In each row, the first 21 elements are offsets at 21 intersections in Warsaw (a part of the Ochota district), while the last element is the total waiting time at red lights for all cars during a simulation of 10 minutes of realistic traffic (it was calculated using the Traffic Simulation Framework tool). The offsets are times (in seconds) from the start of the simulation to the first transition (of a selected signal state at the given intersection) from the red signal state to the green signal state. The values of the offsets are integers from the set {0,1,2,...,119}. The total wait times at red signals are also integers.

Your task is to implement a pipeline for:

1) Reading the data.

2) Splitting the dataset into a training set (first 85336 rows) and a test set (last 20000 rows).

3) Preprocessing the data (e.g., you can normalize the inputs and outputs).

4) Training at least 1 machine learning model (e.g., a feed-forward neural network, XGBoost, or LightGBM) to predict the total wait time at red signals based on the 21 offsets.

5) Calculating the MAPE (Mean Absolute Percentage Error) of the trained model(s) on the test set and presenting the results.

6) Optimizing the hyperparameters of your model, if needed.

7) Presenting the results, e.g., you can visualize how the MAPE or loss function changes in iterations of training.



It should be possible to get a MAPE below 2%, but it may take some time and may require optimizing the parameters. 

The code should be prepared as a Jupyter notebook. If you need a GPU, you can use Google Colab.



Questions: send an email to pawel.gora@qaif.org

Submission: send the Jupyter notebook file with the code to pawel.gora@qaif.org by 22.06.2025.