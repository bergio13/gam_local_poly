# GAM with Local Polynomials and Predictor Importance Analysis using LOCO

This project was completed for the *"Statistical Learning"* course in the Data Science Master's program at *Sapienza University of Rome*. It involves implementing a **Generalized Additive Model (GAM)** using **Local Polynomials** and analyzing predictor importance through the **Leave-One-Covariate-Out (LOCO)** score. 

Our approach scored **4th** place out of 23 teams in the course's *Kaggle* competition, focused on a redshift prediction problem.
<div align="center">
    <img src="https://github.com/bergio13/gam_local_poly/blob/main/leaderboard.png" style="width: 40%;" alt="Leaderboard" />
</div>

## Project Overview
- **Dataset**: The training data consists of approximately 7,500 astronomical objects with redshift values and photometric color measurements (features: ug, gr, ri, iz, zy, and i). The goal is to predict the redshift of an additional 2,500 objects based on these photometric colors.
- **Objective**: Develop a GAM using local polynomial smoothers to model the relationship between redshift and photometric colors and assess predictor importance with LOCO.
- **Competition**: Redshift prediction problem on Kaggle, where the interpretability and predictive power of the model were key. This approach ranked 4th out of 23 teams.

<div align="center">
    <img src="https://github.com/bergio13/gam_local_poly/blob/main/output/diagnostic_plot.png" style="width: 50%;" alt="Diagnostic Plot" />
</div>


<div align="center">
    <img src="https://github.com/bergio13/gam_local_poly/blob/main/output/variable_importance.png" style="width: 50%;" alt="LOCO scores" />
</div>
