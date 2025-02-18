# Lead Scoring Analysis using Logistic Regression

## Project Overview
This project aims to develop a lead scoring model using Logistic Regression to help X Education prioritize potential leads. The model assigns a score between 0 and 100 to each lead, indicating the likelihood of conversion. A higher score means the lead is more likely to convert, allowing the company to focus its efforts on high-potential customers.

## Dataset
The dataset contains information about leads acquired through various channels, including website visits, referrals, and marketing campaigns. It includes categorical and numerical features relevant to lead conversion.

## Project Workflow
1. **Data Preprocessing:**
   - Handle missing values by replacing 'Select' responses with NaN.
   - Drop columns with more than 50% missing data.
   - Fill missing categorical values with the mode.
   - Encode categorical variables appropriately.
   
2. **Feature Engineering:**
   - Select relevant features based on exploratory data analysis.
   - Apply scaling to numerical variables where necessary.

3. **Model Building:**
   - Implement Logistic Regression for lead scoring.
   - Split data into training and testing sets.
   - Train and optimize the model.

4. **Model Evaluation:**
   - Evaluate using metrics such as Accuracy, Confusion Matrix, ROC-AUC Score, and Classification Report.
   - Visualize results using correlation heatmaps and distribution plots.

## Installation & Dependencies
To run this project, install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lead-scoring-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd lead-scoring-analysis
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook LSA_Final.ipynb
   ```

## Results
- The Logistic Regression model provides insights into lead conversion probability.
- The ROC-AUC score helps measure model performance.
- The company can use the lead scores to optimize marketing efforts and increase conversion rates.


## Future Improvements
- Implement more advanced machine learning models (Random Forest, XGBoost, etc.)
- Perform hyperparameter tuning for better accuracy.
- Use additional features to improve prediction performance.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or bug fixes.

## License
This project is open-source under the MIT License.

