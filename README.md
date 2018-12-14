# artificial_neural_networks
[![GitHub license](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://raw.githubusercontent.com/kourouklides/artificial_neural_networks/master/LICENSE)

## About
This repository contains a collection of Methods and Models for various architectures of __Artificial Neural Networks__.

The code implementation is in __Python 3__ (using [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/) libraries).

The repository is the one used for lectures of the Master's degree [MSc in Data Science and Engineering](https://www.cut.ac.cy/faculties/fet/eecei/module-description/modules-msc-data-science-and-engineering/?languageId=1) and also, at the meetups and workshops of [PyData Cyprus](https://www.meetup.com/PyDataCyprus/).

If you like this repository or if you found it useful, feel free to __Star, Fork, Watch__ it or __share__ it online.

__Note:__ Hyperparameter Optimization, Model Selection and Model Evaluation are outside the scope of this repository.

## Introduction

* Currently, this repository is neither a library nor a framework, but it is a collection of __code examples__
* The code is well documented so that it can be used for both __educational purposes__ and for __real-life applications__
* This repository is intended to be friendly to beginners, but it is not limited just to them
* Since TensorFlow is ideal for both __Research__ and __Production Development__, then so is this repository
* In order to deploy the source code into Production, a few extensions will have to be made first
* The [license](LICENSE) of this repository essentially allows you to do whatever you want with the code

## Downloading
It is strongly recommended that you download the whole GitHub repository, but you can also try to download just the individual Python files and see if they work. However, there is no guarantee that individual files will work on their own.

To download the whole repository, there are currently two mains options:
* Clone the repository using [GitHub Desktop](https://desktop.github.com/) or using the [command line (terminal)](https://help.github.com/articles/cloning-a-repository/)
* Download the respository as a ZIP file

You can choose the one which best suits your needs.

## Setup and Installation
The code should run on any machine (i.e. Windows, macOS, Linux) that supports __Python 3__.

Guides and instructions on how to install the necessary libraries and how to setup your environment can be found [here](setup/README.md).

## Running from the terminal

If you do not want to use an IDE (e.g. [Spyder](https://www.spyder-ide.org/)) and want to run a script from the command line (terminal) then you __should use__ it with the [``-m`` command-line flag](https://docs.python.org/3.6/using/cmdline.html#cmdoption-m) and without its ``.py`` extension, for the reasons explained [here](https://stackoverflow.com/questions/22241420/execution-of-python-code-with-m-option-or-not).

For example, by __replacing__ \<your directory path> accordingly, you can either run this:

    cd <your directory path>/artificial_neural_networks/code/architectures/feedforward_neural_networks/standard_neural_networks/
    python -m snn_dense_mnist

or you can run this:

    cd <your directory path>/artificial_neural_networks/
    python -m artificial_neural_networks.code.architectures.feedforward_neural_networks.standard_neural_networks.snn_dense_mnist


## Methods and Models
This repository includes the following architectures:

- [Feedforward Neural Network](code/architectures/feedforward_neural_networks)
  - Bayesian Neural Networks
  - [Convolutional Neural Networks](code/architectures/feedforward_neural_networks/convolutional_neural_networks)
  - [Standard Neural Networks](code/architectures/feedforward_neural_networks/standard_neural_networks)
- [Recurrent Neural Network](code/architectures/recurrent_neural_networks)
  - GRU
  - [LSTM](code/architectures/recurrent_neural_networks/LSTM/)
  - Vanilla RNN

Some advanced Methods of Machine Learning are also included:

- Ensemble Learning
- Transfer Learning

## Areas of Application
Various applications of the aforementioned Methods and Models are also included and they fall under the following domains, in alphabetical order:

- [Bioinformatics](code/applications/bioinformatics)
- [Computational Finance](code/applications/computational_finance)
- [Computer Vision](code/applications/computer_vision)
- Econometrics
- Energy
- Environmetrics
- Geospatial Data
- [Medical Imaging](code/applications/medical_imaging)
- [Natural Language Processing](code/applications/natural_language_processing)
- [Sequential Data](code/applications/sequential_data) (including Time Series)
- [Speech Processing](code/applications/speech_processing)

## Theory
Finally, regarding theory of Artificial Neural Networks, you can check the following pages on my personal wiki:

- [Artificial Neural Networks](https://wiki.kourouklides.com/wiki/Artificial_Neural_Network)
- [Deep Learning](https://wiki.kourouklides.com/wiki/Deep_Learning)
- [Machine Learning](https://wiki.kourouklides.com/wiki/Machine_Learning)

The wiki contains curated lists of online and offline resources (e.g. books, papers, URL links) about these topics.

## Contributing

Contributors are all welcome.

## License

[Apache License 2.0](LICENSE)

