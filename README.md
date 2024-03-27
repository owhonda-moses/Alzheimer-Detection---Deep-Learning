# ALZHEIMER DETECTION 

## INTRODUCTION

> In this project, we developed deep learning models using PyTorch and leveraging GPU acceleration, to analyze MRI scans of Alzheimer's patients. The dataset contained 5,121 training data and 1,279 test data of PyTorch tensor images.
We employed various model architectures and adjustments to the training algorithm to improve performance, and employed the area under Precision-Recall curve (AUPRC) and confusion matrix for performance evaluation.


### NEURAL NETWORKS

Basic but functional simple and convolutional neural networks containing the necessary features to constitute as neural networks were built. Subsequently, improved models were built with changes/adaptations made to the model structure, and training algorithm, to improve the results delivered by the models. A comparative analysis was then carried out on the improved models, discussing the changes made and how they improved on the basic models. 

### MODEL EVALUATION

The area under Precision-Recall curve (AUPRC) and confusion matrix were used for a comprehensive performance evaluation of the trade-off between precision and recall across different thresholds for each model.


### KEY FINDINGS

The models initially exhibited overfitting tendencies, which were mitigated through hyperparameter tuning during training. Notably, the convolutional model was enhanced with multiple convolutional layers and fully connected layers, incorporating regularization techniques and weight initialization. This refinement process led to significant improvements in model performance, ultimately yielding the best results.


#### PACKAGES USED:

- JuPyter notebook
- PyTorch
- tqdm
- pandas
- numpy
- sklearn
- matplotlib
- seaborn


_Some notable references for this project include -_
- https://stackoverflow.com/
- https://github.com/
- https://pytorch.org/docs/stable/index.html
- https://towardsdatascience.com/
- https://kaggle.com/