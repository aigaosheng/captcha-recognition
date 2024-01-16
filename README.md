# Captcha recognition
Cacptcha recognition is a problem tomapping the input captcha image to captcha characters. Thus if the training data are available, i.e. captcha image - character text pair, then the supervised learning can be used to train a model to mapping input image into output text. But if training data is not available, we can exploit the pretrained model for the task of image to text. In the notebook, two solutions are provided:
+ Traditional macine learning model: Logistic regression
+ SOTA pretrained image to text for printed characters available in Huggingface

## Logistic regression
Use the provided sample data, randomly split into train & test data set. The train data is used to train logic regression model, and test it using test set.
Model name: model/captcha_lr.pkl
Test output: output_lr

## Large pretrained model for image-to-text
Model: download from Huggingface (refer code)
Test output: output_i2t

