# Finetuning Large Language Models - Lecture 3: Instruction Tuning

## Overview

This README provides an overview of the third lecture in the "Finetuning Large Language Models" course by Sharon Zhou. The focus of this lecture is on instruction fine-tuning, a variant of fine-tuning that transformed GPT-3 into ChatGPT, giving it powerful chatting capabilities. The lecture covers the concept of instruction fine-tuning, its importance in turning models into chatbots, and the impact it had on increasing AI adoption.

## Key Concepts

### Instruction Fine-tuning

- Instruction fine-tuning is a specific type of fine-tuning that teaches the model to follow instructions and behave more like a chatbot.
- It is a crucial step in turning models, such as GPT-3, into effective chat-oriented AI systems.
- The method dramatically increased AI adoption, making models accessible to millions of users.

### Dataset for Instruction Following

- Use readily available datasets for instruction following, such as FAQs, customer support conversations, or Slack messages.
- Convert existing data into a question-answer format or instruction-following format using prompt templates.
- Alpaca, a technique from Stanford, uses ChatGPT to convert data into instruction-following format.

### Benefits of Fine-tuning

- Fine-tuning introduces new behaviors to the model, allowing it to generalize knowledge learned during pre-training to specific tasks.
- Models can answer questions about topics not explicitly provided in the fine-tuning dataset, such as code-related queries.

### Steps of Fine-tuning

1. **Data Prep:** Prepare the data for instruction fine-tuning, tailoring it to the specific task.
2. **Training:** Train the model on the prepared data.
3. **Evaluation:** Evaluate the model's performance and iterate on data prep for improvements.

## Lab Demonstration

The lecture includes a lab where participants explore the Alpaca dataset for instruction tuning. The demonstration involves comparing models that have undergone instruction fine-tuning with those that haven't. Models of varying sizes, including a 70 million parameter model, are explored.

### Lab Steps

1. Import necessary libraries.
2. Load the instruction-tune dataset, particularly the Alpaca dataset.
3. Explore examples from the dataset, which is more structured than simple question-answer pairs.
4. Utilize prompt templates to convert data into instruction-following format.
5. Run models, comparing instruction-tuned and non-instruction-tuned models of various sizes.

### Model Comparison

- Compare models, including Llama 2 (not instruction-tuned), instruction-tuned models, and ChatGPT (a large model).
- Observe differences in behavior and responses, emphasizing the impact of instruction fine-tuning.

## Tokenizer and Data Prep

The README briefly mentions the upcoming content related to tokenization and data preparation for training. This will be covered in detail in subsequent labs.
