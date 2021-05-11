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
#### [image_classification.ipynb](image_classification.ipynb)
### Multi-class multi-label
#### [image_classification2.ipynb](image_classification2.ipynb)


## Classification: _mos1, mos2_
### Multi-class _mos1_
#### [image_classification4.ipynb](image_classification4.ipynb)
### Multi-class _mos2_
#### [image_classification3.ipynb](image_classification3.ipynb)


## Regression: _mos1, mos2_
### _mos1_
#### [image_regression.ipynb](image_regression.ipynb)
### _mos2_
#### [image_regression2.ipynb](image_regression2.ipynb)
