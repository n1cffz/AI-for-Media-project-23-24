## Emotion-driven Music Generation vias Neural Network Classifier Incorporating Ocular-Centric Approach. 

This repository contains the implementation of an emotion-driven music generation system using a neural network classifier that incorporates an ocular-centric approach. My aim for this project is to focus on making a classifier using critical theory and in comparison to pre-existing emotion recognition classifiers such as the Haar Cascade classifier. I hope to furrther this project for my thesis by experimenting with generative music to produce an outputs based on detected emotional cues ( eye, mouth and nose focal points).


### Data collection
The data for training the neural network classifier was collected from online images sourced from Pinterest. The images were manually curated to represent a diverse range of emotional states and were annotated with labels corresponding to four different emotional classes. The emotional classes used in the classification include (but are not limited to):
1. Happy
2. Sad
3. Angry
4. Neutral

The curated dataset from Pinterest served as the foundation for training the neural network classifier, enabling it to recognize and classify emotional cues present in ocular movements during the subsequent phases of the project.


### Requirements ( for the image classifier)
- Python
TensorFlow
Keras
NumPy

### How to run this project.
The first labelled file within this porject ( '1-Image-classification-dataset.ipynb') does not need to be re-run as the data has been provided in the correct directories. This has been left in this project to show methods of data curation from Pinterest.

The majority of the classification training occurs within the third file ('3-Data-cleaning-and-training.ipynb'). Run the image processing code ( which implements Haar Cascade Classifier + shape_predictor_68) then training as shown. 

### Data sheets
The following can be found: 
- 'emotional-class-datasheet.csv'
- 'facial_landmarks_data.csv'

# Model evaluation
The test loss and accuracy calculated and a new image file ('new-image.png') has been used to evaluate the classification model so far.
