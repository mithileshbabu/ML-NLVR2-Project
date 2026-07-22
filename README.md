# ML-NLVR2-Project
# Natural Language Visual Reasoning using NLVR2

## Project Overview

This project focuses on Natural Language Visual Reasoning (NLVR2), where a model determines whether a natural language statement is true or false based on two images.

The project compares a traditional machine learning baseline with a state-of-the-art multimodal transformer model.

---

## Dataset

The original NLVR2 dataset files (`train.json` and `dev.json`) are **not included in this repository** because they exceed GitHub's file size limitations for web uploads.

The dataset can be downloaded from the following Google Drive folder:

**Google Drive Link:**  
https://drive.google.com/drive/folders/1i6G_r8gqHjGzbhcIT9sGCg1uLOW2HTBu?usp=sharing

After downloading:

1. Place `train.json` and `dev.json` inside the following folder in Google Drive:

```
MyDrive/
└── NLVR2_Project/
    ├── train.json
    └── dev.json
```

2. Open the notebook in Google Colab.
3. Run the **Mount Google Drive** cell.
4. Execute the remaining notebook cells.

The notebook is already configured to load the dataset directly from Google Drive.

- Dataset: NLVR2
- Task: Binary Classification (True / False)
- Input:
  - One sentence
  - Two images
- Output:
  - True (1)
  - False (0)

---
## GitHub Notebook Preview

GitHub may display **"Invalid Notebook"** when previewing `ML_Project_NLVR2.ipynb`.

This is a GitHub notebook rendering issue and **does not affect the notebook itself**.

The notebook opens and executes normally in:

- Google Colab
- Jupyter Notebook
- JupyterLab

---
## Models

### Baseline Model
- TF-IDF Vectorizer
- Logistic Regression

### Main Model
- ViLT (Vision-and-Language Transformer)
- Pretrained model from Hugging Face

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

---

## Technologies Used

- Python
- Google Colab
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Repository Contents

- `ML_Project_NLVR2.ipynb` – Complete notebook implementation.

---
