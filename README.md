# ASL-HackHer (Artificial Sign Language)
Created a program in 24 hours that uses artificial intelligence to translate American Sign Language into English text in real time. 
Competed with other groups in a Hackathon, and won in the category for use of best artificial intelligence model.
With verbal languages, we can communicate through widespread applications like Google Translate, 
but with language communicate barrier between people through ASL and people who can’t, there is no just tool. 
Our friend has a deaf parent. We know many deaf people - grandparents and even one of us (me). 
There is no expectation for people to learn sign language unless they know someone that deaf. 
With verbal languages, we can communicate through wide-spread applications like Google Translate, 
but with language communicate barrier between people through ASL and people who can’t, there is no just tool. 
We set up the live video feed through our computer camera, and had it track hand motion through cv2 library. 
While the video was still on, we are constantly checking if there are any hands in frame. 
If there are one, we generate a box around it and get the dimensions, which we use to create the image (our data). 
Since all the images of the hands are different sizes, we had to crop each image, proportionally resize it, and center it on a white background to 
have the teachable machine accurately train the AI model. We later replicated our steps to accommodate two hands as well. The way that the AI 
works is that we use detection and classification. Once we have the position and data points of the hand, we could classify different phrases and letters, 
through and generating an AI model. In other words, we would collect hundreds of images of the same sign, and generate an AI model with teachable machine.
After uploading the AI model to our project folder, we, then, would use the cv2 detection capacbilties to label and to detect if 
someone was signing the same sign in real time. 
As we continue to build this application, we would like to incorporate text to speech and expand the data in our project. 
So that, people can communicate with one another without any barriers. Also making it a mobile application where we can translate an sign language into any language. 
Every difficult to hold a conversion. Our application does it real time. 
Also can be implemented in daily life like in doctors office, thru a drive thru, etc. have it has a built in feature in zoom calls and 
video calls for easier communication. All around accessibility 





