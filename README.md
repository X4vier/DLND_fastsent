<h3>FastSent</h3>

During the <b>Deep Learning Udacity Nanodegree</b>, we were asked to implement a neuralnet with 1 hidden layer in pure Python. This project is in pure C.

<b>Code is not that clean and this project is actually a playground for me to better understand concepts and technology limitations</b> but still had better metrics than LSTM/CNN approaches tried on the same dataset.

Key implementation info:
1) Pure C even for Backpropagation and Stochastic Gradient Descent
2) Multi-Threaded
3) Fast file loading
4) NN Weights saved/loaded
5) Early Stopping so no need to specify number of epochs
6) Learning Rate range test so no need to specify learning rate 
7) Learning Rate decay
8) Two sentiment outputs objectivity/subjectivity and polarity (measure and score)
9) All the above in 706 lines of pure C without using external frameworks or libraries

<h3>Usage:</h3>
<pre>./fastsent_train TRAIN_FILE VALIDATION_FILE TEST_FILE</pre>


* <i>Validation_file needed for early stopping</i>


* <i>All files in the sample.input format</i>


* <i>Output metrics: 1rst train, 2nd validation, 3rd test</i>

