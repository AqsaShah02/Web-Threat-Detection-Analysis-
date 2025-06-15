# Cybersecurity: Suspicious Web Threat Interactions 

## Project Overview
This project focuses on detecting and analyzing suspicious web traffic patterns to identify potential cybersecurity threats. Using machine learning techniques, we analyze AWS CloudWatch web traffic data to classify normal vs. suspicious activities and visualize threat patterns.

## Project Structure
```
UML_CYBER_THREAT_ANALYSIS/
├── data/
│   └── CloudWatch_Traffic_Web_Attack.csv       # Raw dataset
├── images/                                     # Visualization exports
│   ├── 1.jpg                                  # EDA visualizations
│   ├── 2.jpg                                  # Model performance charts
│   ├── 3.jpg                                  # Network graphs
│   ├── 4.jpg                                  # Correlation matrices
│   ├── 5.jpg                                  # Traffic over time
│   └── 6.jpg                                  # Anomaly detection results
├── model/
│   ├── network_intrusion_model.h5             # Neural network model
│   ├── neural_network_model.h5                # Alternative NN model
│   └── random_forest_model.pkl                # Random Forest model
├── results/
│   └── analyzed_data.csv                      # Processed/analyzed data
├── requirements.txt                           # Python dependencies
└── UML_Cyber_Threat_Analysis.ipynb           # Main Jupyter notebook
```

## Key Features
- **Data Analysis**: Exploratory analysis of web traffic patterns
- **Anomaly Detection**: Identification of suspicious activities using Isolation Forest
- **Machine Learning Models**:
  - Random Forest Classifier
  - Neural Networks (including CNN architecture)
- **Visualizations**:
  - Network interaction graphs
  - Traffic pattern heatmaps
  - Time-series analysis
  - Country-based threat distribution

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cybersecurity-web-threat-detection.git
   ```
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter notebook `UML_Cyber_Threat_Analysis.ipynb`
2. The notebook includes:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Feature engineering
   - Model training and evaluation
   - Visualization generation

## Results
Our models achieved 100% accuracy in classifying suspicious web traffic (note: this may indicate data leakage in the sample dataset - further validation needed with larger, more diverse datasets).

Key findings:
- High bytes_in with low bytes_out often indicates infiltration attempts
- Specific country codes showed higher frequency of suspicious activities
- Non-standard ports were frequently associated with unauthorized access attempts

## Visualizations
![6](https://github.com/user-attachments/assets/a8df3d29-ec70-46bb-b199-f80fcc2939e1)
![5](https://github.com/user-attachments/assets/2b458afe-7762-48cf-86cb-d846721d0a5c)
![4](https://github.com/user-attachments/assets/2cdbe2ff-b5e0-49ec-adf2-7f0742f4d59a)
![3](https://github.com/user-attachments/assets/79b748db-6250-4e64-9a2f-1a0e0ab2f319)
![2](https://github.com/user-attachments/assets/6246115e-5013-426e-ba91-4b38b02f61f9)
![1](https://github.com/user-attachments/assets/a066e54f-45d5-4f45-aa18-e9f72e200de8)


## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License
This project is licensed under the MIT License.
