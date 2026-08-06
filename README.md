# Fine-Tuning a Language Model using Hugging Face Transformers

## Objective

Fine-tune a pre-trained DistilBERT model on a custom sentiment dataset.

---

## Dataset

A small custom dataset containing positive and negative sentences.

Example:

| Text | Label |
|------|------|
| I love this product | Positive |
| Very bad experience | Negative |

---

## Transformer Model

- DistilBERT
- Model: distilbert-base-uncased

---

## Tasks Performed

- Data preprocessing
- Tokenization
- Fine-tuning
- Model testing
- Evaluation using Accuracy and F1-score

---

## Libraries Used

- Transformers
- Datasets
- PyTorch
- Scikit-learn

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

Open

```
Fine_Tuning_Language_Model.ipynb
```

Run all cells sequentially.

---

## Evaluation Metrics

The notebook prints:

- Accuracy
- F1 Score

---

## Sample Prediction

Input:

```
This product is really good
```

Output:

```
Positive
```

---

## Project Structure

```
Fine-Tuning-Language-Model/
│
├── Fine_Tuning_Language_Model.ipynb
├── README.md
├── requirements.txt
├── fine_tuned_model/
├── logs/
└── results/
```

---

## Author

Prince Tiwari
Prince8879 https://github.com/Prince8879/Fine-Tuning-Transformer-Model


