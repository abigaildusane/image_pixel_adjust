# Image Pixel Adjust
A python program showing how to access and modify individual pixels in an image using the pillow library.
# Description
This script:
	•	Loads an image x.png
	•	Reads the RGB values of the pixel at (0, 0)
	•	Sets the red channel of that pixel to 255
	•	Saves the modified image as output.png
	•	Displays the result
# Requirements
	•	Python 3.x
	•	Pillow:
	•	pip install pillow

# Usage
	1	Clone the repository
	2	Place an image named x.png in the project directory
	3	Run the script:
	⁃	python main.py
	⁃	After running, you will find output.png, the modified image
# Notes
	•	Pixel coordinates start at the top-left corner (0, 0)
	•	RGB values range from 0 to 255
	•	Works with RGB images (convert with img.convert("RGB") if needed)
