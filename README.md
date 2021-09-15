# Virtual-mouse
1. Used the mediapipe, opencv, autopy library
2. open the webcam, read the frames using cv2 and calculate the framepersecound
3. The primary thing is need to detect the hand is done by findhands method in 'handTrackingmodule.py' file
4. Later need to find the postion of hands. this is done by findposition method
5. ![image](https://user-images.githubusercontent.com/61477053/133412075-68a26bd6-a802-4b0f-83f8-358f3276376b.png)

6. Later need to find the index and middle finger
7. To perform mouse moving action used autopy
8. when the middle and index will become closer it will get clicked. The clicking operation performed based on the distance between middle and index finger
9. ![image](https://user-images.githubusercontent.com/61477053/133412716-4eb50af8-10be-44c4-ab33-4d17724ee4ee.png)



10. you need to run the notebook which provides the main operation and remaining like findpostion,find distance,finger up all these are implemented in 'handTrackingmodule.py' file
