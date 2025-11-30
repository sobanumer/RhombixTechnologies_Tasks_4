# RhombixTechnologies_Tasks_4

A house price prediction project using machine learning (Linear Regression) trained on the **California Housing dataset**.

## 📌 Task 4: House Price Prediction

### 🎯 Goal

Build a machine learning model to **predict house prices** based on features like median income, house age, rooms, and location.

### 📊 Dataset

* **California Housing dataset** from `sklearn.datasets`.
* Features include:

  * `MedInc` (Median income)
  * `HouseAge`
  * `AveRooms` (Average rooms per household)
  * `AveBedrms` (Average bedrooms per household)
  * `Population`
  * `AveOccup` (Average occupancy)
  * `Latitude`
  * `Longitude`
* Target variable: `MedHouseValue` (Median house value).

### 🛠 Method

* **Data preprocessing**:

  * Feature scaling using **StandardScaler**
* **Model training**:

  * **Linear Regression** to predict house prices.
* **Evaluation**:

  * **Mean Squared Error (MSE)**
  * **R² Score**
* **Prediction function**:

  * Custom function allows prediction of house price given a dictionary of feature values.

### ✅ Results

* Model evaluation:

  * **Mean Squared Error:** ~`0.56`
  * **R² Score:** ~`0.58`
    Output:
    `Predicted House Price: $439345.69`

### 💻 Technologies Used

* Python
* scikit-learn
* NumPy
* Pandas
* Matplotlib
* Seaborn

