# Speech Emotion Recognition
dataset is available here [Emo-db](http://www.emodb.bilderbar.info/download/)

### Installing dependencies
Dependencies are listed below and in the `requirements.txt` file.

* h5py
* Keras
* scipy
* sklearn
* speechpy
* tensorflow

`pip3 install -r requirements.txt` 
`pip3 install tensorflow-gpu`


### Examples
Have a look at `examples/` directory. `ml_example.py` has examples using ML models.
`cnn_example.py`  and `lstm_example.py` has examples using cnn and lstm models. 

### Installation

A `setup.py` file is provided in the repository. You can run `sudo python3 setup.py install` to install it at system level.
If you don't have privileges to do so, you can install it at user level by running `python3 setup.py install --user`.
