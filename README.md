# Gesture-recognition

We find inspiration in the captivating world of gesture recognition depicted by movies like "Ready Player One." We're witnessing how virtual reality (VR) is rapidly reshaping the gaming landscape, capturing the imagination of major industry players. Companies like Meta have unveiled exciting innovations, like their electromyography (EMG) wearable wristband, which can detect hand movements and seamlessly integrate with their advanced AR glasses, Nazare. This isn't just about gaming; it's also about revolutionizing how we interact with technology in numerous real-world scenarios. Gesture recognition is making inroads in fields like healthcare, where it aids in surgical procedures, and in education, where it enhances interactive learning experiences. Beyond that, it's transforming accessibility for the deaf community by facilitating sign language recognition. Our project is driven by the desire to explore this exciting field further, gain a deeper understanding of its capabilities, and hope to experiment with more possibilities in this area. 

Credits to the Hagrid dataset as dataset resource(Kapitanov Alexander et al, HaGRID - HAnd Gesture Recognition Image Dataset (2022). Cornell University, arXivLabs. Url: https://arxiv.org/pdf/2206.08219.pdf)

Inside of this repo, there are two folders:
  The "model" is for the best model we trained on Resnet18, Resnet50 and Resnext101. 
  The "experiment" is the original colab file which shows you how we trained and tested on the data. 

The dataset is already loaded inside of the google colab. 

The model is for classification of 19 kinds of gestures(those displayed in the picture and no_gesture class): 
![image](https://github.com/Charlo-M/Gesture-recognition/assets/75926255/dbc8e6b4-929b-4b36-a965-e1ac266279ed)

We seek to classify the gestures. To test model robostness, we use three different kinds of data augmentation and test our model based on the dataset. 
![image](https://github.com/Charlo-M/Gesture-recognition/assets/75926255/990ce9eb-758f-465b-b0e8-d68213192755)
