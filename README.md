# Falcon 7B Midjourney Prompt Generation

This notebook is designed to fine-tune the Falcon 7B model to generate prompts for the Midjourney platform.

## Installation

Before running the notebook, ensure you have installed the required packages:

```bash
pip install -U pip
pip install bitsandbytes==0.39.0
pip install torch==2.0.1
pip install -U git+https://github.com/huggingface/transformers.git
pip install -U git+https://github.com/huggingface/peft.git
pip install -U git+https://github.com/huggingface/accelerate.git
pip install datasets==2.12.0
pip install loralib==0.1.1
pip install einops==0.6.1

```
# Usage
To use the notebook:

1.Log in to Hugging Face using notebook_login().

2.Load the Falcon model and tokenizer with the specified configurations.

3.Fine-tune the model on your dataset in same format as the dataset provided.

4.Save and push the trained model to the Hugging Face Hub.


# Fine-tuning
The notebook includes cells for fine-tuning the model with PEFT (Parameter Efficient Fine-tuning) and Lora (Low-Rank Adaptation).


# Testing
After fine-tuning, you can test the model’s prompt generation capabilities with your own prompts.

# Contributing
Contributions to improve the notebook or fine-tuning process are welcome.
