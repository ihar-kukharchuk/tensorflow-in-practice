# tensorflow-in-practice
Coursera TensorFlow in Practice Specialization: https://www.coursera.org/specializations/tensorflow-in-practice
1. Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning: https://www.coursera.org/learn/introduction-tensorflow
2. Convolutional Neural Networks in TensorFlow: https://www.coursera.org/learn/convolutional-neural-networks-tensorflow
3. Natural Language Processing in TensorFlow: https://www.coursera.org/learn/natural-language-processing-tensorflow
4. Sequences, Time Series and Prediction: https://www.coursera.org/learn/tensorflow-sequences-time-series-and-prediction

```python
import base64

def encode(line):
    return base64.b64encode(line.strip()).encode('rot13')

def decode(line):
    return base64.b64decode(line.decode('rot13'))
```
