# ✍️ Next Word Prediction using LSTM 

This is a **Next Word Prediction** web app built with **TensorFlow (LSTM)** and **Streamlit**.  
The model is trained on *Shakespeare's Hamlet* text to predict the next word based on the given input sequence.

---

## 🚀 Features

- Predicts the next word from Shakespearean text.
- Uses **LSTM** for sequential word prediction.
- Clean, interactive **Streamlit** UI.
- Pre-trained on *Hamlet* for stylistic predictions.

---

## 🛠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **NumPy**
- **Pandas**
- **NLTK**
- **Scikit-learn**

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aditya-Tyagi-05/next-word-prediction-lstm.git
   cd next-word-prediction-lstm
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure model and tokenizer files exist**:
   ```
   next_word_lstm.h5
   tokenizer.pkl
   ```

4. **Run the app**:
   ```bash
   streamlit run app.py
   ```

---

## 📁 Project Structure

```
├── app.py                # Main Streamlit app
├── next_word_lstm.h5     # Pre-trained LSTM model
├── tokenizer.pkl         # Tokenizer for text sequences
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

---

## 💡 How It Works

1. Input a sequence of words.
2. The app tokenizes and pads the sequence to match the training input size.
3. The LSTM model predicts the most probable next word.
4. The prediction is displayed to the user.

---

## 📜 Requirements

```
streamlit
numpy
tensorflow==2.16.2
nltk
pandas
scikit-learn
```

---

## 📥 NLTK Data Download

The app uses the **NLTK Gutenberg corpus**. If running for the first time, ensure it is downloaded automatically by adding this snippet to your code:

```python
import nltk
nltk.download('gutenberg')
```

---

## ✨ Example

**Input:**
```
To be or not
```

**Predicted Next Word:**
```
to
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to modify.

---

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)
