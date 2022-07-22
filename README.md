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
<table>
<tr>
<td><img src="https://user-images.githubusercontent.com/63440529/180378397-c2f70020-8447-4675-9db5-2846c4e00e7c.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180378483-322935aa-2598-4e77-ab44-04a5a5fe52ab.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180378746-0fa03ea1-23ef-431c-b72c-9ed828867370.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180379321-07df2b34-23a0-4edb-8b41-8f74b99d26b1.png" width="200" height="200" /></td>
</tr>
<tr>
<td><img src="https://user-images.githubusercontent.com/63440529/180379426-083cb6d8-899f-42fe-9e52-bda2d5554b5b.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180379552-eda0d961-1433-41e8-928d-62081c6c9bbb.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180379701-0075982d-2e2c-4134-a6e1-28da80de397b.png" width="200" height="200" /></td>
<td><img src="https://user-images.githubusercontent.com/63440529/180379783-edc9e366-0d1f-49ec-a699-38d0defb5290.png" width="200" height="200" /></td>
</tr>
</table>

## Future Scope 🔮
- Add Samyukta or two hand mudras

## References 🔱
 
 -  Ivan Grishchenko and Valentin Bazarevsky, Research Engineers, Google Research. [Mediapipe by Google](https://github.com/google/mediapipe)
 -  Guitar Learner by Akshay Bahadur. [Github link](https://github.com/akshaybahadur21/Guitar-Learner)
