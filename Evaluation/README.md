# Evaluation

This project directory contains notebooks for evaluating different models on specific datasets. Below are the details of the files present in this directory:

- `evalauation-of-distilroberta-models.ipynb`: This Jupyter notebook focuses on evaluating the performance of DistilRoBERTa models. It contains code and instructions to load the trained models and perform evaluation tasks on a test dataset. To run this notebook, follow the instructions provided within.

- `evalauation-of-legalbert-models.ipynb`: This Jupyter notebook is dedicated to evaluating LegalBERT models. It includes code snippets and guidelines to load the model and assess its performance using a specific evaluation dataset. To execute this notebook, refer to the instructions mentioned inside.

To evaluate the models and analyze their performance, please follow these steps:

1. Open the notebook `evalauation-of-distilroberta-models.ipynb` in Jupyter Notebook or JupyterLab.
2. Modify the `model.load_state_dict` line within the notebook to specify the path to the model you want to evaluate. (`model.load_state_dict(torch.load('**model path**'))`); Also appropriately set base path: `base_path = "**AMR-parsed test dataset**"`
3. Execute the cells in the notebook sequentially, following the provided instructions and guidelines.
4. Once you have completed the evaluation of DistilRoBERTa models, proceed to the notebook `evalauation-of-legalbert-models.ipynb`.
5. Similarly, update the `model.load_state_dict` line in this notebook to specify the path to the LegalBERT model you wish to evaluate. (`model.load_state_dict(torch.load('**model path**'))`); Also appropriately set base path: `base_path = "**AMR-parsed test dataset**"`
6. Run the cells in the notebook as instructed to evaluate the LegalBERT model on the designated evaluation dataset.