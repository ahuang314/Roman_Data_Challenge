# Submissions

 Please prepare your results in a CSV file, to be emailed to [roman_data_challenge_submissions@stonybrook.edu](mailto:roman_data_challenge_submissions@stonybrook.edu). In the email subject, please include which rung the submission corresponds to. In the email body, please include the names, emails, and affiliations of all team members associated with the submission. The submitted CSV file should be named `{team name}_rung{rung number}_submission{submission number}.csv`. For example, if team "bob" wishes to re-submit for rung 1 due to a bug that appeared in the previous submission, their csv file should be named `bob_rung1_submission2.csv`.

For rungs involving classification, the models' precision, recall, and f2 score will be evaluated. For rungs involving regression, the grading scheme is identical to that of [Ding et al. 2021](https://ui.adsabs.harvard.edu/abs/2021MNRAS.503.1096D/abstract), section 2.7.

## Rung 0

In this rung, you will train a regression model to determine the Einstein radius of lenses. The submitted CSV file should contain the parameters `ID`, `theta_E`, and `theta_E_sigma` in the header row, with each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung0_submissions.ipynb).

!!! warning
    The deadline for Rung 0 submissions is TBA, but anticipated in February 2026. Stay tuned for updates.

## Rung 1

In this rung, you will train a binary classification model to determine whether or not a simulated lens contains dark matter substructure. The submitted CSV file should contain the parameters "ID", "has_substructure" in the header row, with each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung1_submissions.ipynb).

## Rung 2

TBA

## Rung 3

TBA