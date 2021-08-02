# diffraction-ai
## Data: [https://smb.slac.stanford.edu/~holton/deep_learning/trial2/](https://smb.slac.stanford.edu/~holton/deep_learning/trial2/)

```
# downlaod training data from google storage
gsutil -m cp -r gs://diffraction-ai/training_data ./
```
## Label:
[new_multiclasses.csv](./new_multiclasses.csv)

## Classification: _blank,ps1,ps2,multi,ice,badice_
### Multi-class

#### Notebook: [image_classification.ipynb](image_classification.ipynb)

#### Training data
![image](./outputs/multiclass_training_samples.png)
![image](./outputs/multiclass_training_data.png)

#### ROC Curve (Training)
![image](./outputs/multiclass_ROC_training.png)

#### ROC Curve (Testing)
![image](./outputs/multiclass_ROC_testing.png)

#### PR Curve (Training)
![image](./outputs/multiclass_PR_training.png)

#### PR Curve (Testing)
![image](./outputs/multiclass_PR_testing.png)

#### Confusion Matrix (Training)
![image](./outputs/multiclass_ConfusionMatrix_training.png)

#### Confusion Matrix (Testing)
![image](./outputs/multiclass_ConfusionMatrix_testing.png)

### Multi-class multi-label
#### [image_classification2.ipynb](image_classification2.ipynb)


## Classification: _mos1_
### Multi-class _mos1_
#### Notebook: [image_classification4.ipynb](image_classification4.ipynb)

#### Training data
![image](./outputs/mos1_classification_training_samples.png)
![image](./outputs/mos1_classification_training_data.png)

#### ROC Curve (Training)
![image](./outputs/mos1_classification_ROC_training.png)

#### ROC Curve (Testing)
![image](./outputs/mos1_classification_ROC_testing.png)

#### PR Curve (Training)
![image](./outputs/mos1_classification_PR_training.png)

#### PR Curve (Testing)
![image](./outputs/mos1_classification_PR_testing.png)

#### Confusion Matrix (Training)
![image](./outputs/mos1_classification_ConfusionMatrix_training.png)

#### Confusion Matrix (Testing)
![image](./outputs/mos1_classification_ConfusionMatrix_testing.png)

## Regression: _mos1, mos2_
### _mos1_
#### Notebook: [image_regression.ipynb](image_regression.ipynb)

#### Training data
![image](./outputs/mos1_regression_training_samples.png)
![image](./outputs/mos1_regression_training_data.png)

#### Prediction Error Analysis
![image](./outputs/mos1_regression_Predict_Error_Analysis.png)


### _mos2_
#### [image_regression2.ipynb](image_regression2.ipynb)

#### Training data
![image](./outputs/mos2_regression_training_samples.png)
![image](./outputs/mos2_regression_training_data.png)

#### Prediction Error Analysis
![image](./outputs/mos2_regression_Predict_Error_Analysis.png)
