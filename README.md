# 🔮 Next Word Prediction using LSTM with Attention Mechanism

This project implements a **Next Word Prediction** system using **LSTM** networks enhanced by an **Attention Layer**. It is specifically trained on AI and ML research abstracts collected from ArXiv. The model predicts the most probable next word in a given sequence of words, serving applications like autocomplete systems and intelligent text generation.

## 🧠 Project Overview

- **Goal**: Predict the next word based on a given sequence using LSTM networks and an Attention layer.
- **Dataset**: Abstracts from AI/ML papers on ArXiv.
- **Architecture**: A hybrid ensemble of three LSTM models trained on different sequence lengths (2, 4, and 6).
- **Frontend**: HTML & CSS web interface
- **Backend**: Flask API to serve the model.

## ⚙️ Features

- Deep learning models using Bidirectional LSTM and Attention layers.
- Models trained and evaluated with sequence lengths of 2, 4, and 6.
- Attention layer improves context awareness and prediction accuracy.
- Visualized training/validation loss and accuracy for performance comparison.
- Web-based user interface for interactive word prediction.

## Model Architecture 
The model integrates the attention mechanism with LSTM as shown below:
The attention mechanism selectively focuses on important words in the sequence to improve next-word prediction accuracy.
![image](https://github.com/user-attachments/assets/d377d03a-3a6c-4797-82c9-fefc8cc0b6d8)

## LSTM with Attention Model
![image](https://github.com/user-attachments/assets/15b64e48-2f08-4951-b516-ca6802b04f42)

## Architecture of Attentin Layer
![image](https://github.com/user-attachments/assets/d3a7bda0-3ff6-4296-b249-d9e2405aea44)

### 🔧 Prerequisites
- Python 3.8+
- TensorFlow / Keras
- Flask
- NumPy
- Matplotlib
- Jupyter Notebook
- NLTK

### 📦 Setup
```bash
# Clone the repository
git clone https://github.com/deivanand/Next-Word-Prediction.git
cd Next-Word-Prediction

# Install dependencies
pip install -r requirements.txt
```

## Results 
Attention-based models consistently outperform base LSTM models in terms of test loss.
![image](https://github.com/user-attachments/assets/0ad13a96-3d94-4a7e-aca9-4de61714d92a)

## Output:
![image](https://github.com/user-attachments/assets/379c5e07-913b-4073-9344-8235994f865c)





 

