### VoiceAgeClassifier

This project is a machine learning-based voice age classification system developed as a Capstone Design project. It classifies a user's age group by analyzing their voice input, extracting MFCC features, and applying a convolutional neural network (CNN) model.

---

### Project Overview

The goal of this system is to enhance user interaction in voice-based platforms, such as kiosks or voice assistants, by adjusting responses to suit the perceived age group of the user. The model processes voice recordings to extract relevant acoustic features and predict the speaker's age category.

---

### Features

- Converts audio data into MFCC (Mel-frequency cepstral coefficients) features  
- Classifies audio samples into age groups using a CNN  
- Outputs training and validation accuracy  
- Displays confusion matrix and classification metrics  
- Designed for scalable application in age-adaptive voice interfaces  

---

### Technologies Used

- Python  
- TensorFlow / Keras  
- Librosa  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

### How to Run

1. Clone this repository:  
   `git clone https://github.com/your-username/VoiceAgeClassifier.git`

2. Install dependencies:  
   `pip install -r requirements.txt`

3. Open the notebook:  
   `oneshotwedied.ipynb`

4. Run the notebook cells sequentially to:  
   - Preprocess and load the data  
   - Extract MFCC features  
   - Train the CNN model  
   - Evaluate performance  

---

### Directory Structure
'''project-root/
├── audio_data/ - Raw voice recordings by age group
├── mfcc_data/ - Preprocessed MFCC feature arrays
├── models/ - Trained model files
├── oneshotwedied.ipynb - Main notebook
└── README.md'''


---

### Performance

Model accuracy and confusion matrix will be generated after training. These are displayed directly in the notebook output.

---

### License

This project is for academic use only as part of a Capstone Design course. Redistribution or commercial use is not permitted without permission.


