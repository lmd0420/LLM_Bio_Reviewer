# LLM_Bio_Reviewer

Team Members: Mingda Li, Utkarsh Mujumdar, Hsuan-Wen (Peggy) Wang

Advisor: Dr. Abhijit Mishra

## Introduction
This repository hosts the code and datasets for our research on utilizing Natural Language Processing (NLP) and Large Language Models (LLMs) in the peer review process for biomedical and healthcare research papers. Our work focuses on applying classic NLP techniques and advanced LLMs to improve the efficiency and effectiveness of peer reviewing.

## Repository Structure
- `data/`: Contains all the biology papers collected from OpenReview and their corresponding human reviews, along with preprocessed data for each task.
- `code/`: Includes subfolders for each sub-task in our research. These tasks encompass various stages of the peer review process, from pre-review analysis to post-review sentiment assessment.

## Dataset
Our dataset comprises a collection of biology papers and their reviews. This dataset has been carefully curated and preprocessed to facilitate research in NLP applications in peer review.

## Code
The `code/` directory is organized into several subfolders, each dedicated to a different aspect of our research:
1. **Before Review**: Implements topic segmentation to determine paper relevance.
2. **During Review**: Focuses on generating summaries and answering reviewer questions using LLMs.
3. **After Review**: Analyzes the tone of reviews through sentiment analysis.

## Usage
Detailed instructions on how to run and use the code for each sub-task are provided in their respective subfolders.

## Contributions
- **Dataset Creation**: Compilation of biology papers and their reviews, enhanced with LLM-generated summaries and review question answers.
- **Pre-Review Analysis**: Applying topic segmentation for relevance determination.
- **Review Assistance**: Using LLMs for generating summaries and answering review-specific questions.
- **Post-Review Analysis**: Sentiment analysis of review comments.

## Citation
Please cite our paper if you use our dataset or code: https://medium.com/@mingdali_76805/is-llm-a-good-peer-reviewer-experiments-on-biology-paper-3965aeec472d
