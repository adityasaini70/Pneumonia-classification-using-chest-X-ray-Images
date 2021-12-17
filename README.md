# Pneumonia-classification-using-chest-X-ray-Images

Pneumonia is a deadly lung infection which impacts millions of people around the world. According to a report by the American Thoracic
Society in 2015, it was the world’s leading cause of death among children under 5 years of age.
This project deals with classification of pneumonia based on chest X-ray images using Machine
Learning based techniques. With this project,
we hope to make the diagnostic process easier
by providing quick and accurate results.

# Dataset
For training our models, we used the Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification hosted publicly under the Creative Commons License at https://data.mendeley.com/datasets/rscbjbr9sj/2.

![image](https://user-images.githubusercontent.com/49980787/124458163-4bc03a80-ddaa-11eb-87d2-fb707783f444.png)

### Dataset distribution
![image](https://user-images.githubusercontent.com/49980787/124458390-888c3180-ddaa-11eb-8ac7-3ffca39f0022.png)

# Evaluation metrics
* Accuracy
* Confusion matrix
* F1- Score (data is imbalanced)

# Models
1.  Baseline: HOG Features + SVM model
3.  HOG Features + ANN
4.  Vanilla CNN
5.  Transfer Learning using VGG-16

Please refer the notebooks at https://github.com/adityasaini70/Pneumonia-classification-using-chest-X-ray-Images/tree/main/Models for more information about the training workflow.

# Results
![image](https://user-images.githubusercontent.com/49980787/124458584-c5582880-ddaa-11eb-8817-36dd5a9c6868.png)

## Contributors
(Equal contribution by all)
* [Aditya Saini](https://github.com/adityasaini70)
* [Lavanya Verma](https://github.com/broompa)
* [Prabhat Soni](https://github.com/prabhatsoni99)

## References
- https://learnopencv.com/transfer-learning-for-medical-images
