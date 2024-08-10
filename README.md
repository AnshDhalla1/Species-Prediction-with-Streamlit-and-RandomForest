# Species-Prediction-with-Streamlit-and-RandomForest

## Description
This project is a web-based application built with Streamlit to predict the species of an iris flower based on its sepal and petal dimensions. The prediction model is based on the 'RandomForestClassifier' from scikit-learn, using the classic Iris dataset.

## Dataset Overview
The Iris dataset is a well-known dataset in the field of machine learning. It contains 150 samples of iris flowers, with 50 samples each from three species: Iris setosa, Iris versicolor, and Iris virginica. Each sample has four features: sepal length, sepal width, petal length, and petal width.

## Installation
1. First, clone the repository to your local machine using git
```bash
git clone https://github.com/AnshDhalla1/Species-Prediction-with-Streamlit-and-RandomForest
cd Species-Prediction-with-Streamlit-and-RandomForest
```
2. Create a new virtual environment:
```bash
python -m venv myenv  
```

3. Activate the virtual environment:
```bash
source myenv/bin/activate 
```

4. Install the required dependencies:
```bash
pip install -r requirements.txt
```

5. Run the Model:
```bash
streamlit run classifier.py
```

## Workflow

1. **Data Loading:** The Iris dataset is loaded and cached using st.cache_data to improve performance. 
2. **Model Training:** A RandomForestClassifier is trained on the Iris dataset to classify iris species.
3. **User Input:** The user inputs sepal and petal dimensions through a sidebar slider interface.
4. **Prediction:** The trained model predicts the species based on the user's input, displaying the result in the app.


<img width="1440" alt="Screenshot 2024-08-09 at 3 06 31 PM" src="https://github.com/user-attachments/assets/2c2047b9-5ac1-42b7-a40b-f9420927359e">
<img width="1440" alt="Screenshot 2024-08-09 at 3 06 49 PM" src="https://github.com/user-attachments/assets/27475cfd-8190-4012-8b53-ab21a577ea35">
