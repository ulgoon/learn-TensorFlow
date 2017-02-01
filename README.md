# Learn TensorFlow

## Reference
모두를 위한 머신러닝 / 딥러닝 강의 by Sung Kim
(https://hunkim.github.io/ml/)

## Goals
- Basic understanding of machine learning algorithms
    - Linear regression, Logistic regression(classification)
    - Neural networks, Convolutional Neural Network, Recurrent Neural Network
- Solve your problems using machine learning tools
    - Tensorflow and Python

## Acknowledgement
- Andrew Ng's ML class(coursera)
    - https://class.coursera.org/ml-003/lecture
    - http://www.holehouse.org/mlclass/ (note)
- Convolutional Neural Networks for Visual Recognition
    - http://cs231n.github.io/
- Tensorflow
    - https://www.tensorflow.org
    - https://github.com/aymericdamien/TensorFlow-Examples

## Schedule
- Machine learning basic concepts
- Linear regression
- Logistic regression (classification)
- Multivariable (Vector) linear/logistic regression
- Neural networks
- Deep learning
    - CNN
    - RNN
    - Bidirectional Neural networks

## Installation
`python 3.5.1` with pyenv, virtualenv, autoenv
(https://github.com/yyuu/pyenv-virtualenv)
(https://dobest.io/how-to-set-python-dev-env/)

`$ pyenv activate learntf`

### Install TensorFlow
Mac OS X, CPU only, Python 3.4 or 3.5:
`(learntf)$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.12.1-py3-none-any.whl
`
`(learntf)$ pip install --upgrade $TF_BINARY_URL`

### Tools for Data Analysis
(https://jkeun.github.io/post/data-analysis-env-setting/)
`$ pip install jupyter`
`$ pip install pandas`
`$ pip install sklearn`
`$ pip install matplotlib`
`$ pip install seaborn`
`$ pip install --upgrade --no-deps statsmodels`
