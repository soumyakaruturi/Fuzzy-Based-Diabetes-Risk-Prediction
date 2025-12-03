

## **Fuzzy Based Diabetes Risk Prediction**

This project implements a **Fuzzy Logic–based model** to predict the **risk level of diabetes** using key health parameters. Instead of using strict mathematical boundaries, fuzzy logic allows the system to make human-like decisions based on approximate reasoning.

The model is built using Python and includes fuzzification, rule evaluation, and defuzzification to output the final diabetes risk score.

---

## **📌 Features**

* Fuzzy logic–based prediction
* Supports fuzzification of medical parameters
* Rule-based inference system
* Generates diabetes risk score (Low / Medium / High)
* Fully implemented in Python
* Easy to modify and extend with new rules

---

## **🧪 Input Parameters Used**

Common parameters used in diabetes screening (may vary based on your notebook):

* Glucose Level
* BMI
* Age
* Insulin Level
* Blood Pressure

---

## **⚙️ Technologies Used**

* Python
* NumPy
* Skfuzzy (scikit-fuzzy)
* Jupyter Notebook

---

## **📁 Project Structure**

```
.
├── Fuzzy Based Diabetes Risk Prediction.ipynb
├── README.md
└── requirements.txt (optional)
```

---

## **🚀 How to Run**

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/fuzzy-diabetes-risk.git
   ```

2. Install dependencies

   ```bash
   pip install scikit-fuzzy numpy
   ```

3. Open the notebook

   ```bash
   jupyter notebook "Fuzzy Based Diabetes Risk Prediction.ipynb"
   ```

4. Run all cells to see the fuzzy inference system in action.

---

## **📊 Output**

The model predicts:

* **Low Risk**
* **Medium Risk**
* **High Risk**

based on the evaluated fuzzy rules and defuzzified result.

---

## **📌 Future Improvements**

* Integrate with a frontend UI
* Add more medical parameters
* Convert to a web API using Flask/FastAPI
* Hyper-tune membership functions


