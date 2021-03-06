# HexaFace

This is the project for CMPT733 - Programming for Big Data II.

# Requirements:

- Latest version of Anaconda (https://www.anaconda.com/)

- TensorFlow 1.15 [conda create --name hexaface tensorflow=1.15]

- Keras [conda install keras]

- OpenCV [conda install opencv]

- Django 1.10 [pip install django==1.10]

- MTCNN [pip install mtcnn]

- keras-vggface [pip install keras-vggface] 

- Scikit-Learn [conda install scikit-learn]

- matplotlib [conda install matplotlib]

# Run Application:
Download the model weights (*.h5) files from the following path:<br>
https://bit.ly/3dkxza2 <br>
Move the downloaded files to hexaface/django/static folder.<br><br>

Open command line and go to the hexaface/django/ folder.<br>
Run the following command to start the server:<br>
python manage.py runserver<br><br>

if you got any errors when starting, run:<br>
python manage.py migrate<br><br>

This command runs the application server on http://127.0.0.1:8000 <br>
Pay attention that port 8000 may be occupied on your system.

# Google Cloud deployed version:
http://hexaface.ddns.net