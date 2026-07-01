\# ML2 Anonymous Multi-Class Classification



This repository contains the final notebook for the ML2 anonymous multi-class classification challenge.  

The workflow includes data preprocessing, model validation, MLflow experiment tracking, final model selection, and DVC-based data versioning.



\## Project Files



\- `ML2\_FINAL\_Required\_MLOps\_Experiments.ipynb`: final notebook with the required experiments and MLflow tracking.

\- `sample\_submission.csv`: sample format for the Kaggle submission.

\- `train\_data.csv.dvc`: DVC tracking file for the training dataset.

\- `test\_data.csv.dvc`: DVC tracking file for the test dataset.



\## Data Versioning with DVC



The training and test datasets are tracked using DVC and are not committed directly to GitHub.  

After cloning the repository, install the requirements and run:



```bash

dvc pull

