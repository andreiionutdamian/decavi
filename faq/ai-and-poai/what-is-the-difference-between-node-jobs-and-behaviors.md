# What is the difference between node jobs and behaviors?

Each box including the future software-only box is able to perform two different kinds of jobs, that is the normal job of running an AI model on a given set of observations and the more complex job of taking a model and further tuning and improving the model based on local or remote collected information. In both scenarios the box requires two things: the Deep Learning model and the data to be used with the model either for prediction/inference or for improvement of the model through training. As such there are several approaches for running the proposed scenarios such as: (i) improving a remote model with local data without sending data to another box-node; (ii) improving a remote node via remote data where the box-node that does the job receives both the data and the model; (iii) running inference or prediction jobs with local model on data received from remote nodes; (iv) inferring/predicting insights with remote models on remote data. With respect to the data or the models there are no restrictions on the application domain: a box that is currently enabled for multiple AI video security and safety features can receive jobs for predictive analytics such as time-series prediction and vice versa. Employing homomorphic encryption and other data and model security approaches can be done in any of the above scenarios.