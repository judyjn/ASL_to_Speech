# ASL_to_Speech
Sign Language is a mode of communication used by differntly abled people. There are different forms for sign languages such as American Sign Language(ASL), Indian Sign Language etc. .With this work, we expect to find a solution to bridge the communication barrier between sign language users and others.

This project detects ASL alphabets using SSD MobileNet in real time.It detects the ASL sign input by a tool called visualize boxes and labels on image array(), it is a function of function of visualization utils which is imported from the Object Detection API. The output image is then used to obtain audio output in real time using Pytesseract and Python text to speech Library. 
The tools used in this project are :
1. TensorFlow - CUDA, CUDNN
2. Object Detection API
3. OpenCV
4. Numpy
5. Keras
6. Python PIL - Python Imaging Library which provides the python interpreter with image editing capabilities.
7. PyTesseract - It is an OCR tool. It will read and recognize the text in images, license plates etc, it can easily read all image types
8. pyttsx3 - It is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline and is compatible with both Python 2 and 3.


https://user-images.githubusercontent.com/75877538/184372291-a4c1cab7-7f38-4054-81d6-ddc2f83dc509.mp4



https://user-images.githubusercontent.com/75877538/184372339-b1cd8321-4261-41c5-8eb2-5fb949713f93.mp4

Frame rate is reduced to 5fps to reduce computational complexity.
