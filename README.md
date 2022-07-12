# COVID-19-Image-Classification

About Data: The training dataset contains X-ray and CT scan images of patients with positive Corona test and negative Corona test.

Aim: To build a CNN model that will analyze and detect if the patient is a COVID (i.e. the target value as 1) patient or Non-COVID (i.e. the target value as 0) patient.

Loaded Libraries and dataset, loaded image file path, confirmed if number of labels is equal to number of images, converted the file paths to dataframe, combined labels with images for classification, pre-processed image dataset, separated images from labels, divied the data into training and testing dataset, sclaed the data, build CNN model and performed hyperparameter tunning to compare accuracy and check how the CNN network plateaus, used Tensorboard to visualize the result.
