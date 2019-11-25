# INTEREC P.S
INTEREC P.S is  an unbiased facial recognition API for online exam, that employs the best of machine learning procedures in Artificial intelligence. It offers a continual a video support that monitors the exam process from start to finish

It uses flask **server** for running the keras neural network model. 
The model runs on the server side and accepts requests from clients.

Facial recognition is based on Facenet model.


For running:
1. With python3 and pip installed, type this command in the terminal to install requirements 
```
pip install -r requirements.txt
``` 
2. Run the application with
```
python keras_server.py
```
3. go to browser and type **http://localhost:5000** in the url to access the site
4. Enjoy!



#### References:
- Code for Facenet model is based on the assignment from Convolutional Neural Networks Specialization by Deeplearning.ai on Coursera.<br>
https://www.coursera.org/learn/convolutional-neural-networks/home/welcome 

