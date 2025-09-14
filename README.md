# Support_vector_machine
 
## SVM Assignment Readme

### Problem 1: Forestfire Size Categorization using SVM

In this assignment, we aim to classify the size category of forest fires using Support Vector Machines (SVM). We'll utilize a dataset named "Forestfire" containing various features related to forest fire occurrences.

### Dataset Features:

- **month**: Month of the year (`'jan'` to `'dec'`)
- **day**: Day of the week (`'mon'` to `'sun'`)
- **FFMC**: FFMC index from the FWI system (18.7 to 96.20)
- **DMC**: DMC index from the FWI system (1.1 to 291.3)
- **DC**: DC index from the FWI system (7.9 to 860.6)
- **ISI**: ISI index from the FWI system (0.0 to 56.10)
- **temp**: Temperature in Celsius degrees (2.2 to 33.30)
- **RH**: Relative humidity in % (15.0 to 100)
- **wind**: Wind speed in km/h (0.40 to 9.40)
- **rain**: Outside rain in mm/m2 (0.0 to 6.4)
- **Size_Categorie**: The burned area of the forest (`Small`, `Large`)

### Steps Covered:

1. **Importing Necessary Libraries**: Importing essential Python libraries for data analysis and visualization.
2. **Import Dataset**: Uploading and loading the Forestfire dataset.
3. **Data Understanding**: Exploring the dataset's shape, columns, and basic information.
4. **EDA (Exploratory Data Analysis)**:
   - Visualizing the distribution of the target variable (`Size_Categorie`).
   - Analyzing the number of fires in each month and day.
   - Examining rainfall levels and their relation to forest size categories.
   - Visualizing other features with the target variable.
5. **Label Encoder**: Encoding the target variable to numerical values.
6. **Outliers Detection**: Identifying outliers in continuous variables using boxplots and attempting treatments through log and square root transformations.

### Conclusion:

The analysis provides insights into the distribution and relationships of various features with forest fire size categories. SVM will be utilized for classification after preprocessing and outlier treatment steps.

For detailed code implementation and analysis, please refer to the `SVM_Assignment.ipynb` notebook provided in this repository.
