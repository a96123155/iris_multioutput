# Hybrid Toy Model in Keras on the Iris Dataset
> **Multi output Keras model on the iris dataset. I am adding a regression value to each class so that I can implement classification and regression in the same model. Classes are flower types: Iris-setosa, Iris-versicolor,Iris-virginica.  As an add-on, I am adding another output for flower price.**



> **Some features of the model are as follows:**

* **Early Stopping as Regulariation**
* **Saves best model by using Model Checkpoint**
* **After training, loads best model and then predicts on the test set**
* **Adam optimizer use**

> **The model architecture is given below**

![Alt text](model_plot.png?raw=true "Title")

> **Training Validation Losses, Accuracy plots are the following:**

![Alt text](loss_accuracy.png?raw=true "Title")

> **Model Achieves validation accuracy of ~97%**

> **Other metrics are as follows**

![Alt text](metrics.png?raw=true "Title")
