# AMR-finetuned-models

Explore the capabilities of fine-tuning and utilizing various models designed specifically for AMR (Abstract Meaning Representation) tasks with the help of the Jupyter Notebook files in this repository. Follow the step-by-step instructions below to seamlessly run the notebooks and elevate your AMR-related endeavors.

## Instructions

1. Open the notebook file corresponding to your desired model:

   - [distilroberta-han-pretrained.ipynb](distilroberta-han-pretrained.ipynb)
   - [distilroberta-han.ipynb](distilroberta-han.ipynb)
   - [legalbert-han-pretrained.ipynb](legalbert-han-pretrained.ipynb)
   - [legalbert-han.ipynb](legalbert-han.ipynb)

2. Update the configuration statements within the notebook following these guidelines:

   - Modify the `base_path` variable in the code to reflect the location of your parsed data. Replace `"**location_of_parsed_data**"` with the actual path.
   - If you possess validation data, update the `base_path` variable for validation data as well. Replace `"**location_of_parsed_validation_data**"` with the correct path.
   - For pre-trained model fine-tuning, load the pre-trained model by adjusting the following line:

     ```python
     model.load_state_dict(torch.load('**path_to_pretrained_model**'))
     ```

     Replace `"**path_to_pretrained_model**"` with the path to your pre-trained model file.

3. Run the notebook and adhere to the instructions provided within to execute the desired AMR tasks efficiently.

Note that each notebook file is self-contained, encompassing all the essential code and explanations required to perform the specified tasks. Elevate your AMR model fine-tuning experience with these comprehensive and user-friendly resources. Happy modeling!