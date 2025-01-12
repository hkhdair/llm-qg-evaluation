# LLM-Based MCQ Generation and Evaluation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hkhdair/llm-qg-evaluation/blob/main/qg_eval.ipynb)

## Description
This project implements an automated system for generating and evaluating Multiple Choice Questions (MCQs) using Large Language Models (LLMs). It provides functionality to:

1. Generate high-quality MCQs from given context text
2. Evaluate generated MCQs based on multiple criteria:
   - Relevance
   - Clarity
   - Difficulty
   - Correctness

## Features
- Context-based MCQ generation using OpenAI's GPT models
- Comprehensive MCQ evaluation system
- Detailed scoring and justification for each evaluation criterion
- Pandas DataFrame output for easy analysis

## Requirements
- Python 3.11+
- OpenAI API key
- Required Python packages:
  - openai
  - python-dotenv
  - pandas

## Usage
1. Create a `.env` file with your OpenAI API key:
```env
OPENAI_API_KEY="your-api-key-here"

or if you open with Google Colab, don't forget to add your OpenAI key