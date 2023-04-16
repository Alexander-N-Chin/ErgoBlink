# ErgoBlink
App detects bad posture & blinking patterns, reminds you to take breaks, for healthy screen time habits.

![Application](https://github.com/Alexander-N-Chin/ErgoBlink/blob/main/good.png)

## Demo Video

[![Demo Video](https://img.youtube.com/vi/X1cxh6VUQko/0.jpg)](https://youtu.be/X1cxh6VUQko)

## Table of Contents
- [Description](#description)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Contributors](#contributors)
- [Links](#Links)

## description

ErgoBlink is a fully functioning application that helps mitigate computer vision syndrome and improve posture, overall helping with better human-computer interaction and improving health. It achieves this by using computer vision and machine learning algorithms to classify and detect bad posture and eye blinking patterns, as well as providing reminders for screen breaks. The bad posture classification/detection feature uses the front-facing camera on the device to capture the user's posture in real time. 

The algorithm analyzes the posture using deep learning techniques to determine whether it falls within a range of bad postures. When a bad posture is detected, the app gives the user a gentle reminder to adjust their posture. The blink interval detection feature monitors the user's blinking patterns and alerts them if they are not blinking frequently enough. The app uses computer vision to track the user's eye movements and detect the time intervals between blinks using Eye Aspect Ratio (EAR). If the user's blinking frequency falls below a healthy threshold, the app sends a notification to remind them to blink. The screen time reminders feature helps users manage their screen time by providing reminders to take breaks at regular 20 min intervals. Users can set custom intervals, and the app will remind them to take a break after the specified duration. During the break, the app may suggest activities to do that don't involve a screen, such as stretching or going for a walk. 

Overall, this app provides a comprehensive solution for promoting healthy screen time habits. By detecting bad postures, monitoring blinking patterns, and providing screen time reminders, the app encourages users to take care of their physical and mental health while using digital devices.

## Getting Started

1. install all dependencies
2. run each cell in Align.ipynb

### Main Dependencies

1. mediapipe
2. numpy
3. pickle
4. pandas 
5. playsound
6. winsound
7. threading
8. cv2  
9. dlib  
10. imutils
11. scipy.spatial
12. imutils
13. pygame

## Contributors

Geeth Santhoshvaran Gunnampalli (Github: thetechie7)

Alexander Nim Chin (GitHub: Alexander-N-Chin)

Nikhil Maraboyina (Github: nmaraboyina)

## Links

https://ergoblink.geethg.com/

https://devpost.com/software/ergoblink





