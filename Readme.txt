This is an Assignment given by Infrrd.ai

Note: Filtered dataset means the dataset after removing every row with label "OTHER"

Repo contents:

Files:
Data Analysis full.ipynb: Contains the code for exploratory data analysis of the entire dataset
Data Analysis filtered.ipynb: Contains the code for exploratory data analysis of the filtered dataset
Infrrd Assignment Long Explanation.docx: Contains full in-depth explanation (augmented with plots) of every step taken in this assignment.
Infrrd AssignmentShort.docx: Very Concise document which contains the major steps taken in this assignment.
main.ipynb: Contains the code where the final model is trained and the results are appended and saves into tsv files as mentioned.
Model Analysis.ipynb: Contains the code for the Model Analysis. Aka the Cross validation and the hyperparameter tuning.
eval.py: Python file given by Infrrd.ai to evaluate my results.

Folders:
dataset: Contains the entire dataset.
In this dataset, there are 4 folders to take note of.

result: Contains the tsv files which have been appended by the predicted labels.
train: The training dataset.
val: The testing dataset provided, which has been appended with its predictions and saved in "results"
val_w_ann: The same testing dataset, but it also contains the true labels.