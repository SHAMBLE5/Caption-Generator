## IMAGE CAPTION GENERATOR USING DEEP LEARNING

## Objectives
* To recognize the context of an image and describe them in English.


#### UI was created using Tkinter.

#### Summary
1. Image sent to CNN(Resnet50).
2. Last layer of CNN is removed.
3. CNN produces image vector of length 2048.
4. Image vector and Caption sent to model.
5. Model generates probability distribution.
6. Select word with maximum probability.

## Requirements
1. Tensorflow
3. Python 3.7
4. Tkinter
5. Numpy
