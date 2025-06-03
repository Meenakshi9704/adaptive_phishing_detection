# adaptive_phishing_detection
# Adaptive Phishing Detection using Machine Learning and Ontology

This project presents an intelligent and adaptive phishing detection system that combines Machine Learning (ML) and Semantic Ontology to effectively detect phishing emails and URLs. It leverages Natural Language Processing (NLP), OWL-based ontologies, and classification models to enhance detection accuracy, adaptability, and explainability.

## 📌 Project Highlights

- Combines Machine Learning with Ontology reasoning for phishing detection  
- Uses NLP to analyze email/URL content  
- Employs OWL (Web Ontology Language) to define semantic relationships between phishing indicators  
- Offers explainable detection decisions via ontology inference  
- Adaptive to zero-day attacks and evolving phishing techniques  



## 🧠 Methodology

1. **Data Preprocessing**: Clean and extract lexical and semantic features from phishing emails and URLs.  
2. **Ontology Construction**: Define phishing concepts (e.g., `Suspicious_Link`, `Urgent_Request`) using OWL ontology.  
3. **ML Model Training**: Train classifiers like Random Forest or SVM on lexical features.  
4. **Ontology Reasoning**: Use OWL reasoning engines (e.g., HermiT, OWLAPI) to derive conclusions from semantic data.  
5. **Hybrid Detection**: Combine ontology-based reasoning and ML predictions to make robust decisions.  

## 🧪 Installation & Setup

### Prerequisites

- Python 3.8+  
- Java (for OWL reasoning if using OWLAPI/HermiT)  
- pip  

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python main.py
```

## 🔍 Sample Output

- Classifier Accuracy: 96.3%  
- False Positives reduced by 40% using ontology reasoning  
- Ontology explanations:  
  ```
  Reason: Email flagged due to presence of concept "Fake_Login_Page" linked to suspicious domain and urgent call to action.
  ```

## ⚙️ Technologies Used

- Python  
- Scikit-learn  
- spaCy / NLTK  
- OWL / RDFLib  
- Protégé (for building the ontology)  
- HermiT / OWLAPI (Java-based OWL reasoning)  

## 📚 Literature References

- Jain & Gupta (2020) – Visual similarity detection  
- Aburrous et al. (2009) – Fuzzy logic phishing model  
- Khonji et al. (2013) – Phishing detection taxonomy  
- Arkhipov & Al-Azzawi (2018) – Semantic detection via ontologies  

 

## 📄 License

This project is for academic purposes. All rights reserved by the authors.

## 🙌 Acknowledgements
  
- Protégé OWL Editor  
- Scikit-learn & RDFLib communities
