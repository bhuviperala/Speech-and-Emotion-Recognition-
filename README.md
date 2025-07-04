# Speech-and-Emotion-Recognition-
Used LSTM and MFCC on RAVDESS dataset for emotion classification 

1. Initialize Git Repo Locally
Open a terminal in your project directory and run:

bash
Copy
Edit
git init
git add .
git commit -m "Initial commit: Speech and Emotion Recognition using LSTM and MFCC"
2. Create GitHub Repository
Go to GitHub and create a new repository named something like:

Copy
Edit
speech-emotion-recognition-lstm-mfcc
Don't initialize it with a README or .gitignore (since you've already initialized locally).

3. Push to GitHub
bash
Copy
Edit
git remote add origin https://github.com/YOUR_USERNAME/speech-emotion-recognition-lstm-mfcc.git
git branch -M main
git push -u origin main
Replace YOUR_USERNAME with your GitHub username.

📁 Recommended File Structure
text
Copy
Edit
speech-emotion-recognition-lstm-mfcc/
│
├── data/                     # Put RAVDESS audio files here or link to dataset
├── models/                   # Save trained models
├── notebooks/                # Jupyter notebooks for EDA and training
├── src/
│   ├── preprocess.py         # Code for loading and extracting MFCCs
│   ├── model.py              # LSTM model definition
│   └── train.py              # Training loop and evaluation
│
├── requirements.txt          # List of required Python libraries
├── README.md                 # Project overview
└── .gitignore                # Files/folders to ignore (e.g., *.pyc, /models)

📌 Example .gitignore
gitignore
Copy
Edit
__pycache__/
*.pyc
*.h5
*.pkl
models/
data/
📌 Example requirements.txt
nginx
Copy
Edit
numpy
librosa
matplotlib
pandas
scikit-learn
tensorflow
