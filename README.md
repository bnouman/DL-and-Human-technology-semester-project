# 📘 DL and Human Technology Semester Project

![Python](https://img.shields.io/badge/python-3.8%2B-blue)

**Deep Learning and Human Technology Semester Project**
This repository contains the code and results for the semester project completed as part of the **Deep Learning and Human Technology** course.

---

## 🧠 Project Overview

This project explores the application of **modern language models** in analyzing and processing textual data. I experiment with both **small and large transformer-based models** to evaluate performance in language understanding tasks. The project employs **`simple-prompt`** and **`few-shot`** techniques to maximize the performance of the models.

The models implemented include:

* **SmolLM-135M**
* **SmolLM-360M**
* **BERT**
* **DistilBERT**
* **TurkuNLP/finnish-modernbert-large**

---

## 📁 Repository Structure

```
├── DLT_course_project_2025.ipynb    # Main project notebook
├── dlt_course_project_2025.py       # Python script version of the project
└── README.md                        # Project documentation (this file)
```

---

## 📌 Features

✔ Implementation of multiple transformer-based models.
✔ Use of `simple-prompt` and `few-shot` learning techniques.
✔ Data preprocessing and analysis for textual tasks.
✔ Model training, evaluation, and comparison.
✔ Documentation of results and observations.

---

## 📊 Results

Accuracies of the models are:

> * SmolLM-135M achieved 67.82% accuracy on the test set.
> * DistilBERT performed efficiently after fine-tuning the hyperparameters with smaller memory footprint.
> * SmolLM-360M achieved the best performance.
> * Finnish-modernbert-large model was also tested and it achieved 87.62% accuracy with recall of 86.49%.


---

## 🛠 Installation

Make sure you have **Python 3.8+** and install dependencies:

```bash
git clone https://github.com/bnouman/DL-and-Human-technology-semester-project.git
cd DL-and-Human-technology-semester-project
pip install -r requirements.txt
```


---

## ▶ How to Run

### 🐍 Run the Notebook

1. Open `DLT_course_project_2025.ipynb` in Jupyter Notebook or JupyterLab.
2. Run each cell to reproduce analyses, training, and evaluation.

### 🗂 Run the Script

```bash
python dlt_course_project_2025.py
```

---

## 📦 Dependencies

| Library                  | Purpose                        |
| ------------------------ | ------------------------------ |
| `transformers`           | Transformer-based models       |
| `torch`                  | Deep learning framework        |
| `numpy`                  | Numerical computations         |
| `pandas`                 | Data loading and preprocessing |
| `scikit-learn`           | Metrics and evaluation         |


---

## 🧪 Dataset


> The project uses `rotten-tomatoes` dataset, with 80% goes for training and 10% each for testing and validation.

---

## 👥 Contributor

* **Nouman Bashir** — Project author
  📧 [noumanbashir923@gmail.com](mailto:noumanbashir923@gmail.com)
