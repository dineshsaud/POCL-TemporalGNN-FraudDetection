# Implementation of the Code

This project is based on the research paper [**Pretrained Online Contrastive Learning Model for Fraud Detection**](https://ojs.aaai.org/index.php/AAAI/article/view/30259). 

Code is implemented in the repo : https://github.com/AI4Risk/POCL
The implementation reproduces and extends the original methodology to enhance its effectiveness in detecting fraudulent medical insurance claims.

## Main Contribution
We introduced the **TemporalGNN** model, a graph-based neural network with temporal features, to complement the original POCL model. This extension improves the model's adaptability and accuracy during online learning scenarios. Comparative analysis shows enhanced AUC, F1 Score, and accuracy over the baseline.



# Project Setup Instructions

## Dependencies

To run the Jupyter Notebook for this project, ensure the following dependencies are installed in your Python environment.

### Required Packages
#### Jupyter Notebook
Install Jupyter Notebook to execute the `.ipynb` file:

```
pip install torch torchvision torchaudio
pip install torch-geometric
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv
pip install numpy pandas matplotlib seaborn networkx
pip install scikit-learn
pip install ipykernel
python -m ipykernel install --user --name=<env_name>
```

References 

Paper:https://ojs.aaai.org/index.php/AAAI/article/view/30259

git repo : https://github.com/AI4Risk/POCL
