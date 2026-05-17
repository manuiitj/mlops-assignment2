## MLOps Assignment 2 — HuggingFace Fine-tuning

## What This Project Does?
Fine-tunes a DistilBERT model to classify book reviews by genre
using the UCSD Goodreads dataset. Training is done on Kaggle GPU,
tracked with Weights & Biases, and the model is published on Hugging Face.

## Setup Instructions
1. Clone this repository
2. Install dependencies:
   pip install -r requirements.txt
3. Add your API keys as environment variables:
   - WANDB_API_KEY
   - HF_TOKEN
4. Run the notebook top to bottom

## Training Platform
Kaggle Notebook (free GPU T4)
- Kaggle Notebook: https://www.kaggle.com/code/manusinghg25ait2061/ml-ops2


## Results
| Metric    |   Score   |
|-----------|-----------|
| Accuracy  | 0.61438 |
| F1 Score  | 0.61275 |
| Eval Loss | 2.36346 |

## Links
- Hugging Face Model: https://huggingface.co/manuiitj/distilbert-goodreads-genres
- W&B Dashboard: https://wandb.ai/manu-singh-cms12-prom-iit-rajasthan/mlops-assignment2
- Kaggle Notebook: https://www.kaggle.com/code/manusinghg25ait2061/ml-ops2
