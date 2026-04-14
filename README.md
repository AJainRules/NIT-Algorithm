# 🧠 Neuro-Immune Transformer (NIT) for IoT Intrusion Detection

A novel hybrid deep learning framework combining **Artificial Immune Systems (AIS)** and **Transformer-based self-attention** for robust and adaptive intrusion detection in IoT/IoMT environments.

---

## 📌 Overview

The **Neuro-Immune Transformer (NIT)** is designed to address key limitations of existing intrusion detection systems:

* ❌ Deep learning models lack adaptability to zero-day attacks
* ❌ Bio-inspired models fail to capture sequential dependencies
* ❌ Transformers underperform on structured IoT traffic

✅ NIT solves this by **co-evolving immune-inspired anomaly detection with contextual self-attention**, enabling:

* Adaptive detection of novel attacks
* Context-aware traffic analysis
* Robust performance under noisy and adversarial conditions

---

## 🏗️ Architecture

NIT consists of three parallel pathways:

1. **🧬 Immune-Inspired Module**

   * Detector generation & evolution
   * Affinity matching
   * Clonal selection & mutation
   * Adaptive memory for zero-day detection

2. **🧠 Neural Memory Module**

   * Gated memory mechanism
   * Temporal pattern retention
   * Noise suppression

3. **🔗 Transformer Module**

   * Multi-head self-attention
   * Contextual feature learning
   * Long-range dependency modeling

➡️ Outputs are fused and passed to a classification head for final prediction.

---

## 📊 Key Results

| Metric                  | Value      |
| ----------------------- | ---------- |
| Accuracy                | **98.04%** |
| Recall (Detection Rate) | **92.91%** |
| F1-Score                | **0.9168** |
| False Alarm Rate        | **1.4%**   |
| ROC-AUC                 | **0.9875** |

✅ Outperforms AIS, LSTM, CNN, and Transformer-based baselines
✅ Strong performance on imbalanced datasets
✅ Robust to noise and adversarial attacks

---

## ⚡ Efficiency

* ⏱ Training Time: **12.4 sec/epoch**
* ⚡ Inference Latency: **3.2 ms/sample**
* 🧮 Model Size: **856K parameters**

✔ Suitable for **real-time IoT/edge deployment**

---

## 📂 Project Structure

```
NIT-IDS/
│
├── data/                  # Dataset (or download links)
├── models/                # Model architecture (NIT)
├── training/              # Training scripts
├── evaluation/            # Metrics, plots, analysis
├── utils/                 # Helper functions
├── results/               # Output results, figures
├── requirements.txt       # Dependencies
└── main.py                # Entry point
```

---

## 📥 Dataset

We use the **WUSTL EHMS 2020 IoMT dataset**:

🔗 https://www.cse.wustl.edu/~jain/ehms/index.html

* 35 network features
* 8 biometric features
* Includes MITM attacks
* Imbalanced real-world scenario

---

## ▶️ Usage

### Train Model

```bash
python main.py --mode train
```

### Evaluate Model

```bash
python main.py --mode evaluate
```

### Run Inference

```bash
python main.py --mode test
```

---

## 🧪 Experiments

The following evaluations are included:

* ✔ Comparative benchmarking (11 models)
* ✔ Ablation study
* ✔ ROC & PR curve analysis
* ✔ Confusion matrix
* ✔ Statistical significance (t-test, Cohen’s d)
* ✔ Robustness testing (Gaussian noise, FGSM attack)

---

## 🔬 Key Contributions

* 🚀 Novel **Neuro-Immune Transformer (NIT)** architecture
* 🔄 Co-evolution of AIS and Transformer modules
* 🧩 End-to-end hybrid learning (not sequential)
* 📉 Low false alarm rate with high recall
* ⚡ Lightweight and efficient for edge deployment

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a new branch
* Submit a pull request

---

## 📬 Contact

👤 **Apoorv Jain**
📧 [your-email@example.com](apoorvjain911@gmail.com)
🔗 LinkedIn: linkedin.com/in/asst-prof-apoorv-jain-17b86b114

---

## ⭐ Acknowledgements

* WUSTL EHMS Dataset
* PyTorch Community
* Research inspiration from AIS & Transformer literature

---

## 🚀 Future Work

* Model compression (edge deployment)
* Federated learning integration
* Explainable AI (XAI) for interpretability
* Cross-domain applications (finance, ICS security)

---

⭐ If you find this work useful, please consider giving it a star!
