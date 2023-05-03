# Fake-Currency-Detection

The repository consists of three modules namely classification modle, UV model, Watermark model. For each model individual datasets were considered.
Classification module classify the note based on its allignment. UV module uses images of currency under uv light and these images were used to determine the authenticity of the currency note based on security thread on it. Watermark module consists images of currency which were taken by a back light and these images are examined to check whether a currency note contains Gandhi watermark.
Each module contains train and test files which are to be executed first. The test model is then converted into tflite version due to available computational resources.
A final module is considered where all the tflite versions of three modules is integrated and checks whether a currency note is counterfiet or not.
Datasets for the three modules can be downloaded from below drive links:
classification model: https://drive.google.com/drive/folders/18av7hpDA7bId2x4y5qVJ1kSng763_oGq?usp=share_link
uv model: https://drive.google.com/drive/folders/13AG4D6jbDeC2IR0zIYL86jC6_ZDFFHjD?usp=share_link
watermark model: https://drive.google.com/drive/folders/1YG_NHDcbvNa9QRmbfbVVStFHQkem6q5d?usp=share_link
