
This structure is designed for machine learning project.

Project Organization
------------

    ├── environment.yml              <- The environment file
    │
    ├── LICENSE
    │
    ├── README.md                    <- The top-level README for developers using this project.
    │
    ├── config                       <- Directory for yaml configuration files for model training, etc
    │
    ├── data
    │   ├── external                 <- Data from third party sources.
    │   └── processed                <- The final, canonical data sets for modeling.
    │
    ├── figures                      <- Generated graphics and figures
    │
    ├── models                       <- Saving model after training steps
    │   ├── encoding                 <- the model's encoding infomation    
    │   └── NN                       <- the full model information
    │
    ├── nohup                        <- the log and error information of each run
    │
    ├── notebooks                    <- Updated Jupyter notebooks, file naming gets a number (for ordering),
    │                                   the creator's initials, and a short `-` delimited description, 
    │                                   e.g. `1.0-pg-data-analysis`
    │   └── archive                  <- Jupyter notebook belongs to early stage analysis which are no longer usable
    │
    ├── reports                      <- Generated analysis result as CSV, PDF, LaTeX, etc.
    │   ├── activation               <- the results of  models' activation score
    │   ├── CV                       <- the results of cross-validation performance
    │   └── {OTHER_ANALYSIS}         <- the results of other analysis
    │
    └── src                          <- Source code for the project
        ├── archive                  <- Previous, not usable scripts
        └── {SCRIPT_NAME}            <- helper scripts
    

--------

<p><small>Based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter</a> and <a target="_blank" href="https://github.com/cmawer/reproducible-model">cmawer/reproducible-model</a> data science project template</small></p>
