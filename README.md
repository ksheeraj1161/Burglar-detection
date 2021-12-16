# Burglar-detection

Complete simulation of a surveillance system has be achieved using appropriate techniques by decreasing additional effort for securing a place. .

For any location, setting up the CCTV cams to monitor is one task, storing all the captured video is another, for larger places a person to monitor all the activuty is to be recruited. Any of these extending tedious tasks can be eliminated by replacing with the procedures discussed in this project. 

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

