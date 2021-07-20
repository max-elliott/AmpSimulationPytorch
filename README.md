# Guitar Ampilfier Simulation using Deep Learning by Max Elliott


This work is inspired by https://github.com/GuitarML/GuitarLSTM, which is a Tensorflow implementation of work done in https://www.mdpi.com/2076-3417/10/3/766/htm. I have effectively re-implemented parts of the repository above using Pytorch within this notebook. However the model architecture, hyperparameter tunings, training/testing loops etc. have varied based on my experimention. 

Following through this notebook will train a neural network (CNN into LSTM layers) to model a guitar amplifier, converting an input audio sequence into the amplified version. The model works in the raw audio domain, here at 44.1kHz. The sound that the model is aiming to replicate is an aggressive distorted preset for bass guitar recorded with https://neuraldsp.com/plugins/parallax. 

Enjoy!
