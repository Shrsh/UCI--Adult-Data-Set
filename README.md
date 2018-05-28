# UCI--Adult-Data-Set
This data was extracted from UCI Repository- ADULT DATA.\

## Test-Train Split
Split into train-test using MLC++ GenCVFiles (2/3, 1/3 random).<br />
48842 instances, mix of continuous and discrete    (train=32561, test=16281)<br />
45222 if instances with unknown values are removed (train=30162, test=15060)<br />

### Prediction task is to determine whether a person makes over 50K a year.

# Results: <br />
   | Algorithm                                    | Accuracy           |
   |----------------------------------------------|--------------------|
   |SVM- 'rbf' Kernel                             | 0.7986448220064725 |
   |SVM- 'linear' Kernel                          | 0.8180622977346278 |
   |Decision Trees                                | 0.8518406148867314 |
   |Bagging with Decision Trees                   | 0.8973503236245954 | 
   |Random Forest                                 | 0.8701456310679612 |
