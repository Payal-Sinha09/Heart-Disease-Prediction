# Heart Disease Prediction System

## Description
This project is a heart disease prediction system that uses various classification models to predict the likelihood of heart disease based on a dataset of 779 individuals. Models included are Logistic Regression, Random Forest, SVM, Naive Bayes, Decision Tree, LightGBM, and XGBoost.

## Getting Started

### Prerequisites
- Python 3.11
- Required libraries listed in `requirements.txt`

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/heart-disease-prediction.git
    ```
2. Navigate to the project directory:
    ```sh
    cd heart-disease-prediction
    ```
3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```
### Project Screenshots
![Variation of Age for each target class](https://github.com/Payal-Sinha09/Heart-Disease-Prediction/blob/master/image/Screenshot%20(163).png)
<br><br>
![Variation of Age for each target class](https://github.com/Payal-Sinha09/Heart-Disease-Prediction/blob/master/image/Screenshot%20(164).png)
<br><br>
![Subplot Configuration Tool](https://github.com/Payal-Sinha09/Heart-Disease-Prediction/blob/master/image/Screenshot%20(165).png)
<br><br>
![Distrubution of Age vs. Sex with the target class](https://github.com/Payal-Sinha09/Heart-Disease-Prediction/blob/master/image/Screenshot%20(166).png)
<br><br>
![Accuracy of training set](https://github.com/Payal-Sinha09/Heart-Disease-Prediction/blob/master/image/Screenshot%202024-10-01%20185236.png)
<br><br>
### Usage
1. Place your dataset in the `data/` directory.
2. Run the main script to execute the models:
    ```sh
    python main.py
    ```
3. You can also run individual models by executing their respective scripts in the `models/` directory.

### Project Structure
- `data/`: Contains the dataset used for training and testing.
- `models/`: Contains scripts for each classification model.
- `notebooks/`: Contains Jupyter notebooks for exploratory data analysis.
- `requirements.txt`: Lists the required Python libraries.
- `README.md`: This file.

### Contributing
Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.

### License
[MIT License](LICENSE)
