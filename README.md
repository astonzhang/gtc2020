# GTC2020 Tutorial - Dive into Deep Learning

Instructors: Rachel Hu (Amazon AI), Aston Zhang (Amazon AI)

Deep learning is transforming the world nowadays. However, realizing deep learning presents unique challenges because any single application brings together various disciplines. Applying deep learning requires simultaneously understanding:

1. the engineering required to train models efficiently, navigating the pitfalls of numerical computing and getting the most out of available hardware;
2. the mathematics of a given modeling approach;
3. the optimization algorithms for fitting the models to data;
4. and the experience of choosing proper hyperparameters for the solution.


To fulfill the strong wishes of simpler but more practical deep learning materials, [Dive into Deep Learning](https://d2l.ai/), a unified resource of deep learning was born to achieve the following goals:

- Offering depth theory and runnable code, showing readers how to solve problems in practice;
- Allow for rapid updates, both by us, and also by the community at large;
- Be complemented by a forum for interactive discussions of technical details and to answer questions;
- Be freely available for everyone.



## Prerequisites


### GPU Basics

- [Installations with CUDA](https://d2l.ai/chapter_installation/index.html)
- [Basic Operations on GPUs](https://nbviewer.jupyter.org/github/goldmermaid/gtc2020/blob/master/dl/1-use-gpu.ipynb)
- [Hardware for deep learning](https://d2l.ai/chapter_computational-performance/hardware.html#gpus-and-other-accelerators)


### Deep Learning Basics

| title                               |  notes    |  slides    |
| ------------------------------ | ---- | ---- |
| Data Manipulation with Ndarray | [D2L](https://d2l.ai/chapter_preliminaries/ndarray.html) | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-1/1-ndarray.ipynb#/) |
| Automatic Differentiation | [D2L](https://d2l.ai/chapter_preliminaries/autograd.html) | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-1/2-autograd.ipynb#/) |
| Softmax Regression | [D2L](https://d2l.ai/chapter_linear-networks/softmax-regression.html) | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-1/7-softmax-regression-gluon.ipynb#/) |
| Multilayer Perceptron (MLP) | [D2L](https://d2l.ai/chapter_multilayer-perceptrons/mlp.html) | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-1/9-mlp-gluon.ipynb#/) |



## Syllabus

In this training, we are going to provide an overview of the in-depth convolutional neural networks (CNN) theory and handy python code. What is more important, the audience would be able to train a simple CNN model on our pre-setup cloud-computing instances for free. Here are the detailed schedule:


| Time | Topics | Slides |
| --- | --- | --- |
| 9:00---9:10 | Dive into Deep Learning | [Slides](https://github.com/goldmermaid/gtc2020/blob/master/DL.pdf) |
| 9:10---9:40 | Convolutional Neural Networks | [Slides](https://github.com/goldmermaid/gtc2020/blob/master/CNN.pdf), [Notebooks](#Convolutional-Neural-Networks) |
| 9:40---10:00 | Intro to Natural Language Processing | [Slides](https://github.com/goldmermaid/gtc2020/blob/master/NLP.pdf) |
| 10:00---10:30 | TextCNN on Sentiment Analysis | [Notebook](https://nbviewer.jupyter.org/format/slides/github/goldmermaid/gtc2020/blob/master/dl/textCNN.ipynb#/1) |
| 10:30---10:45 | Resources and Q&A | [Links](#Resources-and-Q&A ) | 



### Convolutional Neural Networks Notebooks



| title                                        | notebooks                                                         |
| -------------------------------------------- | ------------------------------------------------------------ |
| Convolutions                                 | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/goldmermaid/gtc2020/blob/master/dl/2-conv-layer.ipynb#/) |
| Pooling                                      | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-2/3-pooling.ipynb#/) |
| Convolutional Neural Networks (LeNet)        | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-2/4-lenet.ipynb#/) |
| Deep Convolutional Neural Networks (AlexNet) | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-2/5-alexnet.ipynb#/) |
| Residual Networks (ResNet)                   | [nbviewer](https://nbviewer.jupyter.org/format/slides/github/mli/d2l-1day-notebooks/blob/master/notebooks-2/8-resnet.ipynb#/) |


### Resources and Q&A 


- [AutoGluon](https://autogluon.mxnet.io/) enables easy-to-use and easy-to-extend AutoML with a focus on deep learning and real-world applications spanning image, text, or tabular data;


- [GluonNLP](http://gluon-nlp.mxnet.io/) offers state-of-the-art pretrained NLP models, easy text preprocessing, datasets loading and neural models building; 


- [GluonCV](http://gluon-cv.mxnet.io/) provides state-of-the-art deep learning models in computer vision and carefully designed APIs that greatly reduce the implementation complexity;


- [GluonTS](https://gluon-ts.mxnet.io/) supports deep learning based probabilistic time series modeling;


- [Deep Graph Libray](https://www.dgl.ai/) develops easy-to-use, high performance and scalable Python package for deep learning on graphs;


- [TVM](https://tvm.apache.org/): automatic generates and optimizes tensor operators on more backend with better performance for CPUs, GPUs and specialized accelerators.


If you have any question, please leave us a message at our [discussion forum](https://discuss.mxnet.io/c/d2l-book). Have fun diving into deep learning!
