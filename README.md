# **Face Detection Based Automatic Curtain**

**Note : This is an Engineering Clinics project done at VIT-AP University during my second semester(WIN 2017-18).Any plagiarism of any sort complete or partial will be not accepted. The git and commit history and project submission date will be shared as proof.Also it will be easier to trace plagiarist if he/she belongs to the same institute.**


# introduction
With technological advancement there are AC’s available which automatically maintains a particular temperature of the room even during owner’s absence . The compressor in the air conditioner is turned on and remains on until the room temperature decreases to be the same as the temperature of the thermostat. Once the desired temperature is reached, the compressor turns off until the room temperature increases again.In case the owner forgets to close the curtain before he leaves for his office then sunlight can easily penetrate through the glass and make the room warmer.As a result the AC will consume more power to maintain the temperature set by the user.
So we thought of making an automatic motorised curtain which opens only after detecting a human face in the room. we are already done with the prototype and we are sure that its real time application will significantly decrease the electricity bill generated.

# Following are our Objectives:
1. To detect a human face using Raspberry Pi camera module.
2. Controlling a motorized curtain based on number of faces detected.

# Methodology
1. Our project basically works on the principle of face detection.
2. Raspberry Pi camera module captures an image and send it to raspberry pi.
3. The image taken is converted into grayscale becauseimage in the form of grayscale can only be used to detect human face.
4. “detectmultiscale” function used in the face cascade (available in imported cv2 module) will search for human faces in the image taken.
5. If any human face is detected in that image,it return the list of detected faces(which is the list of rectangles Rect(x,y,w,h).
6. Then signal is given to H-Bridge circuit to rotate the motors and open curtain

# Conclusion
1. Our involvement in the project since last four months made us realise we can automate and simplify our daily activities using face detection algorithm.
2. Specifically our project “Automatic Curtain” (based on face detection) when used in real time, will significantly decrease the electricity bill generated.

# Future Scope
Project can be further improved 
1. By controlling curtain after detecting a specific face of a person and not just by any human face.
2. Also ,by including a light sensor in the project the curtain can be opened or closed according to the threshold limit set by the user. 

# Demo Link
https://www.youtube.com/watch?v=LMdrZr9hP0E


