# Next Word Prediction using LSTM

A deep learning-based Next Word Prediction application built using **TensorFlow/Keras LSTM** and deployed with **Streamlit**. The model predicts the most likely next word based on the input sentence entered by the user.

---

## 📌 Project Overview

This project uses a Long Short-Term Memory (LSTM) neural network to learn language patterns from a text dataset and predict the next word in a sentence.

The application provides a simple and interactive web interface built with Streamlit where users can enter a sequence of words and receive the predicted next word instantly.

---

## 🚀 Features

- Text preprocessing and tokenization
- Sequence generation for training
- Padding of input sequences
- LSTM-based deep learning model
- Next word prediction
- Interactive Streamlit web application
- Easy-to-use interface

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pickle
- Streamlit

---

## 📂 Project Structure

```
next_word_prediction/
│
├── app.py                 # Streamlit application
├── model.keras            # Trained LSTM model
├── tokenizer.pkl          # Saved tokenizer
├── requirements.txt
├── README.md
└── dataset/
    └── quotes.txt
```

---

## ⚙️ Model Architecture

```
Input Layer
      │
Embedding Layer
      │
LSTM Layer
      │
Dense Layer (ReLU)
      │
Output Layer (Softmax)
```

The model is trained to predict the probability distribution of the next word using categorical cross-entropy loss.

---

## 📊 Workflow

1. Load text dataset.
2. Clean and preprocess text.
3. Tokenize the text.
4. Generate input sequences.
5. Apply sequence padding.
6. Train the LSTM model.
7. Save the trained model and tokenizer.
8. Load the model in Streamlit.
9. Predict the next word from user input.

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/next_word_prediction.git
```

Move into the project directory

```bash
cd next_word_prediction
```

Create virtual environment (Optional)

```bash
conda create -n tf_env python=3.11
conda activate tf_env
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit

```
http://localhost:8501
```

---

## 📥 Input

```
Artificial intelligence is
```

## 📤 Output

```
changing
```

*(Prediction depends on the trained dataset.)*

---

## 📈 Training

The model is trained using:

- Tokenizer
- Input sequence generation
- Padding
- Embedding layer
- LSTM
- Dense layers
- Adam optimizer
- Categorical Crossentropy Loss

---

## 📦 Requirements

```
tensorflow
streamlit
numpy
pickle-mixin
h5py
```

or install using

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

- Beam Search Prediction
- Top-K Word Prediction
- Transformer-based Language Model
- Better UI Design
- Deploy on Streamlit Cloud
- Larger training dataset

---

## 📸 Application Screenshot

Add a screenshot here after running the Streamlit app.

```
assets/app_screenshot.png
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is developed for educational purposes.

---

## 👩‍💻 Author

**Janhavi Wasade**

GitHub: https://github.com/yourusername
