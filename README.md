# Personalized Healthcare Recommendation System 💊🩺

This is a Machine Learning-powered system designed to recommend medicines and treatments based on patient symptoms and history. It aims to improve diagnostic support and reduce human error in initial prescriptions.

## 🚀 Features
- Symptom input and disease prediction
- Medicine recommendation based on predicted disease
- User-friendly interface
- Trained on public datasets
- Uses multiple ML models for better accuracy

## 🛠️ Tech Stack
- Python
- Pandas, NumPy, Scikit-learn
- Streamlit (optional for UI)
- Git, GitHub

## 📂 Project Structure
<details>
<summary>📁 Click to view folder structure</summary>
```text
📁 Personalized-Healthcare-RS/
├── 📁 data/                      # All datasets go here (CSV, JSON, etc.)
│   └── symptoms_disease.csv
│
├── 📁 models/                    # Trained models or model-saving code
│   ├── decision_tree.pkl
│   └── model_trainer.py         # Script to train & save models
│
├── 📁 utils/                     # Helper functions (e.g., preprocessing, utils)
│   └── preprocessing.py
│
├── 📁 notebooks/                # Jupyter notebooks for exploration or prototyping
│   └── EDA.ipynb
│
├── 📁 app/                      # Streamlit or Flask app
│   ├── app.py                   # Main app file
│   └── layout.py                # (Optional) for UI layout separately
│
├── 📁 tests/                    # Test scripts (unit tests, integration tests)
│   └── test_prediction.py
│
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
├── .gitignore                   # Files/folders Git should ignore
└── LICENSE                      # License file (e.g., MIT)

</details>
```
## 🔍 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Prasannakrish12/Personalized-Healthcare-Recommendation-System.git

2.	Install dependencies:

   pip install -r requirements.txt
3.	Run the app:
   python app.py
🤖 Algorithms Used
	•	Decision Tree
	•	Random Forest
	•	Naive Bayes
	•	Support Vector Machine (SVM)

📈 Future Improvements
	•	Add deep learning for better accuracy
	•	Build full-fledged UI
	•	Integrate user feedback loop

📬 Contact

Made with ❤️ by [Prasanna Krish](https://github.com/Prasannakrish12)

Feel free to fork, improve, or suggest features!

