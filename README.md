# Machine_learning_and_neural_network_project

## This is a project about collecting data in 4 different movement to perform machine learning and neural network. 

## Explanation of collected data (the data will be used for machine learning and neural network)
I chose running, walking, jumping and bend_knee during the moment of collecting my body data. The data are collected individually by its group. Also, there is another data was collected by combining all movement of myself. 

### Explanation of machine learning model
I chose KNeighborsClassifier, because this machine learning is classification model. Also, KNN has the property of find how spread are the data surrounding by the K-value. Besides, using grid search can let me to pick my k-value, weight and display the accuracy. 

### Results of machine learning. 
In the end, the value of count, mean, std, min, 25%, 50%, 75% and max will be display in a table format. Also, finding the correlation  
Here is an example of the testing data result
![proof_table_correlation_pic](https://user-images.githubusercontent.com/118713625/230785513-526ad6c5-0ce9-45d7-b9b0-3ac80a31a016.PNG)

Example of autocorrelation plotfunction
![pic_1](https://user-images.githubusercontent.com/118713625/230785566-6129adc3-9e03-4726-9988-2a356834b0be.PNG)

Example of the result of training data
![pic_2](https://user-images.githubusercontent.com/118713625/230785665-c87bc445-4e99-4850-843d-a12d9ec3cb8d.PNG)

### Explanation of neural network model


traning_data_sets			
			
neurons	layers	time steps	accuracy
LSTM	    2	        10	     0.5993
LSTM	    2	        20	     0.5431
LSTM	    2	        40	     0.4195
			
LSTM	3	10	0.8436
LSTM	3	20	0.8071
LSTM	3	40	0.6404
			
LSTM	4	10	0.8146
LSTM	4	20	0.6592
LSTM	4	40	0.5094
			
SimpleRNN	2	10	0.2603
SimpleRNN	2	20	0.4307
SimpleRNN	2	40	0.3708
			
SimpleRNN	3	10	0.4522
SimpleRNN	3	20	0.3352
SimpleRNN	3	40	0.4644
			
SimpleRNN	4	10	0.265
SimpleRNN	4	20	0.2622
SimpleRNN	4	40	0.2547
			
			
			
testing_data_sets			
			
neurons	layers	time steps	accuracy
LSTM	2	10	0.2731
LSTM	2	20	0.3981
LSTM	2	40	0.2407
			
LSTM	3	10	0.6343
LSTM	3	20	0.5093
LSTM	3	40	0.444
			
LSTM	4	10	0.287
LSTM	4	20	0.2685
LSTM	4	40	0.2593
			
SimpleRNN	2	10	0.3056
SimpleRNN	2	20	0.2407
SimpleRNN	2	40	0.3333
			
SimpleRNN	3	10	0.287
SimpleRNN	3	20	0.3519
SimpleRNN	3	40	0.2593
			
SimpleRNN	4	10	0.287
SimpleRNN	4	20	0.2685
SimpleRNN	4	40	0.2593
			
			
			
Moments are done continuously			
neurons	layers	time steps	accuracy
LSTM	2	10	0.1943
LSTM	2	20	0.2759
LSTM	2	40	0.4419
			
LSTM	3	10	0.6
LSTM	3	20	0.4318
LSTM	3	40	0.4186
			
LSTM	4	10	0.3314
LSTM	4	20	0.3333
LSTM	4	40	0.3953
			
SimpleRNN	2	10	0.0914
SimpleRNN	2	20	0.1034
SimpleRNN	2	40	0.2093
			
SimpleRNN	3	10	0.3714
SimpleRNN	3	20	0.3563
SimpleRNN	3	40	0.4884
			
SimpleRNN	4	10	0.3314
SimpleRNN	4	20	0.3333
SimpleRNN	4	40	0.3256


<!-- | neurons  | layers  | time steps | accuracy |
| :------------ |:---------------:| -----:|
|LSTM     | 2 | 10 | 0.1943      |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 | -->


| neurons  | layers  | time steps | accuracy |
| :------------ |:---------------:| --------------| --------:|
| col 3 is      | some wordy text | $1600 | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

