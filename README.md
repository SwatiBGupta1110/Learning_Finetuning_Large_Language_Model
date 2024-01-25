# 01 Why Fine-Tuning Lab Student

## Overview

This repository contains a Python script, "01_Why_finetuning_lab_student," for comparing the output of fine-tuned and non-fine-tuned language models using the lamini and llama libraries. The script utilizes the BasicModelRunner class to assess the performance of two models - one non-fine-tuned (meta-llama/Llama-2-7b-hf) and one fine-tuned (meta-llama/Llama-2-7b-chat-hf). Additionally, a comparison with ChatGPT is provided.

## Setup

Before running the script, make sure to set the lamini API URL and key using the environment variables `POWERML__PRODUCTION__URL` and `POWERML__PRODUCTION__KEY`. Replace `<your_lamini_api_url>` and `<your_lamini_api_key>` with your actual lamini API URL and key.

```bash
export POWERML__PRODUCTION__URL=<your_lamini_api_url>
export POWERML__PRODUCTION__KEY=<your_lamini_api_key>

## Usage

1. Clone the Repository

git clone https://github.com/your-username/01_Why_finetuning_lab_student.git
cd 01_Why_finetuning_lab_student


2. Install Dependencies

pip install -r requirements.txt


3. Run the Script

python 01_Why_finetuning_lab_student.py


4. Review Outputs
Explore the model responses for different queries related to dog training, Mars, and a simulated Amazon customer service interaction.

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

## About the Short Course

This Python script is part of the short course "Finetuning Large Language Models" offered by Sharon Zhou, Co-Founder and CEO of Lamini. Sharon is also an instructor for the GANs Specialization and How Diffusion Models Work.

### Course Objectives

Upon completion of the course, we will gain the following skills:

- Understand when to apply finetuning on Large Language Models (LLMs).
- Prepare your data for finetuning.
- Train and evaluate an LLM on your data.

### Finetuning Overview

With finetuning, you can take your own data to train the model on it and update the weights of the neural nets in the LLM. This process allows you to change the model compared to other methods like prompt engineering and Retrieval Augmented Generation. Finetuning enables the model to learn style, form, and can update the model with new knowledge to improve results.

---

**Credit to the original owners: This script is part of the "Finetuning Large Language Models" course by Sharon Zhou at Lamini. All credits for the script go to the original creators and owners.**

---
