# human-or-bot
Classification problem to identify bot bidders from human bidders

Initial dataset can be obtained through the Kaggle link provided below,
https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data

After downloading the dataset, place the unzipped datasets into a "data" folder.

The sequence of notebooks to run are numbered from number 1 to 7. After the notebook 6, we conducted 
experiments using 10, 15, 20, 25, 30, 35, 40 features for each of the models. Each experiment results
can be found in the "Experiments" folder.

In case of encountering an error when running the Artificial Neural Network Model, please try the 
following versions for keras and tensorflow:

keras==2.6.0
Keras-Preprocessing==1.1.2
keras-tuner==1.0.4
tensorboard==2.7.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.0
tensorflow==2.6.1
tensorflow-estimator==2.6.0
