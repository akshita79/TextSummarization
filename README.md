# Text Summarization using pre-trained models

This project aims to implement text summarization using pre-trained models from the Hugging Face Transformers library. Text summarization is the process of generating a concise and coherent summary of a text document while preserving its most important information. We employ various pre-trained models and evaluate their performance using metrics such as ROUGE scores and BLEU scores. Additionally, we utilize the TOPSIS method to determine the best-performing model based on multiple evaluation metrics.


## Installation



```bash
pip install transformers
```



## Work flow
## 1. Data Collection and Preprocessing:
Gather text data for summarization tasks.
Preprocess the data, including tokenization, cleaning, and splitting tasks into training/validation/test sets.
## 2. Model Selection:
Choose from various pre-trained models available in the Hugging Face Transformers library.
Experiment with models suitable for text summarization tasks, considering factors such as model architecture and size.
## 3. Training and Evaluation:
Fine-tune selected pre-trained models on the summarization task using appropriate datasets.
Evaluate model performance using established metrics such as ROUGE scores and BLEU scores.
Calculate various metrics to assess the quality of the generated summaries.
## 4. Model Comparison:
Utilize the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to compare models based on multiple evaluation metrics.
Determine the best-performing model based on the calculated scores and metrics.


## Topsis 

![Workflow-of-the-TOPSIS-method](https://github.com/akshita79/TextSummarization/assets/92212914/c2bd3a56-ffbd-477a-83cf-a977a4d36144)
