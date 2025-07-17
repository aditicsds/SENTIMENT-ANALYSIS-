# Sentiment Analysis on Amazon Product Review :

A machine learning-based project that analyzes Amazon product reviews and classifies them as Positive, Negative, or Neutral using Natural Language Processing (NLP) techniques. This project helps customers make better purchase decisions and enables sellers to improve their products based on real feedback.

---

## Table of Contents

* Overview
* Objectives
* Features
* Tech Stack
* System Architecture
* Installation
* Usage
* Design Diagrams
* Project Team
* License

---

## Overview

Millions of reviews are posted daily on Amazon. It becomes difficult for customers to make confident choices due to mixed or overwhelming feedback. This project uses NLP and supervised machine learning to classify these reviews automatically into three sentiment categories:

* Positive
* Negative
* Neutral

---

## Objectives

* Extract opinions from text reviews.
* Detect sentiment polarity and strength.
* Provide quick sentiment feedback.
* Assist buyers and sellers in decision-making.

---

## Features

* Classifies user reviews as Positive, Negative, or Neutral.
* Cleans text using NLP preprocessing (stop words, tokenization, stemming).
* Trains a supervised ML model on labeled data.
* Shows real-time and batch processing.
* Scalable and easy to integrate.

---

## Tech Stack

| Category      | Tools                      |
| ------------- | -------------------------- |
| Programming   | Python                     |
| Libraries     | NLTK, scikit-learn, Pandas |
| IDE           | Jupyter Notebook / VS Code |
| Visualization | Matplotlib / Seaborn       |
| Diagramming   | ConceptDraw, Draw\.io      |

---

## System Architecture

```text
User Review Input -> Preprocessing -> Feature Extraction -> ML Model -> Sentiment Output
```

* Input: Raw Amazon review text
* Processing: NLP cleaning and classification
* Output: Sentiment label (Positive, Negative, Neutral)

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/sentiment-analysis-amazon.git
cd sentiment-analysis-amazon
```

2. (Optional) Create virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

You can run the sentiment analysis using:

```bash
python sentiment_analysis.py
```

Or open the Jupyter Notebook:

```bash
jupyter notebook Sentiment_Analysis.ipynb
```

Upload a .csv file of reviews or input custom review text.

---

## Design Diagrams

* 0-Level DFD: Shows review input, model processing, and sentiment output.
* 1-Level DFD: Includes steps like reading, preprocessing, and classification.
* Use Case Diagram: Shows how users interact with the system.
* Sequence Diagram: Timeline view of operations between modules.

---

## Software Attributes

* Accuracy: Classifies reviews with high precision.
* Performance: Fast processing for large datasets.
* Adaptability: Trained on various Amazon product domains.
* Explainability: Shows reason for each classification.
* Security: Keeps review data private and safe.

---

## Project Team

| Name          | Role                          |
| ------------- | ----------------------------- |
| Aditi Tiwari  | Coding, Design, Testing       |
| Aanya Singhai | Design, Requirement Gathering |
| Anshika Gupta | Coding, Testing               |
| Jagrati Yadav | Requirement Gathering         |

---

## License

This project was created for academic purposes. Contact the contributors for reuse or collaboration.

---
