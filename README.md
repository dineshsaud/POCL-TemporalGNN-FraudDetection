# Project Setup Instructions

## Dependencies

To run the Jupyter Notebook for this project, ensure the following dependencies are installed in your Python environment.

### Required Packages

#### Jupyter Notebook
Install Jupyter Notebook to execute the `.ipynb` file:
```bash

pip install torch torchvision torchaudio
pip install torch-geometric
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv
pip install numpy pandas matplotlib seaborn networkx
pip install scikit-learn
pip install ipykernel
python -m ipykernel install --user --name=<env_name>
