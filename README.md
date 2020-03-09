# TaxiPrediction

This work aims at resolving a Kaggle Competition to predict the destination of taxi trips based on initial partial trajectories: https://www.kaggle.com/c/pkdd-15-predict-taxi-service-trajectory-i/overview.

This project is composed of four notebook files:
  - Data_viz.ipynb : it visualizes data to prepare the feature engineering
  - Tensoring.ipynb : it pre-processes data to put them in tensor form, and adapt them to our network.
  - Network_taxi.ipynb : it defines our neural network and traines it.
  - Test_model.ipynb : it computes results for the test dataset.

The project is also composed of:
  - a file "model_cluster_100.pth" that stores the weights of our network after the 100th epoch
  - a file "loss_cluster.txt" that stores the loss obtained after each epoch while training our network
  
To run our project, you have to :

  - download data from the kaggle competition website: https://www.kaggle.com/c/pkdd-15-predict-taxi-service-trajectory-i/data
  - run all the Data_viz.ipynb notebook (data are then ready to be pre-processed)
  - run all the Tensoring.ipynb notebook (data are then ready to be used in our neural network)
  - run all the Network_taxi.ipynb notebook (weights of the neural networks are saved into pth files each two epochs and losses are saved into a txt file)
  - run all the Test_model.ipynb notebook
  
This projects has been carried out by Barnabé Mas, Alodie Boissonnet and Jean Bouteiller, under the supervision of Marc Lelarge.
