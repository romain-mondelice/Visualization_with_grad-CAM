# Dlip TP2 - Visualization with grad-CAM

## Project Structure

Below is the project structure, enabling a modular and manageable codebase.
Some subforlders are not used and may be empty.

```
├── README.md          <-  A README file for teacher to understand the project setup.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable given data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc. (when asked)
│   └── figures        <- Graphics and figures for use in reports.
│ 
├── requirements.txt   <- Required libraries and dependencies. 
│
├── pyproject.toml     <- Make the project pip installable with `pip install -e`.
├── src                <- If needed Source code of the project.
│   │
│   ├── conf           <- Configuration files for experiments (YAML files managed by Hydra).
│   │   └── ...
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── ...
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── ...
│   │
│   ├── models         <- Scripts to train models, to use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── ...
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── ...

```