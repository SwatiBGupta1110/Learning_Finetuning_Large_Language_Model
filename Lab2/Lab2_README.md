# Finetuning Large Language Models - Lecture 2: Where finetuning fits In

## Overview

This README provides insights into the second lecture of the "Finetuning Large Language Models" course by Sharon Zhou. The focus of this lecture is on the crucial role of finetuning in the training process, specifically after the pre-training step. The transcript delves into the significance of pre-training, the utilization of unlabeled data, and the transition from a base model to a fine-tuned model.

## Key Points

### Pre-training: The Starting Point

- Pre-training precedes fine-tuning and involves training a model with random weights.
- The model begins with no knowledge of the world and learns through next token prediction.
- Unlabeled data, often sourced from the entire web, is used for self-supervised learning.
- The Pile dataset, created by EleutherAI, provides structured data for effective pre-training.

### Fine-tuning Essentials

- Fine-tuning follows pre-training to adapt the model for specific tasks.
- It transforms the base model, obtained from pre-training, into a specialized model.
- The process involves using both unlabeled and curated data, requiring less data than pre-training.
- Fine-tuning is a versatile tool for behavior change, gaining new knowledge, and improving model capabilities.

### Fine-tuning vs. Pre-training

- Fine-tuning is a step after pre-training, building on the knowledge gained.
- It requires less data and focuses on specific tasks, making it efficient for customization.
- Clarity about the task's objectives is crucial for successful fine-tuning.

### Behavior Change and Knowledge Gain

- Fine-tuning facilitates behavior change in the model, making it more consistent and focused.
- It helps the model gain new knowledge, correcting outdated information and learning specific topics.
- Tasks for fine-tuning can be categorized into text extraction and text expansion.

### Lab Recommendations for First-timers

1. Identify a task by prompt engineering a large language model.
2. Choose a task that the model performs moderately and gather 1000 input-output pairs for it.
3. Fine-tune a small language model on the collected data to observe performance improvements.

## Lab Demonstration

The lecture includes a lab where participants explore datasets used for pre-training and fine-tuning. The provided script guides through loading and visualizing these datasets, emphasizing structured data for fine-tuning tasks.

## Setup

Before engaging in the lab, ensure the necessary libraries, including HuggingFace, are installed. Follow the provided Python script to load and explore datasets for a hands-on experience.

---

**Note: Credit to the original owners — This script is part of the "Finetuning Large Language Models" course by Sharon Zhou at Lamini. All credits for the script go to the original creators and owners.**


