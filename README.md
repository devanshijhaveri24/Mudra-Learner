# Mudra-Learner
One hand mudras(Asamyukta Hastas) detection and classifier

## Description 🎼
Mudras or hand gestures made using a single hand are called asamyukta mudra. They are mainly used in Indian classical dances like Kathak, Bharat Natyam, etc. 

![image](https://user-images.githubusercontent.com/63440529/179675027-382927b5-74ea-4b92-aeac-d6193c55d529.png)


## Setup 🖥️

1) First, you have to create a hand-mudra database. For that, run `CreateDataset.py`. Enter the mudra name and you will get 2 frames displayed. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
2) Repeat this for all the features you want.
3) For training the model, run `Trainer.py`
4) Finally, run `MudraLearner.py` for testing your model via webcam.

## Execution 🐉

```
python3 MudraLearner.py
```

## Future Scope 🔮
- Add Samyukta or two hand mudras

## References 🔱
 
 -  Ivan Grishchenko and Valentin Bazarevsky, Research Engineers, Google Research. [Mediapipe by Google](https://github.com/google/mediapipe)
 -  Guitar Learner by Akshay Bahadur. [Github link](https://github.com/akshaybahadur21/Guitar-Learner)
