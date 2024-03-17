<h1 align="center">Wine Quality Prediction</h1>


<p align="center">
  <img src="https://images.unsplash.com/photo-1589972103237-4bafe369ec3b?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Description of your image" width="500" height="300">
</p>

<h2 align="center">Problem Statement</h2>
<p align="center">
  <b><i>Using physicochemical properties to determine quality of wine</i></b>
</p>



## Dependencies

- numpy: Fundamental package for scientific computing with Python.
- pandas: Data manipulation and analysis library.
- scikit-learn: Machine learning library for building predictive models.
  - RandomForestClassifier: Ensemble learning method for classification.
  - train_test_split: Function for splitting data into train and test sets.
  - accuracy_score: Function for calculating the accuracy of model predictions.
- seaborn: Statistical data visualization library based on matplotlib.
- matplotlib: Comprehensive plotting library for creating static, interactive, and animated visualizations in Python.

## Data Vizualization
<p align="center">
  <img src="images/quality_correlation.png" alt="Figure 1" width="300" height="200">
  <img src="images/quality_count.png" alt="Figure 2" width="300" height="200">
  <img src="images/quality_heatmap.png" alt="Figure 3" width="300" height="200">
</p>

<p align="center">
  Fig 1. &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Fig 2.&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Fig 3.
</p>

## Outcomes
<p>
  <b>Fig1.</b>Show The relationship between every feature and price also plots every value of faeture with respect to price
<p>
<p>
  <b>Fig2.</b>Bar plot of quantity of every unique value in 'Quality'  
<p>
<p>
  <b>Fig2.</b>Show the heatmap or plots the correlation and its magnitude of label vs feature
<p>

# Final Result
<p><b><i>Accuracy<b></b></i> was found out to be to be <b><i>90%</i></b> using <b><i>RANDOME FORREST</i></b>
<P>Model is saved in a binary file named <b><i>Saved_model</i></b>






