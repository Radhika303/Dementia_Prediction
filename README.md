# Dementia Prediction 

Team: Mabel Alamu, Dainty Cuevas, & Radhika Sagar 

## Data 

	
Longitudinal collection of 150 subjects aged 60 to 96.

EDUC   Years of Education

SES      Socioeconomic Status- (1 illiterate - 7 honors)   

MMSE Mini Mental State Examination- 30-point questionnaire that is used 	extensively in clinical and research settings to measure cognitive impairment.

CDR     Clinical Dementia Rating-  5-point scale  (0 normal - 3 demented) 

eTIV     Estimated Total Intracranial Volume

nWBV  Normalize Whole Brain Volume

ASF      Atlas Scaling Factor


## Pre-Processing

```python
# OVERSAMPLING
from sklearn.datasets import make_classification
from imblearn.over_sampling import RandomOverSampler
from collections import Counter
...
print(Counter(y_over))
...
Counter({0: 9900, 1: 9900})

# PCA
from sklearn.preprocessing import StandardScaler 
X_std = StandardScaler().fit_transform(X)
X_std
```

## Machine Learning Models
#### Grid Search                       
#### Logistic Regression 
#### SVM (Support Vector Machine) 
#### Receiver Operating Characteristic Curve (ROC AUC)
