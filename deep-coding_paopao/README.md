# README #

### What is this repository for? ###

* This repository try to get more efficient video coding by deep learning
* Version v0.0.1

### How do I get set up? ###
#### Dependencies
* Tensorflow
* Numpy

#### Get start
* Firstly, you should download the dataset, such as bsds500, mscoco. And then call `python preparation.py` to convert jpeg images in desired directory to YUV file, which will be encoded by HEVC to get the reconstructed YUV file; after that, these YUV will be tranformated to tensorflow records, which are used for train, test.
* Use `python train.py` to train CNN model
* Test CNN model by `python test.py`