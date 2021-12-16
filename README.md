# Burglar-detection

Complete simulation of a surveillance system has be achieved using appropriate techniques by decreasing additional effort for securing a place. .

For any location, setting up the CCTV cams to monitor is one task, storing all the captured video is another, for larger places a person to monitor all the activuty is to be recruited. Any of these extending tedious tasks can be eliminated by replacing with the procedures discussed in this project. 

- cv2.VideoCapture()

Using Live camera feed: You pass in an integer number i.e. 0,1,2 etc e.g. cap = cv2.VideoCapture(0), now you will be able to use your webcam live stream. The number depends upon how many USB cams you attach and on which port.

Playing a saved Video on Disk: You pass in the path to the video file e.g. cap = cv2.VideoCapture(Path_To_video).

Live Streaming from URL using Ip camera or similar: You can stream from a URL e.g. cap = cv2.VideoCapture( protocol://host:port/video) Note: that each video stream or IP camera feed has its own URL scheme.  

Read a sequence of Images: You can also read sequences of images, e.g. GIF.



- Background Subtraction

Done by generating a foreground mask. Separates out foreground elements from the background detecting dynamically moving objects. Majorly used for object tracking


- Contour Detection

When the previous technique subtracts the background, this one detects the borders of the remaining objects in the image. So it works as when there is a movement in the camera region, it subtracts the other remaining background and only focus on movemement of person detecting its border.


<h1> Requirements </h1>

- IP Webcam app on mobile or wifi smart cctv cams
- External storage device or computer storage
- Jupyter notebook or google collab
- Libraries: <br>
        1. Numpy <br>
        2. Opencv <br>
        3. Time <br>
        4. Datetime <br>
        5. deque <br>

