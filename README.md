# End-to-end-Machine-Learning-Project-with-MLflow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Aaryaman09/wine-quality-mlflow-deploy
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n venv python=3.10.6 -y
```

```bash
conda activate venv/
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Aaryaman09/wine-quality-mlflow-deploy.mlflow \
MLFLOW_TRACKING_USERNAME=Aaryaman09 \
MLFLOW_TRACKING_PASSWORD=<> \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Aaryaman09/wine-quality-mlflow-deploy.mlflow

export MLFLOW_TRACKING_USERNAME=Aaryaman09 

export MLFLOW_TRACKING_PASSWORD=<>

```

> ## Use set instead of export for windows.

### Fetch MLflow tracking URI details on Dagshub
![alt text](https://github.com/Aaryaman09/wine-quality-mlflow-deploy/blob/main/images/mlflow_tracking_uri_info_on_DAGSHUB.JPG?raw=true)


## About MLflow 
MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & tagging your model

