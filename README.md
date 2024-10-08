# Face-Recognition-Attendance-System-for-Groups-Using-Object-Identi-cation-Technique-

# steps to execute the project files 
 1. open a new terminal
 2. set the path of the project folder
 3. execute the given command line inputs respectively

# extract embeddings
python extract_embeddings.py --dataset dataset --embeddings output/PyPower_embed.pickle --detector face_detection_model --embedding-model openface_nn4.small2.v1.t7

# train model
python train_model.py --embeddings output/PyPower_embed.pickle --recognizer output/PyPower_recognizer.pickle --le output/PyPower_label.pickle

# test model 
python recognize.py --detector face_detection_model --embedding-model openface_nn4.small2.v1.t7 --recognizer output/PyPower_recognizer.pickle --le output/PyPower_label.pickle --image test_images/test1.jpg



# Result

![image](https://github.com/prabhatvit92/Face-Recognition-Attendance-System-for-Groups-Using-Object-Identi-cation-Technique-/assets/114719849/e6a5eecb-8125-42fd-9fc1-f9431cb67ff6)


Email: Prabhatmishra3112@gmail.com
whatsapp: 7004596360
