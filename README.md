co# End to end machine learning: MLOps Recommendation system

## Summary:

This repository demonstrates how to deploy an end-to-end ML application using **CI/CD pipelines** and GitHub Actions, in combination with a container registry and Azure Web App. And provides a hands-on approach to deploying ML models, making it easier for both beginners developers to embrace this technology. By using CI/CD pipelines, GitHub Actions, a container registry, and Azure Web App, you can streamline the deployment process, ensuring that your machine learning models are always up to date and readily accessible.




1. Data Ingestion :
    - In the Data Ingestion phase, the initial step involves reading the data from a CSV file.
    - Subsequently, the data is partitioned into training and testing sets, which are then saved as CSV files.
2. Data Transformation :
   - Preprocess data with scaling and encoding, saving as a PKL file.
3. Model Training :
   - Train, evaluate, and chosee the best model.
4. Prediction Pipeline :
   - Utilize pickle files for predictions in a Python environment.
5. Flask App creation :
   - Create web app
     
### Run in localhost:

```zsh
git https://github.com/Rakeshakhouri
python -m venv venv
source venv/bin/activate
#test training
python setup.py install
python src/components/data_ingestion.py 
```

Then you have to create a Docker image, Container Registry and Azure Web App and run:
```zsh


---
*Author: RakeshAKhouri*
