# Disease-Prediction-Machine-Learning-
nm_model.add(tf.keras.layers.Dense(units=10, activation="relu", input_dim=46))

# Second hidden layer
nm_model.add(tf.keras.layers.Dense(units=6, activation="relu"))

nm_model.add(tf.keras.layers.Dense(units=4, activation="relu"))

# Output layer
nm_model.add(tf.keras.layers.Dense(units=1, activation="sigmoid"))\

1982/1982 - 1s - loss: -2.1951e+07 - accuracy: 0.8022 - 1s/epoch - 668us/step
Loss: -21950550.0, Accuracy: 0.8021917343139648