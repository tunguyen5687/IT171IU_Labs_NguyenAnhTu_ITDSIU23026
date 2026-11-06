# Lab 5: Linear Model Selection and Regularization

- **Full Name:** Nguyễn Anh Tú
- **Student ID:** ITDSIU23026
- **Class / Lab Group:** IT171IU / Group 1
- **How to run the notebook:** 
  1. Open the `.ipynb` file using Google Colab (recommended), VS Code, or JupyterLab.
  2. Ensure the environment has the required packages installed (`ISLP`, `statsmodels`, `scikit-learn`, `numpy`, `pandas`, `matplotlib`, `l0bnb`). If running locally, activate your `.venv` and run the starter/setup cell first.
  3. Go to the top menu and select **"Restart session and run all"** (or **"Restart Kernel and Run All Cells"**) to execute all code cells sequentially from top to bottom without errors.
- **AI-Assistant Usage Note:** All core model selection and regularization workflows—including subset selection (Forward Stepwise Selection using $C_p$), penalized regression methods (Ridge regression and the Lasso using `scikit-learn` Pipelines, `RidgeCV`, and `ElasticNetCV`), dimension reduction techniques (Principal Components Regression [PCR] and Partial Least Squares [PLS]), cross-validation hyperparameter tuning, the empirical importance of predictor standardisation, and closed-form Ridge derivations—were implemented following the lab guidelines and ISLP textbook theory. Google Gemini was utilized as an auxiliary tool for debugging environment setup errors, resolving API parameter compatibility, refactoring code pipelines, and polishing English explanations for statistical interpretations.