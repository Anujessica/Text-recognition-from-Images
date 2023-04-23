# Text-recognition-from-Images

The goal of this project is to utilize Python programming language to transform an image that has textual information into its corresponding textual format. The project relies on Optical Character Recognition (OCR) technology to identify and extract the text from the given image.

#pre-requesites for Project

To use this project, you must have Python, OpenCV, and pytesseract installed on your computer.

Here are the steps to install pytesseract:

1.Download and install tesseract using the Windows installer available at: @https://github.com/UB-Mannheim/tesseract/wiki

2.Make sure to note the tesseract path from the installation. The default installation path may vary, but at the time of this edit, it was: C:\Users\USER\AppData\Local\Tesseract-OCR. It is important to verify the installation path.

3.Install pytesseract, which is a tesseract module built for Python, using the command: pip install pytesseract

4.Before calling image_to_string, set the tesseract path in the script using this line of code:
pytesseract.pytesseract.tesseract_cmd = r'C:\Users\USER\AppData\Local\Tesseract-OCR\tesseract.exe'

#Usage

OpenCV is a powerful library that provides convenient methods for reading and writing a diverse range of image file formats, including JPG, PNG, and TIFF. Additionally, it simplifies the process of displaying images on screen and allows for user interaction with the opened window.

If OpenCV is unable to read an image, it is important to verify that the input filename was specified correctly, as the cv2.imread function will return a NoneType Python object if it fails.

Pytesseract, also known as Python-tesseract, is a Python library that facilitates Optical Character Recognition (OCR). This tool has the ability to recognize and extract text from a variety of sources, such as images and license plates.

#Limitations

I added some sample files in PNG and JPEG formats to test the project's accuracy. However, I noticed that the project faces difficulty in extracting text from images with curly fonts. I understand that the OCR technology used in this project is not always 100% accurate, and its accuracy can be impacted by various factors such as image quality, font type, and image resolution. Hence, I plan to test the project using a diverse range of images to evaluate its performance and identify any potential limitations.
