# SDoH Extractor

![image](https://github.com/user-attachments/assets/20ad3cf5-cc9e-49b9-b548-eb91597e1ebd)

## Overview

The SDoH Extractor project focuses on leveraging natural language processing (NLP) techniques to identify and extract social determinants of health (SDoHs) from clinical notes. By transforming unstructured clinical data into structured formats, this project aims to improve the understanding of factors influencing health and well-being in individuals and populations.

## Description

Social determinants of health (SDoHs) encompass the conditions under which individuals are born, grow, live, work, and age. These determinants—including economic stability, education, social support, healthcare access, and behaviors—significantly influence health outcomes. Unfortunately, much of this vital information is often buried within clinical notes rather than being represented in standardized formats.

This project utilizes a large language model to extract adverse SDoHs from clinical note sentences. By categorizing each sentence into predefined SDoH categories—such as EMPLOYMENT, HOUSING, PARENT, RELATIONSHIP, and TRANSPORTATION—the model aims to provide actionable insights for health data science.

The extraction process involves:
1. Training a model on example sentences provided in 'train.csv'.
2. Testing the model's performance with 'test.csv'.
3. Generating outputs in 'sdoh-categorization.md'.
4. Including 'original.csv' for comparative analysis against the original suggested classifications by Marco Guevara. Reference #3.

## Data

The data used in this project consists of the following CSV files:

- **train.csv**: Contains example sentences labeled with their corresponding SDoH categories for training the model.
- **test.csv**: Used to evaluate the model’s performance on unseen data.
- **sdoh-categorization.md**: Contains the categorized output of sentences from the clinical notes.
- **original.csv**: Provides a full list of sentences along with their original suggested classifications for comparative purposes.

## Citation

Special thanks to Dr. Yejin Kim for assigning this project and providing invaluable resources, guidance, and support.

Guevara, M., Chen, S., Thomas, S. et al. Large language models to identify social determinants of health in electronic health records. *npj Digit. Med*. 7, 6 (2024). https://doi.org/10.1038/s41746-023-00970-0

Hugging Face. (n.d.). *SHADR dataset*. Hugging Face. https://huggingface.co/datasets/m720/SHADR

We Care TLC. (2023). *Social determinants of health* [Image]. https://wecaretlc.com/wp-content/uploads/2023/03/social-determinants-of-health-visual-1024x654.png
