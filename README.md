Setup

Go to 'Assets/Features/Speed Estimator/Trainer'
Create a python environment python3 -m venv .venv
Activate the virtual environment
Install the requirements pip install -r requirements.txt
You can also use setup.ps1

Train

Activate your virtual environment
Run the training script python train_speed_estimator.py
The input data is 'data/training_data.csv'
This input data is in the telemetry format
The output model will be saved in 'model/speed_estimator.onnx'
