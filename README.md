# KNN-based Titanic Survival Prediction

This project applies a K-Nearest Neighbors (KNN) classifier to predict survival on the Titanic using the Titanic dataset. It involves preprocessing, feature engineering, hyperparameter tuning, and model evaluation with visualization.

## Features

- Data Preprocessing: Cleans data, handles missing values, and engineers new features.
- Feature Engineering: Adds `FamilySize`, `IsAlone`, and binned `Fare`/`Age` features.
- Hyperparameter Tuning: Uses `GridSearchCV` for optimal KNN model selection.
- Model Evaluation: Reports accuracy and displays a confusion matrix using Seaborn.
- Visualization: Heatmap of the confusion matrix for clear result interpretation.

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install them via pip if needed:

    pip install pandas numpy scikit-learn matplotlib seaborn

## Usage

1. Download the Titanic dataset (`titanic.csv`) and place it in the correct path (as set in the script).
2. Run the script:

        python KNN-Titanic.py

3. View the results:
    - Output will show preprocessing info, model accuracy, and the confusion matrix.
    - A heatmap of results will display graphically.

## Project Structure

    .
    ├── KNN-Titanic.py
    └── titanic.csv

## Customization

- To use a different dataset, adjust the file path in the script.
- Modify the feature engineering section to experiment with other features.

## License

This project is for educational purposes.

---

Made with ❤️ for Machine Learning practice!
