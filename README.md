# 🛡️ Cyber Threat Analysis & Detection

This project is a comprehensive cyber threat analysis pipeline. It analyzes network traffic data, applies machine learning models for anomaly and attack detection, and visualizes cyber threat patterns. The goal is to simulate a security monitoring scenario — like one for a university — using real or realistic data.

---

## 📌 Objectives

- Analyze cloud-based network traffic logs.
- Detect malicious activity using ML models.
- Visualize cyber threats and attack patterns.
- Interpret results with a focus on network intrusion analysis.
- Package results into a reproducible format with trained models.

---

## 🧰 Technologies & Tools

- **Platform:** Google Colab
- **Language:** Python
- **Libraries:**  
  - pandas  
  - matplotlib / seaborn  
  - scikit-learn  
  - tensorflow / keras  
  - numpy  

---

## 📂 Project Structure

```

UM\_Cyber\_Threat\_Analysis/
├── data/
│   └── CloudWatch\_Traffic\_Web\_Attacks.csv
├── images/
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ... (threat visualizations)
├── model/
│   ├── network\_intrusion\_model.h5
│   ├── neural\_network\_model.h5
│   └── random\_forest\_model.pkl
├── results/
│   └── analyzed\_data.csv
├── requirements.txt
└── UM\_Cyber\_Threat\_Analysis\_.ipynb

````

---

## 🚀 How to Run This Project

### 🔗 Option 1: Google Colab (Recommended)
1. Open the notebook directly in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

2. Upload all folders (`data`, `images`, `model`, `results`) via Colab’s file manager.
3. Run all cells step-by-step.

---

### 💻 Option 2: Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/UM_Cyber_Threat_Analysis.git
   cd UM_Cyber_Threat_Analysis
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:

   ```bash
   jupyter notebook UM_Cyber_Threat_Analysis_.ipynb
   ```

---

## 🧠 Models Used

| Model                | File Name                    | Type                       |
| -------------------- | ---------------------------- | -------------------------- |
| Neural Network       | `neural_network_model.h5`    | Deep Learning (Keras)      |
| Network Intrusion NN | `network_intrusion_model.h5` | Custom Intrusion Detection |
| Random Forest        | `random_forest_model.pkl`    | Scikit-learn ML            |

These models are pre-trained and used for classifying and detecting threats in network traffic data.

---

## 📊 Visual Results

Example visualizations are available in the `images/` folder:

![WhatsApp Image 2025-06-15 at 13 58 44_64bfb651](https://github.com/user-attachments/assets/dee6d27a-98c4-49a7-8c03-39f45266a0f0)


You can view them by opening the notebook and exploring the "Images" section.

---

## ✅ Results

The `results/analyzed_data.csv` file contains:

* Detected anomalies
* Probabilities or prediction results
* Feature-engineered outputs

---

## 📦 Dependencies

All dependencies are listed in `requirements.txt`. If you used Colab, most will already be pre-installed.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, create a branch, and open a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

* Google Colab for cloud-based computing
* University of Michigan (for scenario inspiration)
* Open-source Python and ML libraries
* CloudWatch (as a reference for sample data schema)

