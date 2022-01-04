# Facial-Expression-Sentiment-Analysis
An emotion detector for multi-faced real-time scenes

Face detection in this project is done in real-time using Haar cascades and then each face is classified into an emotion category. 
Sentiments are analyzed based on the VGG-Face model and cosine similarity used in Facebook's DeepFace framework. 
DeepFace is originally designed to handle the dominant face expression in the frame, but some modifications have been made to cope with multiple faces.

![](FaceSentiment.gif)
