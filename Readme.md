# Optical Character Recognition (OCR) Project

## Overview
This project is an Optical Character Recognition (OCR) application developed in C, featuring a graphical user interface (GUI) built with the GTK library. The application processes images containing text and extracts the readable characters from them and saves them in a *.txt* file.

## Features
- Load images for OCR processing
- Preprocessing for better text recognition
- Character segmentation and recognition
- Graphical user interface using GTK
- Export recognized text to a *.txt *file

## Requirements
### Linux
Ensure the following packages are installed:
```sh
sudo apt update && sudo apt install -y gcc make libgtk-3-dev

## Build and Run

-1- Go to the OCR directory.
-2- From here, open the terminal and type make. This command will compile all the files and outputs an executable called UI_code.
-3- Run the executable (always on the terminal).
-4- Once the program opens, you can run our program. You can select an image by clicking on the button Open. Once an image is selected , click run and the image
will be processed. This process will output a file called Result. This file can be found in the current directory.


#- All the images can be found here : OCR/OCR/Testing_images
