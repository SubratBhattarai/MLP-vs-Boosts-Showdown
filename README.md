# MLP vs Boost Showdown 🥊

An experimental benchmark exploring whether neural networks equipped with **Entity Embeddings** can challenge the long-standing supremacy of **Gradient Boosted Decision Trees (XGBoost & LightGBM)** on a showdown.

---

## 🚀 Key Features

* **Entity Embeddings:** Maps high-cardinality categorical variables into dense continuous vector spaces to capture latent semantic relationships.
* **Regularized MLP Architecture:** Combines Batch Normalization, Dropout, and the AdamW optimizer to prevent overfitting on tabular data.
* **Rigorous Training Loop:** Implements Binary Cross-Entropy with Logits, patience-based **Early Stopping**, and model checkpointing.
* **Head-to-Head Benchmarking:** Directly compares MLP performance against **XGBoost** and **LightGBM** using AUC-ROC metrics.

---

## 📊 Project Structure

```text
"Parent_directory"/
├── main.ipynb/             
├── best_model.pth/            
├── README/             
