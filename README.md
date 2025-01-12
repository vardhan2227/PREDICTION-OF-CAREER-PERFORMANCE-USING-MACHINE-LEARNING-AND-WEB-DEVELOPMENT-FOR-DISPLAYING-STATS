# PREDICTION-OF-CAREER-PERFORMANCE-USING-MACHINE-LEARNING-AND-WEB-DEVELOPMENT-FOR-DISPLAYING-STATS

This project utilizes machine learning to analyze cricket captaincy performance based on historical ODI data. It includes preprocessing, model evaluation, and insightful visualizations to identify key trends and the most successful captains.

### Features
🏏 Data Preprocessing
Extracted decade information from captaincy years to analyze trends over time.
Performed KNN imputation to handle missing values for critical features like matches played, won, lost, and tied.

### 🤖 Machine Learning Models
Trained and compared three models:
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
Evaluated models based on:
Accuracy: Correct predictions.
Precision: Relevant predictions.
### 📊 Visualizations

### Model Performance:
Bar charts showing accuracy and precision scores for each model.

### Top Captains:
Filtered captains with at least 50 matches played.
Ranked captains by Win% to highlight top performers.
### Captaincy Trends:
Bar charts visualizing Win% for captains with over 50 matches.

### Key Insights
Identification of the most successful captains based on Win%.
Analysis of decade-based captaincy trends.
Comparative model performance to predict cricket outcomes effectively.

### Sample Output
Best Captain:
Displays the name and Win% of the best-performing captain with over 50 matches played.

Model Performance:
Bar charts comparing accuracy and precision of Logistic Regression, Random Forest, and SVM.

### Future Enhancements
Integrate real-time cricket data using APIs (e.g., ESPNcricinfo).
Expand analysis to Test and T20 formats.
Develop an interactive web app using Streamlit or Flask.
