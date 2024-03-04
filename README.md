# Remaning-Useful-Life-Prediction-NASA-dataset-

**<u>About Dataset</u>**

The dataset involves four Li-ion batteries subjected to charge,
discharge, and impedance cycles at room temperature. Charging involves
constant current (CC) and constant voltage (CV) modes, while discharge
is at a specified current until reaching set voltage levels. Impedance
measurements cover a frequency range. The experiments continue until
batteries meet end-of-life (EOL) criteria. The dataset structure
includes information on cycles, ambient temperature, and date-time
records. It provides data on voltage, current, temperature, and
impedance, facilitating the prediction of remaining charge and remaining
useful life (RUL).

**Regression Model Evaluation:**

**Linear Regression**:

Mean Squared Error: 0.000224

R-squared: 0.9768

**Decision Tree Regressor:**

Mean Squared Error: 5.79e-30

R-squared: 1.0

**Random Forest Regressor:**

Mean Squared Error: 1.23e-09

R-squared: 0.99999987

2\. Ensemble Techniques:

**Bagging with Random Forest:**

Mean Squared Error: 1.08e-11

R-squared: 0.999999999

**Boosting with Gradient Boosting:**

Mean Squared Error: 3.02e-06

R-squared: 0.9997

**<u>Observations:</u>**

Decision Tree, Random Forest, Bagging with RF, and Boosting with GB
exhibit near-perfect accuracy, with R-squared values close to 1.0.

Linear Regression also performs well, though not as high as the
tree-based models.

The ensemble techniques (Random Forest, Bagging with RF, Boosting with
GB) outperform individual models, emphasizing their effectiveness in
improving predictive accuracy.

**<u>Conclusion:</u>**

Based on this comparison, Decision Tree, Random Forest, Bagging with RF,
and Boosting with GB are identified as strong candidates for predicting
the State of Health (SOH) of batteries due to their high accuracy. The
choice among these models may depend on factors such as
interpretability, computational efficiency, and specific requirements of
the application.
