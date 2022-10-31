# FixCrea

FixCrea uses an Extreme Gradient Boosting model to closely approximate an enzymatically-derived result for a given Jaffe-based creatinine result.

## Online Resources

Online deployment of Extreme Gradient Boosting model: https://fixcrea.onrender.com

Github repo site for machine learning training: https://github.com/fixcrea/fixcrea

Github repo site for offline linear regression version: https://github.com/fixcrea/fixcrea_offline

## Files Included

The Python code and statistical model training can be reviewed in the [Jupyter notebook file](https://github.com/fixcrea/fixcrea/blob/main/Jaffe%20Enzymatic%20Model%201.5%20Public%20Build.ipynb).

The Python dependencies used in deriving the models can be reviewed in the [requirements.txt file](https://github.com/fixcrea/fixcrea/blob/main/requirements.txt).

The file [190504 Jaffe Enzymatic 210426 Public.csv](https://github.com/fixcrea/fixcrea/blob/main/190504%20Jaffe%20Enzymatic%20210426%20Public.csv) contains the data used for training the models.

The file [190506 Jaffe Enzymatic Test Set 210426 Public.csv](https://github.com/fixcrea/fixcrea/blob/main/190506%20Jaffe%20Enzymatic%20Test%20Set%20210426%20Public.csv) contains the data used for testing the trained models.

The Extreme Gradient Boosting model is available as a Pickle model and a Joblib sav.

## Updates
### 1.5 - 10.27.22
1. Added Joblib model save and testing

### 1.4 - 10.11.22
1. Compatibility check with Anaconda Docker image continuumio/anaconda3 2022.9
2. Compatibility check with Jupyter Stacks Docker image jupyter/scipy 2022.10
3. Fixed data formatting '190506 Jaffe Enzymatic Test Set Public.csv': added index column
4. Consolidate library initiation

### 1.3 - 02.13.22
1. Compatibility check with Linux Debian anaconda3 updates

### 1.2 - 04.26.21
1. Compatibility check with Linux Debian anaconda3 updates

### 1.1 - 05.06.19
1. Compatibility check with Linux Debian anaconda3 updates