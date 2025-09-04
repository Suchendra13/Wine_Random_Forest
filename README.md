# Classification of Wine using Random Forest Classifier
  This *project* helps us to **classify** the type of wine based upon the `features` such as **color intensity, presence of magnesium, phenols**,etc.

# Contents
1. [Dataset](#dataset)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Scaling](#scaling)
4. [Evaluation](#evaluation)
5. [Libraries Used](#libraries-used)
6. [How to Run](#how-to-run)
7. [Acknowledgments](#acknowledgements)

## Dataset
 This project utilises the standard `load_wine` dataset to classify the target into **3 classes** - *class_0,class_1 and class_2* based upon it's features. This projects demonstrates the use of **Random Forest** to *classifiy* the *dataset*.We create a *dataframe* using `panda library` to create the **features matrix ( X )** and **target vector ( y )**.

## Exploratory Data Analysis
1. We have plotted a **histogram** of all the `wine features` which highlights about the *characteristics* of each feature!
2. Plotted a **boxplot** about the `alocohol content` of the respective *wine classes*.
3. There is also a `scatterplot` which depicts the **color intensity** of the alocohol.
4. Then, we dive into the **correlation matrix** of all the `features` in the *dataset*.
5. So, also we plotted a **scatterplot** of the __features__ including *alcohol*, *flavanoids*, *color_intensity*, *proline* and *wine class*.

## Scaling
 Then we used the **Standard Scaler** to scale down all the *features* in order to make our `dataset` look clean and easy to process and apply the model.

## Evaluation
 After applying the Random Forest Model we got,
 
 Accuracy of *Random Forest*: **1.0000**
 
*Classification Report* of `Decision Tree` :
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        12
           1       1.00      1.00      1.00        14
           2       1.00      1.00      1.00        10

   * accuracy                           1.00        36
    
  * macro avg       1.00      1.00      1.00        36
   
*weighted avg       1.00      1.00      1.00        36


## Libraries Used
    We used the python libraries which include numpy, matplotlib, pandas, seaborn and scikit-learn.

## How to Run
1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone [https://github.com/Suchendra13/Wine_Random_Forest.git](https://github.com/Suchendra13/Wine_Random_Forest.git)
    cd Wine_Random_Forest
    ```
2.  **Ensure you have Jupyter Notebook installed** or use a compatible IDE (e.g., VS Code with Jupyter extensions).
3.  **Install the required Python libraries**:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
4.  **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook Wine_Random_Forest.ipynb
    ```
5.  **Run all cells** in the notebook.
   
## Acknowledgements
 We have used the standard **scikit-learn library** i.e. `load_wine dataset` for the *educational purposes*.
