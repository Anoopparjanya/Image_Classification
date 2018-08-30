# Image_Classification
Image classification using CNN Vgg16 architecture - Keras-Tensorflow
Image Recognition_Flowers DataSet_Keras_Tensorflow
# Usage

Environment Setup:

1.Keras
2.Opencv2 
3.Tensorflow 
4.imutils
5.numpy
6.matplotlib

Run the following command to clone the source code from github

```bash
git clone https://github.com/Anoopparjanya/Image-Classification
``` 
Since keras by default uses theano backend,to work on tensorflow backend run the following command:

```bash
set KERAS_BACKEND=tensorflow
```
Training
Open Anaconda prompt and set the current project dictionary and run the following command.
```bash
python train.py --dataset dataset --model flowers.model --labelbin lb.pickle
```
The above commands will train CNN - VGG16 architecture model

once the model is trainned successfully,run the following command to test the model.
```bash
python classify.py --model flowers.model --labelbin lb.pickle --image examples/rose.png
```
I have got 100% accuracy when i test my model.




