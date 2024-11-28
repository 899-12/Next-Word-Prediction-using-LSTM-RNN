# Next Word Prediction using LSTM

## Project Overview

This project develops a deep learning model to predict the next word in a given sequence of words using Long Short-Term Memory (LSTM) networks. The steps involved in this project are outlined below:

### 1. Data Collection
We use the text of Shakespeare's *Hamlet* as the dataset. This rich and complex text provides an excellent challenge for building a predictive model.

### 2. Data Preprocessing
- The text data is tokenized and converted into sequences.
- Sequences are padded to ensure uniform input lengths.
- The data is then split into training and testing sets.

### 3. Model Building
The LSTM model is constructed with the following architecture:
- **Embedding Layer**: Converts words into dense vector representations.
- **Two LSTM Layers**: Designed for sequential data learning.
- **Dense Output Layer**: Uses a softmax activation function to predict the probability of the next word.

### 4. Model Training
- The model is trained on the prepared sequences.
- Early stopping is implemented to monitor validation loss and prevent overfitting.

### 5. Model Evaluation
The model is evaluated using example sentences to test its ability to predict the next word accurately.

### 6. Deployment
A Streamlit web application is developed, enabling users to:
- Input a sequence of words.
- Receive the predicted next word in real time.

---

## How to Run the Project

### Prerequisites
1. Python 3.8 or later
2. Required Python libraries (install using `pip`):
   - TensorFlow
   - NumPy
   - Streamlit
   - Other dependencies listed in `requirements.txt`

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
