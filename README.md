# Driver-Drowsiness-Detection-System

![image](https://user-images.githubusercontent.com/98420946/187268197-11c0c514-9bb1-47c2-a3bf-abe71cf208b8.png)


Driver fatigue leading to drowsy driving is a severe traffic safety problem and is widely believed to be one of the largest contributors to fatalities and severe injuries on the road at present.

Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving.The system detects the face and eyes of driver.Haar-cascade Classifier has been used to detect the face and eyes. Then the Eye-aspect ratio is calculated which is done by [formula].

![image](https://user-images.githubusercontent.com/98420946/187268346-cc01db25-17c7-43c5-8593-14bddccac059.png)


Drowsiness is detected when the Eye Aspect Ratio falls below a threshold value which is set to 0.5. The system at last plays an alarm when detected drowsy. 


The major library used in this project is openCV . It is library of Python designed to solve computer vision problems. Various functions of this library has been used to set up the camera and to detect faces and eyes. 

Pygame library has been used to play the alarm. 

Tkinter library has been used to design the interface of the project.



![image](https://user-images.githubusercontent.com/98420946/189584665-eb214455-a53c-40b0-a403-f4a2bb42eb9f.png)

