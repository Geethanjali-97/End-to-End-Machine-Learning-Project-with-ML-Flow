# End-to-End-Machine-Learning-Project-with-ML-Flow


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
https://github.com/Geethanjali-97/End-to-End-Machine-Learning-Project-with-ML-Flow.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
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

MLFLOW_TRACKING_URI=https://dagshub.com/geethanjali.mejari/End-to-End-Machine-Learning-Project-with-ML-Flow.mlflow \
MLFLOW_TRACKING_USERNAME=geethanjali.mejari \
MLFLOW_TRACKING_PASSWORD=61e952da01e575a8996ad7f48ceb6fb4c36c2f26 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/geethanjali.mejari/End-to-End-Machine-Learning-Project-with-ML-Flow.mlflow
export MLFLOW_TRACKING_USERNAME=geethanjali.mejari

export MLFLOW_TRACKING_PASSWORD=61e952da01e575a8996ad7f48ceb6fb4c36c2f26

```



AZURE-CI/CD-Deployment-with-Github-Actions using container registry and  web app
Save pass:
oW8DIkvLt2RcHzV29FRhk2vTZCTekiwQV+5CuXR0SC+ACRCuhG4A

Run from terminal:
docker build -t winequality.azurecr.io/winequality:latest .

docker login winequality.azurecr.io

docker push winequality.azurecr.io/winequality:latest

Deployment Steps:
Build the Docker image of the Source Code
Push the Docker image to Container Registry
Launch the Web App Server in Azure
Pull the Docker image from the container registry to Web App server and run