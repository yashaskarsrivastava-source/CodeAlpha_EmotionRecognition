# Emotion Recognition from Speech — CodeAlpha Task 2

## 📌 Objective
Recognize human emotions from speech audio using Machine Learning.

## 🎭 Emotions Detected
| Emotion | Label |
|---------|-------|
| 😐 Neutral | 0 |
| 😌 Calm | 1 |
| 😊 Happy | 2 |
| 😢 Sad | 3 |
| 😠 Angry | 4 |
| 😨 Fearful | 5 |
| 🤢 Disgust | 6 |
| 😲 Surprised | 7 |

## 📊 Dataset
- **Source:** RAVDESS — Ryerson Audio-Visual Database
- **Files:** 1440 audio files
- **Actors:** 24 (12 Male, 12 Female)

## 🛠️ Features Used
- MFCC (Mel Frequency Cepstral Coefficients)
- 40 MFCC Features per audio file

## 🤖 Model Used
- MLP Neural Network (256 → 128 → 64 layers)

## 🎯 Result
- **Accuracy: 71%**

## 📚 Libraries Used
- Librosa, Numpy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

## 👨‍💻 Internship
CodeAlpha Machine Learning Internship
