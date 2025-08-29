1. Project Title and Description
# SpaceX Falcon 9 First Stage Landing Prediction
This project builds and evaluates multiple classification models to predict whether the first stage of a SpaceX Falcon 9 rocket will successfully land. It uses real launch data and applies machine learning techniques including logistic regression, SVM, KNN, and decision trees.

2. Objectives
## Objectives
- Preprocess and engineer features from SpaceX launch data
- Train and tune multiple classification models
- Evaluate model performance using accuracy and confusion matrices
- Select the best-performing model for deployment

3. Technologies Used
## Technologies
- Python 3.11
- Pandas, NumPy
- Scikit-learn (Logistic Regression, SVM, KNN, Decision Tree)
- Matplotlib, Seaborn (for visualization)

4. Model Summary
## Model Comparison
| Model               | Test Accuracy | False Positives | False Negatives |
|--------------------|---------------|-----------------|-----------------|
| Logistic Regression| 83.3%         | 3               | 0               |
| SVM                | 83.3%         | 3               | 0               |
| KNN                | 83.3%         | 3               | 0               |
| Decision Tree      | 61.1%         | 4               | 3               |
Final Selection: Logistic Regression, SVM, or KNN — all showed strong generalization and zero false negatives.

5. Confusion Matrix Insights
Include a brief explanation and optionally embed your matrix image:
## Confusion Matrix Insights
- True Positives: All actual landings were correctly predicted
- False Positives: 3 cases misclassified as "landed"
- No False Negatives: Model never missed a successful landing

6. Installation Instructions
## Installation
1. Clone the repository:https://github.com/abraham9486937737/spacex-landing-prediction
2. Install dependencies:  pip install pandas scikit-learn matplotlib seaborn
3. Run the notebook:
Open `SpaceX_Landing_Prediction.ipynb` in Jupyter or VS Code

7. Author and Acknowledgments
## 👤 Author

**Abraham Ponnuraj**  
Data Analytics & Data Science Graduate  
[LinkedIn Profile](www.linkedin.com/in/abraham-ponnuraj-b717a111)

## 🙏 Acknowledgments

Thanks to IBM and KGiSL Microcollege for the capstone opportunity.


