# Crime_Data_from_2020_to_Present
A comprehensive analysis and machine learning model for crime type prediction using the Crime Data from 2020 to Present dataset.
---

# Crime Data from 2020 to Present

This repository provides a comprehensive analysis and machine learning model for predicting crime types using the "Crime Data from 2020 to Present" dataset. The project leverages data preprocessing, exploratory data analysis (EDA), feature engineering, and model training to classify crimes with high accuracy.

## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset, **Crime Data from 2020 to Present**, includes detailed records of crime incidents. Key fields include:
- **Date** and **Time** of occurrence
- **Crime Type** and **Description**
- **Location** coordinates (latitude and longitude)
- **Victim** demographic information (age, sex, descent)
  
Note: Ensure that the dataset path aligns with the code before running analyses.

## Project Structure
```
├── data/                    # Folder containing the dataset files
├── notebooks/               # Jupyter notebooks for EDA and model training
├── src/                     # Source code for data preprocessing and modeling
├── README.md                # Project README
└── requirements.txt         # Dependencies
```

## Installation
1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/Crime_Data_from_2020_to_Present.git
   cd Crime_Data_from_2020_to_Present
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- **Data Preprocessing**: Run the preprocessing steps to clean the dataset by handling missing values and filtering out outliers.
- **Exploratory Data Analysis (EDA)**: Execute EDA to identify patterns in the data, such as temporal and geographic distributions of crime.
- **Model Training**: Train the model using SMOTE for class balancing and a Random Forest classifier for crime type prediction.
- **Evaluation**: Evaluate model performance using accuracy, precision, recall, and F1-score.

Run the Jupyter notebook or Python script as follows:
```bash
jupyter notebook notebooks/crime_analysis.ipynb
```

## Methodology
1. **Data Cleaning**: Addressed missing values and outliers in key fields.
2. **Feature Engineering**: Created meaningful features based on location, time of day, and victim demographics.
3. **Oversampling with SMOTE**: Balanced the dataset for minority classes using SMOTE.
4. **Model Training**: Utilized a Random Forest classifier, achieving an accuracy of ~87% on test data.
5. **Evaluation**: Detailed classification report generated to assess model performance across crime types.

## Results
- **Model Accuracy**: Achieved 87% accuracy.
- **Classification Report**: Demonstrated strong precision, recall, and F1-scores for most crime categories, especially well-represented types.
- **Insights**: EDA provided key insights into crime trends and geographic hotspots.

## Future Improvements
- **Hyperparameter Tuning**: Further optimize the model using techniques like GridSearchCV.
- **Advanced Models**: Experiment with models like XGBoost for potentially better performance.
- **Interactive Visualization**: Add visualizations for deeper insights and trend exploration.

## Contributing
We welcome contributions! Please submit a pull request or open an issue to discuss any improvements or bug fixes.

## License
This project is licensed under the MIT License.

--- 

