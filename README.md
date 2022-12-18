# MLEndSound Mini Project


<p align="center"><code>Submission for Principles of Machine Learning (ECS7020P) Mini Project @QMUL</code></p>

## Basic Implementation [ [notebook link](ECS7020P_miniproject_basic.ipynb) ] 
Using the MLEnd London Sounds dataset, build a machine learning pipeline that takes as an input an audio segment and predicts whether the audio segment has been recorded indoors or outdoors.


### Pipeline

![basic-pipeline](https://arkochatterjee.github.io/ml-basic-arko.png)


<hr>

## Advanced Implementation [ [notebook link](ECS7020P_miniproject_advanced.ipynb) ] 
Using the MLEnd London Sounds dataset, I am proposing to build a machine learning model to  <b>predict the area</b> of the input audio sample.<br>
The plan is also to employ the indoor/outdoor datapoints as predictors to view if it assists in improving the model or not!


### Pipeline

![adv-pipeline](https://arkochatterjee.github.io/ml-adv-arko.png)

<hr>

### Understanding the feature set csv files

* <b>feature-set-4-adv-full.csv</b> -[ [link](feature-set-4-adv-full.csv) ] -> comprises of 10 featues [ power ,pitch_mean, pitch_std, voiced_fr, mfcc, spectral_centroid, rmse, chroma_stft, spectral_bandwidth, rolloff, zero crossing rate ] across all 2500 sound data, which is used in both basic and advanced implementation notebooks.

* the other feature set csv files play around with a combination of different features across random sound samples. 

<hr>

## Submitted by

![Arko Chatterjee](https://github.com/arkochatterjee.png?size=100)<br>[Arko Chatterjee](https://github.com/arkochatterjee)




