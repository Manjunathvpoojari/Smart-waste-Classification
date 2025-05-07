# Smart-waste-Classification
Classifying the waste materials as recyclable or non recyclable through training the models like XGBoost , Random Forest and SVM

# Brief out

This project focuses on classifying types of waste using multiple machine learning algorithms, aiming to improve waste segregation systems using data-driven methods.

## 📌 Objective

To develop a machine learning model that classifies waste into different categories using features derived from the dataset.

## 🧠 Models Implemented

- XGBoost (`XGBClassifier`)
- Random Forest (`RandomForestClassifier`)
- Support Vector Machine (SVM) (`SVC`)

Each model was trained, evaluated, and compared based on accuracy and other performance metrics.

## 📊 Dataset

- The dataset includes labeled samples representing various types of waste.
- Data preprocessing steps include cleaning, encoding, and splitting into training and testing sets.
- Feature scaling is applied where needed.



## 🔧 Tools & Libraries Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Manjunathvpoojari/Smart-waste-classification.git
   cd smart-waste-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Waste_Classification_Project.ipynb
   ```

4. Execute the cells step-by-step to see preprocessing, training, and model evaluation.

## 📈 Results

- XGBoost achieved the highest accuracy among the tested models.
- Performance comparison includes accuracy, confusion matrices, and feature importance plots.

## 📚 Future Improvements

- Include deep learning models for enhanced image-based classification (e.g., CNNs).
- Deploy as a web application using Flask or Streamlit.
- Expand dataset to include more granular waste categories.

## 👨‍💻 Author

- **Manjunath V Poojari** – [https://github.com/Manjunathvpoojari]

## 📄 License

This project is licensed under the [MIT License](LICENSE).
