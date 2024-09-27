# SDoH Extractor

## Overview

The SDoH Extractor project focuses on leveraging natural language processing (NLP) techniques to identify and extract social determinants of health (SDoHs) from clinical notes. By transforming unstructured clinical data into structured formats, this project aims to improve the understanding of factors influencing health and well-being in individuals and populations.

## Description

Social determinants of health (SDoHs) encompass the conditions under which individuals are born, grow, live, work, and age. These determinants—including economic stability, education, social support, healthcare access, and behaviors—significantly influence health outcomes. Unfortunately, much of this vital information is often buried within clinical notes rather than being represented in standardized formats.

This project utilizes a large language model to extract adverse SDoHs from clinical note sentences. By categorizing each sentence into predefined SDoH categories—such as EMPLOYMENT, HOUSING, PARENT, RELATIONSHIP, and TRANSPORTATION—the model aims to provide actionable insights for health data science.

The extraction process involves:
1. Training a model on example sentences provided in `train.csv`.
2. Testing the model's performance with `test.csv`.
3. Generating outputs in `sdoh-categorization.md` and `sdoh-categorization.csv`.
4. Including `original.csv` for comparative analysis against the original suggested classifications.

## Data

The data used in this project consists of the following CSV files:

- **train.csv**: Contains example sentences labeled with their corresponding SDoH categories for training the model.
- **test.csv**: Used to evaluate the model’s performance on unseen data.
- **sdoh-categorization.md**: Contains the categorized output of sentences from the clinical notes.
- **original.csv**: Provides a full list of sentences along with their original suggested classifications for comparative purposes.

## Citation

Special thanks to Dr. Yejin Kim for assigning this project and providing the invaluable resources, guidance, and support.
