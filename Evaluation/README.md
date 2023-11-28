# Evaluation

Welcome to the Evaluation directory, where you can rigorously assess the performance of different models on specific datasets. Dive into the details of the files available in this directory:

- `evaluation-of-distilroberta-models.ipynb`: This [Jupyter notebook](evaluation-of-distilroberta-models.ipynb) focuses on meticulously evaluating the performance of DistilRoBERTa models. It comprises code and detailed instructions for loading trained models and conducting evaluation tasks on a designated test dataset. To engage with this notebook, follow the instructions provided within.

- `evaluation-of-legalbert-models.ipynb`: This dedicated [Jupyter notebook](evaluation-of-legalbert-models.ipynb) is designed for evaluating LegalBERT models. It provides code snippets and guidelines to load the model and assess its performance using a specified evaluation dataset. Execute this notebook by referring to the instructions outlined within.

To effectively evaluate the models and gain insights into their performance, follow these steps:

1. Open the notebook `evaluation-of-distilroberta-models.ipynb` in Jupyter Notebook or JupyterLab.
2. Modify the `model.load_state_dict` line within the notebook to specify the path to the model you want to evaluate (`model.load_state_dict(torch.load('**model path**'))`); Also, appropriately set the base path: `base_path = "**AMR-parsed test dataset**"`.
3. Execute the cells in the notebook sequentially, adhering to the provided instructions and guidelines.
4. Once the evaluation of DistilRoBERTa models is complete, proceed to the notebook `evaluation-of-legalbert-models.ipynb`.
5. Similarly, update the `model.load_state_dict` line in this notebook to specify the path to the LegalBERT model you wish to evaluate (`model.load_state_dict(torch.load('**model path**'))`); Also, appropriately set the base path: `base_path = "**AMR-parsed test dataset**"`.
6. Run the cells in the notebook as instructed to evaluate the LegalBERT model on the designated evaluation dataset.

Maximize your model assessment capabilities with these detailed and user-friendly resources. Happy evaluating!