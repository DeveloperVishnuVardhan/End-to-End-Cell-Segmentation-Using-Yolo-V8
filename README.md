# End-to-End-Cell-Segmentation-Using-Yolo-V8

The goal of project is build an end-to-end cell-segmentation application.

# Workflow of the Project.
1. Constants -> Initializes all the constant variables to use in the project.
2. entity -> Creates entites to use in the project.
3. components -> Contains code for data_ingestion, data_validation, model_trainer logic.
4. Pipelines -> Code to Initialize training pipelines.
5. app.py -> Executes the application.

# Supporting Modules.
1. **logger:** contains the code to perform logging.
2. **exception:** contains the code to perform exception handling.
3. **utils:** Contains all the utility functions used in the project.
4. **research:** Contains the experimentation .ipynb files.
5. **templates:** Contains the code used to develop UI.

# Data-Ingestion flow-chart.
data_ingestion_dir
feature_store_file_path
data_download_url

# AZURE-CICD-Deployment-with-Github-Actions

## Run from terminal:

docker build -t cellseg.azurecr.io/cell:latest .

docker login cellseg.azurecr.io

docker push cellseg.azurecr.io/cell:latest

## Services used
1. Container Registry
2. web app
3. Github-actions

## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 

## Instruction to run the application.
1. Run the command pip install -r requirements.txt
2. Run python app.py

Please send an email to: kolla.j@northeastern.edu if you have any queries about the project.
