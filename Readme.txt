Data Source and description:

##Dataset Link: https://www.kaggle.com/ritesaluja/bank-note-authentication-uci-data

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

I have used Random Forest algorithm to create the model which gave a very good accuracy. Delpoyed the model and created an app using Flask framework. The UI for frontend is created using Flasgger which makes it very easy to create a UI for Machine learning apps. 

The input to the UI can be seen on main python file which is easy to understand and can be edited for other purposes.
http://127.0.0.1:5000/apidocs

I have dockerized this file.

requirements:
 pip install flasgger

