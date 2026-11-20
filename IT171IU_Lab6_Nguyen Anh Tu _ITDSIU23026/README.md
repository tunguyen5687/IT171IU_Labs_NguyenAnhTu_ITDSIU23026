# Lab 6: Moving Beyond Linearity

- **Full Name:** Nguyễn Anh Tú
- **Student ID:** ITDSIU23026
- **Class / Lab Group:** IT171IU / Group 1
- **How to run the notebook:**
  1. Open the `.ipynb` file in Google Colab, VS Code, or JupyterLab.
  2. Ensure dependencies are installed: `ISLP`, `statsmodels`, `scikit-learn`, `pygam`, `numpy`, `pandas`, `matplotlib`.
  3. Run all cells sequentially via **"Restart Kernel and Run All Cells"**.
- **Key Methods Covered:**
  - **Polynomial Regression & Step Functions:** Model non-linear curvature on `Wage` and `Boston`; tune degrees and cutpoints via 5-fold/10-fold CV and ANOVA.
  - **Splines (B-Splines & Natural Splines):** Local piecewise polynomial fitting with continuity constraints and boundary stabilization; select degrees of freedom ($df$) via CV.
  - **Smoothing Splines & GAMs:** Non-parametric smoothing via roughness penalties ($\lambda$) and additive decomposition ($Y = \beta_0 + \sum f_j(X_j)$) on `College` out-of-state tuition.
- **AI-Assistant Usage Note:** All non-linear models, cross-validation workflows, and visualizations were implemented following the lab specifications and textbook guidelines. Google Gemini was used as an auxiliary tool for syntax debugging, code modularization, and refining statistical interpretations.