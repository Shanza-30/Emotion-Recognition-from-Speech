# 🎤 Emotion Recognition from Speech

This project focuses on recognizing human emotions from speech audio using deep learning and speech signal processing techniques. The system classifies emotions like happy, sad, angry, neutral, etc., from audio files using MFCC features and neural networks.


## 📌 Objective
To build an intelligent system that can:
- Take speech audio as input  
- Extract meaningful audio features (MFCC)  
- Predict the speaker’s emotion using deep learning models  


## 🧠 Approach
- Audio preprocessing using Librosa  
- Feature extraction using MFCCs  
- Model training using Deep Neural Networks / CNN  
- Performance evaluation using accuracy, confusion matrix, and classification report  


## 📂 Dataset

This project uses the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** dataset.

🔗 Dataset Link (Kaggle):  
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio  

The dataset contains:
- Speech recordings from multiple actors  
- Emotions: neutral, calm, happy, sad, angry, fearful, disgust, surprised  
- Audio format: `.wav`  


## ⚙️ Features Used
- MFCC (Mel-Frequency Cepstral Coefficients)  
- Audio normalization  
- Optional data augmentation  


## 🤖 Models Used
- Deep Neural Network (Dense Layers)  
- CNN (for 2D MFCC input)  
- Comparison of model performances  


## 📊 Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- Training vs Validation Graphs  


## 🚀 How to Run

1. Clone the repository  
2. Download the RAVDESS dataset and extract it  
3. Update dataset path in code  
4. Install required libraries:


🔍 Sample Output

Input: Speech Audio
Output:

Predicted Emotion: Happy

📌 Applications

Voice assistants

Call center emotion analysis

Mental health monitoring

Human-computer interaction

👤 Author

Shanza Shakeel
Machine Learning / Data Science Enthusiast
   ```bash
   pip install librosa tensorflow numpy pandas matplotlib seaborn scikit-learn
