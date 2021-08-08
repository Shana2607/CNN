# CNN



def label_img(img):
    word_label = img.split('.')[-3]
   
 # DIY One hot encoder
    if word_label == 'cat': return [1, 0]
    elif word_label == 'dog': return [0, 1]

Libraries Required :

TFLearn – Deep learning library featuring a higher-level API for TensorFlow used to create layers of our CNN
tqdm – Instantly make your loops show a smart progress meter, just for simple designing sake
numpy – To process the image matrices
open-cv – To process the image like converting them to grayscale and etc.
os – To access the file system to read the image from the train and test directory from our machines
random – To shuffle the data to overcome the biasing
matplotlib – To display the result of our predictive outcome.
tensorflow – Just to use the tensorboard to compare the loss and adam curve our result data or obtained log.
