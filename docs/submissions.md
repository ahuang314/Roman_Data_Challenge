# Submissions

After the participants run their neural network models on the given test set for each rung, they will store their results in a CSV file. The CSV files should be emailed to roman_data_challenge_submissions@googlegroups.com (TODO: currently this Google Group has not yet been created). In the email subject, please include which rung the submission corresponds to. In the email body, please include the names, emails, and affiliations of all team members associated with the submission.

## Rung 0

This tutorial rung should serve as a way for participants to familiarize themselves with the data challenge. The dataset of 10,737 lenses, stored in an h5 file, can be downloaded [here](https://gowustl-my.sharepoint.com/personal/b_t_wedig_wustl_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fb%5Ft%5Fwedig%5Fwustl%5Fedu%2FDocuments%2F2025%2D09%2D19%20Roman%20Data%20Challenge%20mini%20dataset%2Froman%5Fdata%5Fchallenge%5Fmini%5Fv%5F0%5F1%2Eh5&parent=%2Fpersonal%2Fb%5Ft%5Fwedig%5Fwustl%5Fedu%2FDocuments%2F2025%2D09%2D19%20Roman%20Data%20Challenge%20mini%20dataset&ga=1). A Jupyter notebook demonstrating how to access and manipulate the data can be found [here](https://gowustl-my.sharepoint.com/personal/b_t_wedig_wustl_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fb%5Ft%5Fwedig%5Fwustl%5Fedu%2FDocuments%2F2025%2D09%2D19%20Roman%20Data%20Challenge%20mini%20dataset%2Fview%5Fdataset%2Eipynb&parent=%2Fpersonal%2Fb%5Ft%5Fwedig%5Fwustl%5Fedu%2FDocuments%2F2025%2D09%2D19%20Roman%20Data%20Challenge%20mini%20dataset&ga=1).

In this rung, you will train a regression model to determine the Einstein radius of lenses. Results should be submitted for the final 25 lenses in the dataset (with IDs 10711 - 10736). The submitted CSV file should be named "{team name}_rung0_submission.csv" and contain the parameters "ID", "theta_E", and "theta_E_sigma" in the header row, and each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung0_submissions.ipynb). Each submitted lens will be graded from 0 to 100.


## Rung 1

TODO: Generate training dataset and test dataset

In this rung, you will train a binary classification model to determine whether or not a simulated lens contains dark matter substructure. The submitted CSV file should be named "{team name}_rung1_submission.csv" and contain the parameters "ID", "has_substructure" in the header row, and each row afterwards corresponding to the results for each of the lenses. An example can be found in the notebook [here](https://github.com/ahuang314/Roman_Data_Challenge/blob/main/Notebooks/rung1_submissions.ipynb). Each submitted lens will be graded from 0 to 100.

## Rung 2

TBA

## Rung 3

TBA