# Face recognition project using opencv
### OpenCV:
OpenCV (Open Source Computer Vision Library: http://opencv.org) is an open-source library that includes several hundreds of computer vision algorithms. The document describes the so-called OpenCV 2.x API, which is essentially a C++ API, as opposed to the C-based OpenCV 1.x API (C API is deprecated and not tested with "C" compiler since OpenCV 2.4 releases)

There are many modules available now a days that provides multiple features that works with the camera related data. It has many applications in all the technologies, like face unlock, attendance system, family member detection at doorbell, etc.

### Haar cascade Classifier-  

Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

OpenCV provides a training method, cascade classifier training or pretrained models, that can be read after loading the model. The pretrained models are located in the data folder in the OpenCV installation.

### PyWhatKit- 
it is a Python library with various helpful features. It is an easy to use library which does not requires you to do some additional setup. One of the feature in pywhatkit is kit.sendwhatmsg(...)This function can be used to send WhatsApp message at certain time, kit.sendwhatmsg_instantly(...) can be used to send message instantly whilekit.sendwhatmsg_to_group(...) can be used to send message to group.

### SMTP- 
SMTP or Simple Mail Transfer Protocol is an application that is used to send, receive, and relay outgoing emails between senders and receivers. When an email is sent, it's transferred over the internet from one server to another using SMTP. In simple terms, an SMTP email is just an email sent using the SMTP server. Google's gmail is an example of an smtp server. 
We have smtplib module in python that helps us in connecting to this server and use their functions.The smtplib module defines an SMTP client session object that can be used to send mail to any Internet machine with an SMTP or ESMTP listener daemon.

#### Task at hand- 
upon recognizing a particular face.
	👉 It send mail to your mail id by writing this is face of your_name. 
	👉 Second it send whatsapp message to your friend, it can be anything.

#### Approach- 
1. First, use the haar cascade classifier to recognize the face. Use cv2 model to crop the identified image and save it as a database.
2. Then create a private.py file having the login details, message, number defined by you. 
3. Device the programs to send mail and WhatsApp messages
4. finally, write a program to recognize a face and compare it with the database available, if it’s the same person, send message on mail and whatsapp. 

#### Using this approach, you can try different applications of the technologies available. Give it a try!
