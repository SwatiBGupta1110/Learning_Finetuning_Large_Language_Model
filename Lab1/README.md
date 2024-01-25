# 01 Why Fine-Tuning Lab Student

## Overview

This repository contains a Python script, "01_Why_finetuning_lab_student," for comparing the output of fine-tuned and non-fine-tuned language models using the lamini and llama libraries. The script utilizes the BasicModelRunner class to assess the performance of two models - one non-fine-tuned (meta-llama/Llama-2-7b-hf) and one fine-tuned (meta-llama/Llama-2-7b-chat-hf). Additionally, a comparison with ChatGPT is provided.

# Notes:
# Finetuning Large Language Models

## Overview

This repository contains a Python script as part of a short course on finetuning large language models (LLMs). The course, offered by Sharon Zhou, Co-Founder and CEO of Lamini, aims to provide insights into the significance of finetuning, its applications, and a comparative analysis with prompt engineering. The provided Python script showcases a lab comparing the outputs of a fine-tuned LLM with a non-fine-tuned model.

## Important Notes from Transcript

### Why Fine-tuning LLMs

- Understand the reasons behind fine-tuning, its purpose, and how it compares to prompt engineering.
- Explore a lab comparing a fine-tuned model with a non-fine-tuned one.

### Fine-tuning Overview

- Fine-tuning involves specializing general-purpose models (e.g., GPT-3) for specific use cases (e.g., ChatGPT or GitHub co-pilot).
- Analogy: General models are like primary care physicians; fine-tuned models are specialists like cardiologists or dermatologists.
- Fine-tuning allows models to learn from more data, upgrading from a general-purpose model to a specialized one.

### Benefits of Fine-tuning

- Enables customization to specific use cases.
- Enhances model consistency, reducing hallucinations and improving output accuracy.
- Allows steering the model's behavior for more desirable and tailored results.

### Comparison with Prompt Engineering

- Prompting is the practice of inputting queries to modify model outputs.
- Pros of Prompting: No need for data to start, lower upfront cost, and minimal technical knowledge required.
- Cons: Limited data input, issues with handling large datasets, and challenges with hallucination correction.

### Fine-tuning vs. Prompting

- Fine-tuning: Can handle almost unlimited data, corrects incorrect information, and provides better control over costs and latency.
- Prompting: Great for generic use cases, quick starts, and prototypes but may lack precision for specific applications.

### Fine-tuning for Performance

- Improves model consistency, reliability, and moderation capabilities.
- Allows customization of responses to maintain a consistent user experience.

### Fine-tuning for Privacy

- Conducting fine-tuning in a Virtual Private Cloud (VPC) or on-premise prevents data leakage and breaches.
- Ensures data safety, especially when dealing with sensitive information.

### Fine-tuning for Cost Optimization

- Offers cost transparency by reducing the cost per request.
- Provides greater control over costs, uptime, and latency.

### Tools and Technologies for Fine-tuning

- Utilizes Python libraries, including PyTorch (Meta), HuggingFace, and Llamanai.
- Highlights LLAMA library's high-level interface for easy model training with minimal code.

### Lab Demonstration

- Compares the outputs of a non-fine-tuned model (LLAMA2) with a fine-tuned model (LLAMA2Chat) using various queries.
- Illustrates the improved performance of the fine-tuned model in generating coherent and relevant responses.

### Next Steps

- The next lab will delve into the fine-tuning process and its placement in the overall training process.

---

**Note: Credit to the original owners — This script is part of the "Finetuning Large Language Models" course by Sharon Zhou at Lamini. All credits for the script go to the original creators and owners.**



## Setup

Before running the script, make sure to set the lamini API URL and key using the environment variables `POWERML__PRODUCTION__URL` and `POWERML__PRODUCTION__KEY`. Replace `<your_lamini_api_url>` and `<your_lamini_api_key>` with your actual lamini API URL and key.

```bash
export POWERML__PRODUCTION__URL=<your_lamini_api_url>
export POWERML__PRODUCTION__KEY=<your_lamini_api_key>

##Usage

1. Clone the Repository

git clone https://github.com/your-username/01_Why_finetuning_lab_student.git
cd 01_Why_finetuning_lab_student


2. Install Dependencies

pip install -r requirements.txt


3. Run the Script

python 01_Why_finetuning_lab_student.py


4. Review Outputs
Explore the model responses for different queries related to dog training, Mars, and a simulated Amazon customer service interaction.
---

## Example Queries
"Tell me how to train my dog to sit"
"What do you think of Mars?"
"Taylor Swift's best friend"
A simulated Amazon customer service interaction
Model Details
Non-Fine-Tuned Model: meta-llama/Llama-2-7b-hf
Fine-Tuned Model: meta-llama/Llama-2-7b-chat-hf

## ChatGPT Comparison
The script includes a comparison with ChatGPT for the query "Tell me how to train my dog to sit." The provided response from ChatGPT is documented for reference.

Feel free to modify the queries and explore the differences in responses between the models.


