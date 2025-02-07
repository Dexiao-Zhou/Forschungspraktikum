# Predicting Skateboarding Speed Using IMU

This project utilizes the gyroscope and accelerometer of an IMU to predict speed.

The project is divided into three main parts:
1. Training a YOLO v7 model to recognize the IMU from video (01_YOLO_training);
2. Using the trained YOLO model to calculate speed (02_speed);
3. Inputting IMU data and speed data into an LSTM network to train the model and make predictions (03_LSTM).

Since the project requires multiple intermediate datasets, such as video frames that need to be manually labeled for YOLO model training and speed data that must be validated and filtered before being used for LSTM training, Jupyter Notebook is used for coding. The generated plots help monitor the process in real time.

You can open the three folders separately, each containing the project's dependencies, including a `requirements.txt` file (or dependencies specified in Jupyter Notebook).

The essential data includes experimental video footage, IMU sensor data, YOLO model training data, the trained YOLO model, and the LSTM model. The Jupyter Notebook files contain code annotations and a structured project workflow.
