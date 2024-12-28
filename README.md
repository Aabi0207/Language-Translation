# 🌍 Language Translation Using Transformers

![Translation Model](https://heidloff.net/assets/img/2023/02/transformers.png)

## 🚀 Overview

This project focuses on **English-to-Hindi** and **English-to-Marathi** translation using **transformer-based neural networks**. Leveraging **PyTorch**, **HuggingFace Datasets**, and **Tokenizers**, it delivers high-performance translation models.

---

## 📦 Features

- 🌐 **Multilingual Support**: Translates between English, Hindi, and Marathi.
- ⚡ **State-of-the-Art Transformers**: Utilizes modern transformer architectures for high accuracy.
- 🛠 **Custom Tokenizers**: Built using WordPiece with special preprocessing techniques.
- 📊 **Dataset Integration**: Automatically loads and processes data from Opus100.
- 🔧 **Modular Design**: Includes `model.py` and `inference.py` for easy training and deployment.

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Aabi0207/Language-Translation.git
cd Language-Translation/Language-Translation-using-Transformers
```

2. **Set up the environment:**

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

---

## 📋 Usage

### 1. Train the Model

Run the training script to preprocess data and train the transformer model:

```bash
python model.py
```

### 2. Perform Inference

Use the trained model for translation tasks:

```bash
python inference.py --input "Hello, how are you?" --language hi
```

Example Output:
```
नमस्ते, आप कैसे हैं?
```

---

## 📊 Results

| Source Text                   | Hindi Translation          | Marathi Translation        |
|-------------------------------|-----------------------------|-----------------------------|
| *Hello, how are you?*         | *नमस्ते, आप कैसे हैं?*     | *नमस्कार, तुम्ही कसे आहात?*|
| *Good morning*                | *सुप्रभात*                  | *शुभ प्रभात*               |
| *Thank you very much*         | *आपका बहुत बहुत धन्यवाद*   | *तुमचे खूप खूप आभार*      |

---

## 📬 Contact

For feedback or suggestions, contact **Aabi** at [your.email@example.com](mailto:abhishekbiradar0207@gmail.com).

---

*Created with ❤️ by [Aabi0207](https://github.com/Aabi0207).*

