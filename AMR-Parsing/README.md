# AMR Parsing

This repository contains code for AMR parsing. Before running the Jupyter notebooks, please make sure to configure the necessary path.

## Configuration

In each Jupyter notebook (.ipynb) file, locate the third cell and fill in the following configuration:

```python
path_to_AMR3 = '**your path to AMR3.parsing.pt' #'/kaggle/input/amrpickledmodel/AMR3.parsing.pt'
```

Make sure to replace `**your path to AMR3.parsing.pt'` with the actual path to the `AMR3.parsing.pt` file.

## Jupyter Notebooks

To perform AMR parsing, you can run the following Jupyter notebooks in the respective directories:

### Split After Parsing

- [test_gpu.ipynb](split-after-parsing/test_gpu.ipynb)
- [train_gpu.ipynb](split-after-parsing/train_gpu.ipynb)
- [validation_gpu.ipynb](split-after-parsing/validation_gpu.ipynb)

### Split Before Parsing

- [test-gpu-nltk-splitter.ipynb](split-before-parsing/test-gpu-nltk-splitter.ipynb)
- [train-gpu-nltk-splitter.ipynb](split-before-parsing/train-gpu-nltk-splitter.ipynb)
- [validation-gpu-nltk-splitter.ipynb](split-before-parsing/validation-gpu-nltk-splitter.ipynb)

Please navigate to the respective directories and execute the desired Jupyter notebook.

Note: Ensure that you have configured the path correctly as mentioned in the configuration section before running the notebooks.