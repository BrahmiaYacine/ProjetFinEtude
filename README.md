# Video-based-human-action-recognition-using-deep-learning
Falls are one of the most critical health risks for the elderly, potentially being an indirect cause
of death in certain circumstances. Additionally, demographic projections indicate a global
increase in the elderly population. In this context, automated fall detection and prediction
models are of paramount importance, particularly in AI applications that utilize ambient sensors
or computer vision. In this thesis, we focus on human action recognition based on video
recordings from surveillance cameras using computer vision techniques. More specifically, we
concentrate on fall detection based on deep learning. In our approach, we first apply the YOLO
model to detect individuals in each image of the CAUCAFALL dataset. We then extract a
feature vector that we use to calculate the aspect ratio of the bounding boxes around individuals
to annotate their state. In the final step, we employ various supervised and unsupervised
classifiers to train our model to classify fall and non-fall events. Our training achieved an
accuracy of 97% using the KNN classifier with neighboring values for other classifiers.
