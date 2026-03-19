# 🤖 Mini-BERT en PyTorch

## 📌 Description
Ce projet implémente une version simplifiée de BERT en PyTorch.

## 🎯 Objectif
- Pré-entraînement avec Masked Language Modeling (MLM)
- Fine-tuning pour classification (IMDB)
- Comparaison : pré-entraîné vs from scratch

## 📚 Datasets
- AG News → prétraining
- IMDB → classification

## 🧠 Modèle
- Transformer Encoder (Mini-BERT)
- Embeddings + positional encoding
- Tête MLM et classification

## ⚙️ Méthodes
- Masking 15%
- CrossEntropyLoss
- Fine-tuning supervisé

## 📊 Résultats
Le modèle pré-entraîné permet d’améliorer les performances par rapport à un modèle entraîné from scratch.

## 🛠️ Technologies
- PyTorch
- HuggingFace (tokenizer)
- NumPy / Matplotlib

## 📂 Notebook
Voir : RN_Souheb_Omar_Osman(1)(2).ipy.ipynb
