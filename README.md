#ASL Hand Sign Language Recognition Project 🤚🔤

#Introduction 📝
This project aims to recognize American Sign Language (ASL) hand gestures and display the corresponding alphabet on the screen.

#Data Collection 📸
To gather data for our project, we captured approximately 300 images for each alphabet gesture using our computer's camera. These images focused on capturing the hand and finger movements necessary for each gesture. To extract meaningful features from these images, we utilized the Python ML library, Mediapipe, in conjunction with CV2. This combination enabled us to detect hands, identify landmark points on the hands, and ultimately compile a comprehensive dataset containing these hand features.

#Model 🤖
Our model is generated by applying the Random Forest Classifier Algorithm, which is then integrated with Mediapipe to analyze the hand gesture and recognize the alphabet. Thus, when presented with a new hand gesture image, the model processes the image and utilizes its ensemble of decision trees to predict the corresponding sign language alphabet. This enables users to convey messages effectively, bridging the communication gap with individuals with hearing impairments.

#Algorithm 🧠
Random Forest, a prominent supervised learning algorithm, finds application in classifying hand gestures for alphabets. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to enhance the accuracy of classifying hand gestures for alphabets.


#How to implement it:
1. Around 300 Images of each alphabet are available in the data Folder.
2. Dataset is generated in data.pickle file.
3. Model is genrated in model.p file.
4. Install the required libraries from requirements.txt.
5. Run the inference_classifier.py file.

#If you want generate your own model woth your data images:
1. Install the required libraries from requirements.txt.
2. Run the collect_imgs.py -> Images will be generated in the data folder.
3. Run the create_datset.py -> data.pickle gets created.
4. Run the train_classifier.py -> model.p is generated
5. Run the inference_classifier.py file.

Output:

https://github.com/Saahil3/Sign-Language-Recognition/assets/97357456/7aa1f967-c2c6-4a07-b8f5-638d66830949


