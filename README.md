# MLAI Challenge 2025 – Deliverables

**By Filippo Colella (03344), Camilla Marvaldi, Lorenzo Licini,
Riccardo Leonetti, Parik Lanke, Jahnavi Minocha**

---

## Overview

This repository contains the list of deliverables for the MLAI Challenge 2025.

---

## Contents

- `AttendanceIsAllYouNeed_Slides.pptx`: Presentation slides.
- `MLAI_Report_AttendanceisAllYouNeed.pdf`: Project report.
- `notebooks.zip`: Contains the Jupyter notebooks for the GNN approach and the classical approach.
- `predictions_GNN.csv`: Prediction file from the GNN approach. Includes one extra column with the predicted class, in addition to the expected columns.
- `approachML_predictions.csv`: Prediction file from the classical machine learning approach, contains exactly the expected columns.
- `presentazione_video.mp4`: Video presentation.
- - `diabetes_train.csv`: Initial train dataset given for the challenge, necessary to make the first Notebook to run 
- - `diabetes_test.csv`: Initial test dataset given for the challenge, necessary to test the inference part in the notebooks
- - `df_model.csv`: In the first notebook (Approach_ML) after encoding, cols dropping and cleaning we save this version of the dataset given to the model in both notebooks. NB: the GNN notebook starts by using df_model and not "diabetes_train.csv" since it starts from the already cleaned df. It is therefore necessary to load this file to test the functions inside GNN_approach. 


---


