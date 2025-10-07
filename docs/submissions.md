# Submissions

After the participants run their neural network models on the given test set for each rung, they will store their results in a CSV file. The CSV files should be emailed to roman_data_challenge_submissions@googlegroups.com (TODO: currently this Google Group has not yet been created). In the email subject, please include which rung the submission corresponds to. In the email body, please include the names, emails, and affiliations of all team members associated with the submission.

## Rung 0

In this rung, you will train a regression model to determine the Einstein radius of lenses. Results should be submitted for the final 25 lenses in the dataset (with IDs 10711 - 10736). The submitted CSV file should be named "{team name}_rung0_submission.csv" and contain the parameters "ID", "theta_E", and "theta_E_sigma" in the header row. Each row afterwards corresponds to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung0_submissions.ipynb). Each submitted lens will be graded from 0 to 100.


## Rung 1

TODO: Generate training dataset and test dataset

In this rung, you will train a binary classification model to determine whether or not a simulated lens contains dark matter substructure. The submitted CSV file should be named "{team name}_rung1_submission.csv" and contain the parameters "ID", "has_substructure" in the header row. Each row afterwards corresponds to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung1_submissions.ipynb). Each submitted lens will be graded from 0 to 100.

## Rung 2

TBA

## Rung 3

TBA