# Unit 1 Project:  Smart Resume Parser 

Short project demonstrating practical NLP tasks using Hugging Face Transformers: NER, summarization, and zero-shot classification on a sample resume.

## Features
- Named Entity Recognition (NER) extraction
- Resume summarization (seq2seq)
- Zero-shot classification into skill domains
- Console-friendly reporting and confidence visualization

## Requirements
- Python (use the included virtualenv at `genai_env/` if desired)
- transformers
- torch

Suggested install:
```sh
pip install transformers torch
```

Note: Hugging Face model downloads may require a HF token for higher rate limits.

## How to run
1. Open the notebook [Project_Unit1_PES2UG23CS150.ipynb](Project_Unit1_PES2UG23CS150.ipynb) in Jupyter.
2. Run cells top-to-bottom. The notebook:
   - loads pipelines/models,
   - extracts entities,
   - generates a summary,
   - runs zero-shot classification,
   - prints a comprehensive report.

## License & Author
- Author: Chethan S (PES2UG23CS150)
- Use and modify for educational purposes.

