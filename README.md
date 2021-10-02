# Watchman
Inspiration
A countless number of people drive on the highway day and night. Taxi drivers, bus drivers, truck drivers and people traveling long-distance suffer from lack of sleep. Due to which it becomes very dangerous to drive when feeling sleepy.

The majority of accidents happen due to the drowsiness of the driver. So, to prevent these accidents i build a system using Python, OpenCV, and Keras which will alert the driver when he feels sleepy.

What it does
Watchman is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving.

The objective of this intermediate Python project is to build a drowsiness detection system that will detect that a person’s eyes are closed for a few seconds. This system will alert the driver when drowsiness is detected.

How I built it
In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy. and if the score is above 23 it will alert the driver.

Challenges I ran into
Finding the dataset was definitely the challenge, and was definitely took the longest. Then uploading the model into github as the model was more than 25 mb.

Accomplishments that I am proud of
This is my first project on OpenCV and i got to learn much about it. Being totally new to Hackathons, the implementation of the entire project helped me realize the importance of collaboration and the dynamics of working in a project . In every Hackathon, proper time management plays a crucial role that can become a determining factor for the overall progress; I understood the instrumentality of following the code of conduct and treating fellow developers with respect while learning and improving through their feedback.

What i learned
I learned a lot about OpenCV and computer vision and also next time, don't waste time on finding good datasets to use, instead, follow the engineers code, "Make it barely work" probably Then focus on good datasets to use and annotate.

What's next for Watchman
Going to create a API so that company like Uber or any platform that provides rides can implement this application directly with ease. also try to create it into a standalone exe and android application so that all the Drivers could also use it. thus saving lot of lives.
