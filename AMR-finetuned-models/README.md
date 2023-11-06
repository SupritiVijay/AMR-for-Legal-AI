# AMR-finetuned-models

This repository contains Jupyter Notebook files for fine-tuning and using various models for AMR (Abstract Meaning Representation) tasks. Please follow the instructions below to run the notebooks.

## Instructions

1. Open the desired notebook file from the list below:

   - [distilroberta-han-pretrained.ipynb](distilroberta-han-pretrained.ipynb)
   - [distilroberta-han.ipynb](distilroberta-han.ipynb)
   - [legalbert-han-pretrained.ipynb](legalbert-han-pretrained.ipynb)
   - [legalbert-han.ipynb](legalbert-han.ipynb)

2. Update the configuration statements in the notebook as described below:

   - In the code, change the `base_path` variable to the location of the parsed data. Replace `"**location_of_parsed_data**"` with the actual path.
   - If you have validation data, update the `base_path` variable for validation data as well. Replace `"**location_of_parsed_validation_data**"` with the actual path.
   - If you want to perform pre-trained model fine-tuning, load the pre-trained model by modifying the following line:

     ```
     model.load_state_dict(torch.load('**path_to_pretrained_model**'))
     ```

     Replace `"**path_to_pretrained_model**"` with the path to your pre-trained model file.

3. Run the notebook and follow the instructions provided within the notebook to perform the desired AMR tasks.

Please note that the notebook files are self-contained and contain all the necessary code and explanations to perform the tasks.