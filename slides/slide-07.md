## Data

Data is the heart and soul of ANNs. Utilizing a good dataset is critical to the success of any neural network.

Vertical:

## What's in a Dataset?

There are typically two categories of data in a dataset:

- Input: Tensors that flow through the network and are returned as output (also called feature)
- Label: Tensors of expected output for a given input

Vertical:

## What makes a Dataset "good"?

Large ANNs often need lots of quality data to be useful. Here are some characteristics of a good dataset:

- Large amount of examples
- Unique examples
- Accurate labelling

Vertical:

## What does the data look like?

Datasets are typically composed of numerical arrays with one or more dimensions:

```python
input_tensor = numpy.array([[0, 1, 2], [1, -1, 0], [-2, 0, 0]])
print(input_tensor.shape) # => (3, 3)

label_tensor = numpy.array([0, 0, 1])
print(label_tensor.shape) # => (3,)
```
