# Image Sonification
## Leonardo Bueno

### What is Image Sonification?
Image Sonification is a tool that allows you to sonify images! When you sonify an image it means that you are converting that image data (pixels) into an audio format that you can then listen to. The program works by taking an image, and then mapping frequencies to each row in the image pixels. Then, the intensity of each frequency is modulated based on the value of each pixel in that row of the image. Each of the frequencies are then synthesized additively, creating a sound. The added sounds and tempo are set so that the sound produced is sonically pleasing and not dissonant.

### How to use
Since this is more of a tool than an application, there is no graphical user interface, so the program is run through the terminal. There is an images directory in the project where you add the image(s) you want to sonify. You then pass into the call of the sonify function the name of the image you want to sonify, and after the program is run, a wav file is outputed into the sonifications directory within the project. From there, you can pull that wav file and listed to the sonic form of your image.

In terminal:
  1. Go into image_sonification folder in terminal (cd image_sonification)
  2. Call python main.py (name of image file)
  3. Output wav file (name of image file.wav) will be in image_sonification/sonifications, open output file to listen.
