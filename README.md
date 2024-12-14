This project is a real-time Sign Language Recognition System that uses computer vision and machine learning to detect and classify hand gestures into commonly used sign language expressions. The system helps bridge the communication gap by recognizing and translating signs into text.

#FEATURE

Real-time hand gesture detection using a system camera or webcam.
Classification of hand gestures into predefined labels:

"Hello"

"Okay"

"Thank you"

"Where"

Robust preprocessing to standardize input images.

Modular codebase for data collection, model training, and testing.

#TECHNOLOGY USED

Python: Programming language for implementation.
Ensure pip is installed by running:

python --version
pip --version

OpenCV: For image processing and webcam input.
pip install opencv

cvzone: For hand detection and classification utilities.

TensorFlow/Keras: For training and using the machine learning model.
pip install tensorfloe

NumPy: For array manipulation.
pip install numpy

Math: For geometric calculations during preprocessing.


Install the required dependencies:

pip install -r requirements.txt


#ENSURE THE WORKING.

Place the pre-trained model (keras_model.h5) and labels file (labels.txt) in the Model/ directory.


#DATA COLLECTION

Run the data_collection.py script to collect hand gesture data:
python data_collection.py
The collected data will be stored in the Data/ directory.


#TESTING

Use the main.py script to test the system:
python main.py


#Folder Structure

![image](https://github.com/user-attachments/assets/9721fb6f-c8b9-4a29-bd13-998048067648)

SignLanguageRecognition/
├── Data/                 # Folder containing collected data (optional if large)
├── Model/
│   ├── keras_model.h5    # Your trained model
│   └── labels.txt        # Label file for the model
├── main.py               # Testing script
├── data_collection.py    # Data collection script
├── requirements.txt      # Dependencies (libraries required)
└── README.md             # Project documentation


#OUTPUT

The system will display:

![image](https://github.com/user-attachments/assets/40d46f65-5601-44b2-b67e-7a1aff621a0b)

Webcam feed with a bounding box around the detected hand.
Predicted label of the hand gesture displayed above the bounding box.


#ACKNOWLEDGEMENT

cvzone library for simplifying computer vision tasks.
TensorFlow/Keras for providing an efficient platform for model training.
