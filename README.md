# Python Random Walker
This project is a little app that runs the random walker segmentation over an image. 

## Installation
This solution uses the pycharm community IDE to run it. So install this IDE and python 3.10.

Once the IDE is installed go to new project put the name that you prefer and use as Base interpreter Python 3.10.

Replace the code of the autogenerated main with the code in this project.

Go to python packages and look for the librarys that the code requieres and install it. for instance scikit-image, kivy, tkinter, cv2, matplotlib, numpy.

## Run the code

Once you run the code it will show 3 buttons, Open, Edit and Process.

The Open button will open a file selection window in which we will select the desired image in .png or .jpg format.

The Edit button opens a graphical interface for modifying the images necessary to perform the algorithm.

The Process button run the algorithm and show you the results that you can save later.

## How to use it.
Open the image that you want to run the algorithm.

Edit the image, for it we must select the red color that will be the one destined for the dark tones. Later we will use the green and blue that will be
for medium and light tones respectively. The algorithm only use some samples so don not draw all the image or it will not work properly. Once you finish the edition press the accept button and the edited image will appear in the app.

When you have the image open and have an "Edit.png" image in the same repository as the main you can press the process button to run the algorithm.

## Extra

The Edit creates a "Edit.png" image in the directory where the main is located so if you already have the image edited you can just put it in the same directory with "Edit.png" as name and press the Process button.
