# Submissions

After the participants run their neural network models on the given test set for each rung, they will store their results in a CSV file. The CSV files should be emailed to roman_data_challenge_submissions@googlegroups.com (TODO: currently this Google Group has not yet been created). In the email subject, please include which rung the submission corresponds to. In the email body, please include the names, emails, and affiliations of all team members associated with the submission. The submitted CSV file should be named "{team name}_rung{rung number}_submission.csv". For all of the rungs, each submitted lens will be graded from 0 to 100.

## Rung 0

In this rung, you will train a regression model to determine the Einstein radius of lenses. The submitted CSV file should contain the parameters "ID", "theta_E", and "theta_E_sigma" in the header row, with each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung0_submissions.ipynb).

**The deadline for Rung 0 submissions is TBA**

## Rung 1

In this rung, you will train a binary classification model to determine whether or not a simulated lens contains dark matter substructure. The submitted CSV file should contain the parameters "ID", "has_substructure" in the header row. with each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung1_submissions.ipynb).

## Rung 2

TBA

## Rung 3

TBA