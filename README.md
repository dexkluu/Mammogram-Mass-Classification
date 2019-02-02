# Note
A jupyter notebook showing the analysis can be seen [here](https://nbviewer.jupyter.org/github/dexkluu/Mammogram-Mass-Classification/blob/master/Mammogram%20Mass%20Classification.ipynb).

# Mammogram-Mass-Classification
This project deals with classifying masses found in mammogram results as benign or malignant. The data is from the UCI repository. One can find the basic info for the columns below:

BI-RADS: 1 to 5 (ordinal) rating on confidence of severity classification 
Age: (integer) 
Shape: round=1, oval=2, lobular=3, irregular=4 
Margin: circumscribed=1, microlobulated=2, obscured=3, ill-defined=4, spiculated=5 
Density: high=1, iso=2, low=3, fat-containing=4 
Severity: benign=0, malignant=1 

The goal of this project is to test different classification methods and find which works best for this problem. The models that will be used are random forest, KNN, Naive Bayes, and logistic regression. Finding a model that can accurately classify the masses could have a huge impact by reducing the amount of patients taking the wrong steps moving due to false positives and false negatives.

## Tools Used
The analysis was done using Python version 3.6.5 on a Jupyter Notebook. The libraries used were pandas, numpy, sklearn, and matplotlib.

## Results
The models had accuracies around 70 and 80 percent. The best performing model was the logistic regression one. Again, the analysis can be seen in the link in the notes section above.

## Replicate the analysis
To replicate my results, one could simply run the code in the Jupyter Notebook. The data is included in the repository but it can also be found from the UCI repository where it was originally found.

## Author(s)

* **Dexter Luu**
