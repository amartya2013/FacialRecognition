# Facial Recognition With Rasberry  Pi
&nbsp;
## Requirements:
- **Rasberry PI 4+**
- **Rasberry Pi Camera 2**
- **A display with HDMI ports**
- **Keyboard and Mouse to operate Rasberry Pi**

## Step 1:

**Download image_capture.py folder and change the 'PERSON_NAME' variable on line 8 to the name of the person who's picture you are taking. Then run the program and press space key to take pictures to train the model. These pictures will be saved in dataset folder.**

## Step 2:

**Download and run model_training.py this will train the model and save it to encodings.pickle**

## Step 3: 

**Download and run facial_recognition.py**

## Step 4(Optional):

**You can also start an action when a authorized face is detected. First add that face to list of authorized names in line 36 of facial_recognition_hardware.py. Then in line 72 or 79 you can execute the action of your choice. I have used a speaker and an LED to indicate that there is an authorized face detected.**
