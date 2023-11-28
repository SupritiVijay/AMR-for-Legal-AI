<img src="/images/legal-amr.png" width="35%" height="35%" align="right" />

# AMR Evaluation for Legal Judgment Prediction

Legal judgment prediction is an automated approach to forecast case outcomes using historical facts and opinions; it holds significant potential for enhancing the efficiency of the legal system. However, concerns about perpetuating biases necessitate careful exploration and refinement of prediction methodologies. Abstract Meaning Representation (AMR), a graph-like structure capturing semantically meaningful information, has recently shown promise as an intermediate text representation in various Natural Language Processing (NLP) tasks.

This project focuses on leveraging the unique capabilities of AMR in the domain of legal judgment prediction. The central objective is to assess the extent to which AMR encodes biases or, conversely, abstracts away from them. Our research aims to contribute to a nuanced understanding of AMR's potential benefits and limitations within the context of legal NLP. The following repository provides a comprehensive toolkit designed to facilitate research on AMR tasks for legal judgment prediction. It includes dedicated directories for parsing, pretraining, finetuned models, and evaluation, each offering detailed instructions.

## [AMR-Parsing](/AMR-Parsing)

<img src="/images/quantitative.png" width="35%" height="35%" align="right" />

```
AMR-Parsing
│   README.md
│
├───split-after-parsing
│       test_gpu.ipynb
│       train_gpu.ipynb
│       validation_gpu.ipynb
│
└───split-before-parsing
        test-gpu-nltk-splitter.ipynb
        train-gpu-nltk-splitter.ipynb
        validation-gpu-nltk-splitter.ipynb
```

Our work explores how there's a difference between two separate approaches for encoding AMR graphs and feeding them into LLM-models. We explicitly observe how `split-after-parsing` has longer context lengths through stronger and consistent conferences. We demonstrate the difference pictographically above. 

The AMR-Parsing directory is dedicated to AMR parsing and includes meticulously crafted code and Jupyter notebooks. Here, you will find notebooks that explore distinct AMR parsing techniques, both `before` and `after` splitting. Ensure that you configure the necessary paths within the notebooks before running them to seamlessly integrate this functionality into your workflow.

## [AMR-Pretraining](/AMR-Pretraining)
```
AMR-Pretraining
│   pre-training-legalbert.ipynb
│   README.md
```

Navigate to the AMR-Pretraining directory for resources related to pre-training AMR models using LegalBERT. The star of this section is the `pre-training-legalbert.ipynb` Jupyter notebook, guiding you through the process of pre-training LegalBERT with AMR data. Prior to execution, make sure to modify the specified path within the notebook for optimal results.

## [AMR-finetuned-models](/AMR-finetuned-models)
```
AMR-finetuned-models
│   distilroberta-han-pretrained.ipynb
│   distilroberta-han.ipynb
│   legalbert-han-pretrained.ipynb
│   legalbert-han.ipynb
│   README.md
```

In the AMR-finetuned-models directory, you'll discover Jupyter Notebook files dedicated to fine-tuning and utilizing various models tailored for AMR tasks. This includes notebooks for models like DistilRoBERTa and LegalBERT. Each notebook provides clear instructions, encompassing details on configuring paths and executing the necessary steps to enhance your AMR-related work.

## [Evaluation](/Evaluation)
```
Evaluation
│   evaluation-of-distilroberta-models.ipynb
│   evaluation-of-legalbert-models.ipynb
│   README.md
```

Delve into the Evaluation directory, where you'll find notebooks crafted for evaluating different models on specific datasets. This section includes notebooks for evaluating DistilRoBERTa models and LegalBERT models. Comprehensive instructions within each notebook guide you through loading models, setting paths, and executing precise evaluation tasks to ensure robust and accurate results.

For detailed instructions on running the notebooks and performing specific AMR tasks, navigate to the respective directories and refer to the README files provided.

## Ackowledgement

The AMR Evaluation for Legal Judgment Prediction repository is the official implementation of the Bachelor Thesis conducted under the supervision of Dr. Professor Daniel Martin Katz. This comprehensive toolkit is designed to facilitate research and development on Abstract Meaning Representation (AMR) tasks, specifically tailored for legal judgment prediction.
