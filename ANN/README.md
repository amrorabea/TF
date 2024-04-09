# This is the full explaination of the code in this [File](https://github.com/amrorabea/TF/blob/main/ANN/ANN.ipynb)
```pip
tf.keras.models.Sequential()
```
This initializes the model basic object,
defines a linear stack of layers (Acts as the container for the layers).

```pip
model.add(tf.keras.layers.Dense(units=128, activation='relu', input_shape=(784, )))
```
``` model.add(...) ``` Adds a layer to the model.

``` tf.keras.layers.Dense(...) ``` Fully connected layer where the neurons learn.

``` tf.keras.layers.Dense(units=128, activation='relu', input_shape=(784, )) ``` 

_units_: Number of neurons in the layer

_activation_: the activation function applied to the output __ReLU__ is one kind of activation functions defined as the positive part of the function (zero of the value is negative).

_input_shape=(784, )_: we only write this in the first layer of the model as it defines the expected shape of the input data

