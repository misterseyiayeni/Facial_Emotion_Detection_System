# Facial Emotion Detection System


## The Context
Deep Learning has found applications in many predictive tasks relating to more unstructured forms of data over the last few years, such as images, text, audio and video. Many of these tasks seem to be in the vein of a larger direction of predictive modeling that aims to match human-level performance on such tasks, because humans have evolved to specialize in performing intelligent actions on such unstructured data. As a specific branch of AI (also called Affective Computing or Emotion AI) Artificial Emotional Intelligence stands for the study and development of technologies and computers that can read human emotions by means of analyzing body gestures, facial expressions, voice tone, etc. and react appropriately to them.

In the field of human-machine interaction, it has been found that as much as 55% of communication of sentiment takes place through facial expressions and other visual cues. Therefore, training a model to identify facial emotions accurately is an important step towards the development of emotionally intelligent behavior in machines with AI capabilities. Automatic facial expression recognition systems could have many applications, including but not limited to any use case that requires human behavior understanding, detection of mental disorders, and creating a higher quality of virtual assistant for customer-facing businesses. Facial emotion detection is an area of computer that is very critical to the advancement of several aspects of social living. It can be used for:

Human-computer interaction: our engagement with AI-enabled devices can be read and provisioned for (our moods can be read and various actions taken, it can be used to save a human in distress or trouble just by reading their countenance and calling the cops e.g. if someone has been held against their will, fear, anxiety can be read and help can be sought, a patient with a medical condition can be monitored for emergency care etc).

CGI-enabled imaging: it can be used to read faces and project that into the screen to appropriately capture facial movements and expressions. Businesses can also leverage this to proactivaly determine engagement with customers.

Forensic investigation: in homicide cases, it can be used to estimate the last few minutes, seconds, even possibly hours of victims involved

## Objective
use Deep Learning and Artificial Intelligence techniques to Create a computer vision model that can accurately detect facial emotions. The model should be able to perform multi-class classification on images of facial expressions, to classify the expressions according to the associated emotion.
The key questions:

How do we reliably source (clean) data and if messy, then perform EDA to make it clean?
How do we carry out research studies into the application of Artificial Emotional Intelligence and advance its cross-discipline interactions nad applications?
How do we achieve an almost perfect performance (precision, recall, F1-Score, etc) that will qialify our work as deployment-ready

## Problem Formulation:
- Reliable and accurate identification of facial emotions.
- Gap in human-computer interaction.

## About the Dataset
The data set consists of 3 folders, i.e., 'test', 'train', and 'validation'. Each of these folders has four subfolders:

‘happy’: Images of people who have happy facial expressions.
‘sad’: Images of people with sad or upset facial expressions.
‘surprise’: Images of people who have shocked or surprised facial expressions.
‘neutral’: Images of people showing no prominent emotion in their facial expression at all.

I have appended images of the training and prediction processes:

Sample of happy faces
![happy_faces_sample](https://github.com/user-attachments/assets/e5dfe908-ace6-42e8-adaf-f9418fcbe722)

Sample of sad faces
![sad_faces_sample](https://github.com/user-attachments/assets/b2e56cce-03ec-4f2c-88eb-1476fdaadbeb)

Sample of neutral faces
![neutral_faces_sample](https://github.com/user-attachments/assets/17e1f1fa-435b-4dc5-a84c-30003e9d1c17)

Sample of surprised faces
![surprised_faces_sample](https://github.com/user-attachments/assets/86e8e2fa-0f14-46eb-bec7-cb2f606568f5)

Distribution of training dataset
![train_distr](https://github.com/user-attachments/assets/462bcb6e-dc88-4807-90cb-8bbbbd4c580b)

Distribution of test dataset
![test_distr](https://github.com/user-attachments/assets/823d19a1-078b-4fae-bee7-dafb86cbd6a3)

Distribution of validation dataset
![valid_distr](https://github.com/user-attachments/assets/feda6c86-7841-41f9-97ba-18428c60efc2)

Training and validation accuracy for base model
![train_val_accuracy_base_model](https://github.com/user-attachments/assets/5a3c35a0-9c02-4c25-b15d-67118faf9ed7)

Training and validation accuracy for second model
![train_val_accuracy_second_model](https://github.com/user-attachments/assets/f0d267e9-c0d1-4c7c-9b7e-3ff7ae3895f3)

Training and validation accuracy for vgg16 model
![train_val_accuracy_vgg16_model](https://github.com/user-attachments/assets/32d1ab80-f7fb-4c67-acd3-fcaedf906cc1)

Training and validation accuracy for resnet model
![train_val_accuracy_resnet_model](https://github.com/user-attachments/assets/c0777900-9180-42a6-af64-ba3f57d8e5a7)

Training and validation accuracy for efficientnet model
![train_val_accuracy_efficientnet_model](https://github.com/user-attachments/assets/96cabcf3-5380-4f0a-8944-eaed415afbbe)

Training and validation accuracy for complex model
![train_val_accuracy_complex_model](https://github.com/user-attachments/assets/a1bae75b-d2d3-4413-a221-4aad22aee810)

Confusion matrix of final model
![confusion_matrix_final_model](https://github.com/user-attachments/assets/985990c6-1ab1-43ee-b879-bcd63ae15a5a)

Prediction with final model
![prediction_with_final_model](https://github.com/user-attachments/assets/76c4f737-5c72-4b6b-94d6-6049511e595b)

Training and validation accuracy for final model
![train_val_accuracy_final_model](https://github.com/user-attachments/assets/33ece21a-02e8-4c58-83a4-397d82c854bf)

Second prediction with final model
![second_prediction_with_best_model](https://github.com/user-attachments/assets/e6f64b99-bcf3-40ad-93b2-d1f09601ed90)

Precision, recall, F1 of final model
![precision_recall_f1_final_model](https://github.com/user-attachments/assets/ee9f0480-af3d-4a3c-8680-d90919deb0b5)
