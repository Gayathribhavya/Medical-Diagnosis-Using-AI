# Medical Diagnosis using AI and ML

This is a web-based disease prediction application built using **Streamlit** and **Machine Learning**. The app predicts diseases based on user-provided symptoms.

## Features
- User-friendly **Streamlit** interface
- Predicts diseases using trained ML models
- Supports multiple symptom inputs
- Provides probabilistic predictions

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Gayathribhavya/Medical-Diagnosis-Using-AI.git
   cd Medical-Diagnosis-Using-AI
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the Streamlit app using the following command:
```bash
streamlit run app.py
```

## Dataset & Model
- The model is trained on a dataset of symptoms and diseases.
- Uses **classification algorithms** like Decision Trees, Random Forest, or Neural Networks.
- The trained model is saved as `model.pkl`.

## File Structure
```
├── app.py                # Main Streamlit app
├── models/               # Trained ML model
├── requirements.txt      # Dependencies
├── README.md             # Project documentation
├── dataset/              # Dataset 
```


## License
This project is licensed under the MIT License.

---


