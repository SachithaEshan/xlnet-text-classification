# XLNet Text Classification

This project implements a transformer-based text classification system using **XLNet** and **Hugging Face Transformers**.  
The model is fine-tuned to classify text into emotional categories such as **anger, fear, joy, and sadness**.

---

## 🚀 Features
- Text preprocessing and cleaning
- Tokenization using XLNet tokenizer
- Transformer-based text classification
- Model training and evaluation
- Inference using Hugging Face pipeline
- Implemented in Jupyter Notebook

---

## 🧠 Model
- **Architecture:** XLNet (`xlnet-base-cased`)
- **Task:** Multi-class text classification
- **Framework:** PyTorch + Hugging Face Transformers

---

## 📊 Dataset
The dataset is **not included** in this repository.


### 📁 Expected File Structure

- emotions_data/
  - emotion-labels-train.csv  
  - emotion-labels-test.csv  
  - emotion-labels-val.csv  



Each file should contain:
- `text` – input text
- `label` – emotion label

---

## 🛠️ Installation

```bash
pip install transformers datasets evaluate torch clean-text pandas scikit-learn
```
## How to Run

1. Clone the repository
2. Place the dataset inside the emotions_data/ folder
3. Open the notebook:
      jupyter notebook
   
4. Run all cells in order

## 📈 Results

- Model trained for multiple epochs
- Evaluation performed using accuracy metric
- Predictions generated using inference pipeline

## 👨‍💻 Author
**Eshan Gamage**  
Computer Science Graduate | Aspiring AI Engineer | NLP & Machine Learning Enthusiast

