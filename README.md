Image_Text_Reader

It's a very basic tool to read images , images formatted like a restaurant-menu.

Tesseract-ocr
This tools need tesseract-ocr engine. Help yourself with this --

https://github.com/tesseract-ocr/tesseract/wiki
Linux
Tesseract is available directly from many Linux distributions. The package is generally called 'tesseract' or 'tesseract-ocr' - search your distribution's repositories to find it. Thus you can install Tesseract 4.x and it's developer tools on Ubuntu 18.x bionic by simply running:

sudo apt install tesseract-ocr
sudo apt install libtesseract-dev

OCR extracts text from the image and displays the text on the Text field.
The Text can then be translated to any language and played in audio mp3 format.
The images are uploaded on the drop down part of the flask web application.
