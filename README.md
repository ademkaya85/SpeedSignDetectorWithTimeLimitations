# SpeedSignDetectorWithTimeLimitations

Traffic sign recognition (TSR) is getting one of the standards of the newest cars. One of the challenges in traffic sign recognition is that in some countries such as Germany, there might be a time limitation represented beneath the speed sign board. It is very difficult to read those time limitations as they are much smaller than the speed limit and they might be very similar as in the case, '22-5h' and '22-6h'. 

The algorithm I developed is able to read the time limitations beneath the speed limit sign while driving. It can differentiate the small differences between time limitations such as in '22-5h' and '22-6h'. This algorithm consist of a machine learning algorithm + some observations + basic mathematics.

There is no limitation for the resolutions of the video or image. With high resolution, it is possible to get more detection but this increases computational cost little. This is the main advantage of the algorithm. Computational cost of one detection for an image with size, for example, 720x920 might be larger than the computational cost for an image of size , for example, 2000x2500.    


The video below shows the success of the algorithm with various time limitations.    



https://user-images.githubusercontent.com/100349023/224855526-7f7ea158-8cfd-4078-b245-1a1cdb59c4eb.mp4



When the algorithm produces an outcome, it gives the correct one. More precisely, an outcome is produced when the algorithm is 100% sure. The video below was captured while driving around 50 km/h. The original video has the following properties. Dimensions: 1920 × 1080, fps: 30. The time limitation beneath the speed limit 30 was detected 27 times. This allow us to skip several frames so that one can obtain result in real time.

https://user-images.githubusercontent.com/100349023/227057961-8455a7f1-f6b4-4f85-bf0a-c3e219835fb6.mp4


Another difficulty in detecting sign speed accurs while driving with high speed. The algorithm is able to detect the speed limit correctly enough times. The following video was captured while driving around 80 km/h. The original video has the following properties. Dimensions: 1920 × 1080, fps: 30.  The speed limit 80 was detected 19 times.



https://user-images.githubusercontent.com/100349023/227689202-c34b054e-e340-4c63-b694-3d8ee23b5027.mp4

The algorithm was also tested for the speed limit 120. The following video was captured while driving around 120 km/h. The original video has the following properties. Dimensions: 1920 × 1080, fps: 30. The speed limit 120 was detected 13 times.




https://user-images.githubusercontent.com/100349023/227689276-b0c92516-df91-4c6d-a262-9c6f3045e5bb.mp4



I am eager to implement my algorithm on real cars and I am open to new opportunuties to do this. 
