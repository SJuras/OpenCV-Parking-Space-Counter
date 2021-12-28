# OpenCV-Parking-Space-Counter
Open-CV / Python project, using Open-CV to monitor the parking lot and count all available and occupied spaces in real time. 

# Description
Program detects parking spaced on a parking lot, differentiates free from occupied spaces and counts free (avaliable) spaces.  

# Project structure
Project constist of main.py file, ParkingSpacePicker.py file and Assets folder

Assets folder contains a testing image and a testing video (mp4 format). Testing image is showing the parking space, video shows the same parking space with several cars moving.

# How to use
Run the main.py file

The program will open the Video window on your screen. 

All parking spaces will be designated with a rectangle. Free spaces will be designated with a green rectangle and occupied spaces will be designated with a red rectangle. 

On the bottom-left edge of every rectangle there will be numbers shown, these numbers represent the number of white pixels during the video processing. The program counts the white pixels to differentiate occupied from free spaces, occupied spaces contain more pixels than free spaces. 

Spaces Counter is located on the top-left corner of the window screen. 
left number shows how many free spaces there are, and right number shows the total number of parking spaces. 
