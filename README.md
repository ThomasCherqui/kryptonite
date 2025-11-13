

# Coursework MML 



## File Structure

| File/Folders                | Description                                                                |
| --------------------------- | -------------------------------------------------------------------------- |
| `models\`                   | Contains saved results from training MLN on each n.                        |
| `visualisations\`           | Contains all the figures produced from experiments saved from experiment_notebook.ipynb |
| `hiddenlabels\`             | Contains produced labels for each n on hidden datasets |
| `datasets\`                 | Contains provided X, y datasets for each Kryptonite-n |
| `experiment_notebook.ipynb` | Functions to evaluate model performance (e.g. accuracy, confusion matrix). |
| `model_prediction.ipynb`    | Script to use trained model parameters to predict on hidden dataset, saves predictions to hiddenlabels folder. |
| `mln_train.ipynb`           | Main script to train our MLN model, results and weights saved for hyperparameters and best model in models folder.      |


## Notes

The key notebook to run all of our experiments is *experiment_notebook.ipynb* in this notebook you will find the following sections:

### Dataset Exploration

Details our code for our LDA, PCA analysis

### kNN

Code to run the kNN model on the Kryptonite dataset, finds optimal k and presents results.

### MLN

Code to evaluate the results from the trained MLN models.