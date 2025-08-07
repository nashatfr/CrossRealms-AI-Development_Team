# BlockShield Intrusion Detection System (IDS) — 5G Network Security

This repository showcases the development of an AI-driven intrusion detection system designed specifically for securing 5G networks. The project uses the publicly available 5G-NIDD dataset to train machine learning models that identify and classify a variety of network-based cyberattacks, including Denial-of-Service (DoS) and scanning attacks, alongside benign traffic.

## Project Highlights

- Developed baseline ML models using advanced feature reduction techniques — Principal Component Analysis (PCA) and Genetic Algorithm-based feature selection — to improve detection accuracy and efficiency.
- Utilized powerful classifiers such as XGBoost and Random Forest to achieve high accuracy (above 98%) in multi-class attack classification.
- Applied rigorous model evaluation with confusion matrices and cross-validation to ensure robustness and reliability.
- Focused on practical applications in next-generation 5G environments, aiming to support real-time intrusion detection and proactive network defense.

## Files

- `IDS PCA 5G-NIDD.ipynb` — PCA feature reduction and model training workflow  
- `IDS model - 5G-NIDD.ipynb` — Genetic Algorithm feature selection and model training  
- `Initial ML-Based Intrusion Detection Using the 5G-NIDD Dataset - report.pdf` — Comprehensive project report covering methodology, results, and analysis  

## Conclusion

The project successfully demonstrates that machine learning models trained on carefully selected features from the 5G-NIDD dataset can accurately classify multiple types of cyberattacks with high precision. Both PCA and Genetic Algorithm feature selection methods proved effective, with XGBoost and Random Forest classifiers delivering strong performance. This system lays the groundwork for real-time intrusion detection tailored to 5G networks.

## Future Work

- Implement hyperparameter tuning to further optimize model performance  
- Explore deep learning models (e.g., LSTM, transformers) to capture temporal patterns in network traffic  
- Develop a secondary model to identify specific attack tools for enhanced threat analysis  
- Integrate real-time data streaming and deployment pipelines for live network monitoring  

---

For detailed insights and complete documentation, please refer to the included project report.
