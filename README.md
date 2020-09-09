# speech-recognition
## Command recognition model (single word commands) using neural networks 

This model uses CNNs and dense layers to recognise the following commands:<br>
*'left', 'up', 'on', 'go', 'yes', 'off', 'no', 'down', 'stop', 'right'*

Data contains 1 second clips of audio commands by multiple speakers with varying vocl features. An example of the same is visualised below (both as a time signl and as a spectogram)
<br><img align="center" width="800" height="400" src="https://github.com/krithik1008/speech-recognition/blob/master/img/visual.PNG"><br><br>
**This model uses `librosa` package for audio preprocessing and feature extraction and uses `keras` for building the nueral network architechture. THe model achives 89% training accuracy and 84% test accuracy. The plot of accuracy and loss is shown below**<br>
<br><img align="center" width="300" height="300" src="https://github.com/krithik1008/speech-recognition/blob/master/img/accuracy.PNG">
<img align="center" width="300" height="300" src="https://github.com/krithik1008/speech-recognition/blob/master/img/loss.PNG"><br><br>

This model was run on Google Colab. Links to respective notebooks:<br>
<br>Training model : https://colab.research.google.com/drive/1EozlIiz2clYWkn1rWTW38UORThJeEBK3?usp=sharing
<br>Testing: https://colab.research.google.com/drive/1MWKCGMXcIkRgp3r1NPwGtNTMAbB57TnD?usp=sharing
<br><br> 
In order to run the pre-trained model use `my_model.h5`
<br>Data, Model with weights and sample data: https://drive.google.com/drive/folders/1Cz29trw8XysGf2ERko3B_S7wAafc3eH4?usp=sharing
