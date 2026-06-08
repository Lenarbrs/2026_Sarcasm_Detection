# Such An Easy Task: Detecting Sarcasm In Text

This repository contains the code and experiments developed for our study on sarcasm detection in English text. We compare a linear Logistic Regression baseline, a standard Multi-Layer Perceptron (MLP), and a novel Pivot-Based MLP designed to capture semantic shifts within a sentence.

The experiments are conducted on a unified corpus built from three publicly available datasets: Sarcasm Corpus V2, iSarcasmEval, and the Conversational Sarcasm Corpus (CSC). Texts are encoded using the `all-MiniLM-L6-v2` SentenceTransformer model and evaluated using accuracy, precision, recall, and F1-score.

Our results show that the proposed pivot-based architecture significantly underperforms compared to simpler baselines, while Logistic Regression achieves the best overall balance with the highest F1-score.

## Reproducibility

All experiments were performed with fixed random seeds and stratified cross-validation. Detailed methodological descriptions, hyperparameters, and significance tests are provided in the accompanying paper.

## Authors

* Éloïse Delerue
* Lucile Lapray
* Léna Rebours

Université PSL
