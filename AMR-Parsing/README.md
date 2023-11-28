# AMR Parsing

Delve into the world of AMR parsing with the resources provided in this repository. Before embarking on your journey with the Jupyter notebooks, ensure a smooth experience by configuring the necessary paths.

## Configuration

In each Jupyter notebook (.ipynb) file, navigate to the third cell and complete the following configuration:

```python
path_to_AMR3 = '**your path to AMR3.parsing.pt' #'/kaggle/input/amrpickledmodel/AMR3.parsing.pt'
```

Replace `**your path to AMR3.parsing.pt'` with the actual path to the `AMR3.parsing.pt` file.

## Jupyter Notebooks

To execute AMR parsing, run the following Jupyter notebooks found in their respective directories:

### Split After Parsing

- [test_gpu.ipynb](split-after-parsing/test_gpu.ipynb)
- [train_gpu.ipynb](split-after-parsing/train_gpu.ipynb)
- [validation_gpu.ipynb](split-after-parsing/validation_gpu.ipynb)

### Split Before Parsing

- [test-gpu-nltk-splitter.ipynb](split-before-parsing/test-gpu-nltk-splitter.ipynb)
- [train-gpu-nltk-splitter.ipynb](split-before-parsing/train-gpu-nltk-splitter.ipynb)
- [validation-gpu-nltk-splitter.ipynb](split-before-parsing/validation-gpu-nltk-splitter.ipynb)

Navigate to the respective directories and kickstart your AMR parsing experience by executing the desired Jupyter notebook.

Note: Prior to running the notebooks, double-check that you have correctly configured the path as outlined in the configuration section for a seamless execution. Happy parsing!