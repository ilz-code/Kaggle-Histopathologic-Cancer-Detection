# Kaggle-Histopathologic-Cancer-Detection
This project is created to correspond to the Kaggle competition Histopathologic Cancer Detection. It uses tf.keras.Sequential CNN model.
Model consists of 3x(Conv2D, Conv2D, BatchNormalization, MaxPool2D), Flatten, Dense, Dropout and Dense layers.
It is trained 5 epochs, and final accuracy is: auc: 0.9372 - loss: 0.3106 - val_auc: 0.9420 - val_loss: 0.3097; accuracy on test results (evaluated by Kaggle): 0.8983
