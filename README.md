# Bias Detection and Mitigation in Large Language Models.

## Technologies Used
[![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://www.python.org/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FF9900?style=for-the-badge)](https://huggingface.co/docs/transformers/en/model_doc/bert)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

## Overview:
Large language models (LLMs) have revolutionized the field of natural language processing, enabling remarkable capabilities in text generation, question answering, and language understanding. However, these powerful models, trained on vast amounts of data, can unintentionally learn and perpetuate societal biases present in their training corpus. These biases can manifest as unfair or discriminatory patterns in the model’s outputs, potentially leading to harmful outcomes and undermining trust in AI systems.

## Problem Statement
Large Language models are trained with a large amount of unsupervised data. If the training data used for LLMs contain unrepresentative samples or biases, naturally, the model will inherit and learn these biases. These can result in potential bias when the end user uses these biased models.

This project aims to systematically identify, quantify, and mitigate the biases present in Large Language Models. By exploring various aspects of bias in LLMs, we seek to enhance the fairness and inclusivity of these models, ultimately improving their reliability and trustworthiness. The key objectives of this project are as follows:
<ol>
  <li><b>Bias Identification:</b> Analyze model outputs to detect and categorize types of biases, such as gender, racial, and cultural biases.</li>
  <li><b>Bias Quantification:</b> Compare the performance of different LLMs to understand the variations in learned biases.</li>
  <li><b>Bias Mitigation Strategies:</b>  Evaluate various strategies to minimize and mitigate biases, including data preprocessing, model fine-tuning, and post-processing techniques.</li>
</ol>

## Methodology
In this study, we will be exploring three major fronts of bias and mitigation in large language models. For each of these fronts, we will be following certain methodologies and experiments that would give us further insight into the data, the behavior of the models, and the patterns being used to generate this biased text.
<ol>
  <li>Scrutinize: Finding out if there is any bias.
  
To detect bias, the methodology involves crafting careful prompts to trigger biased responses from language models, such as using gender stereotypes or sociopolitical stances. These prompts are then evaluated across multiple models, with generated outputs manually inspected for signs of unfair bias.</li>
  <li>Quantify: To quantify the degree of bias present. 
    
The methodology involves using benchmark datasets like CrowS-Pairs and BOLD that are carefully curated to test for specific biases like gender, profession, and stereotype associations. Pre-trained language models are evaluated on these datasets by computing metrics such as toxicity scores that measure unsafe/offensive content and bias scores that quantify stereotypical vs. anti-stereotypical associations using techniques like likelihood ratios or log probabilities</li>
  <li>Mitigate: Provide strategies to minimize, mitigate, and counter the bias present.
    
The key strategies to mitigate biases in large language models involve data augmentation and optimization techniques. Counterfactual data augmentation (CDA) aims to reduce biases by generating counterfactual examples that challenge stereotypical assumptions during fine-tuning. Toolkits like AI Fairness 360 provide a range of pre-processing, in-processing, and post-processing methods to modify the training data, learning procedure, or model outputs to align with fairness constraints.</li>
</ol>

## Results

## Conclusion
