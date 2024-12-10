# LAB2: Fine-Tuning LLM

This repository contains the work for **LAB2: Fine-Tuning LLM**, focusing on fine-tuning large language models (LLMs) and evaluating their performance. All related work is available in the included notebooks, and you can access the Hugging Face interface for testing the fine-tuned model at the following link:  
`.......`

## Evaluation Metrics

We use **BERTScore** to evaluate the semantic similarity between generated text and reference text. For tasks like translation, you could use metrics like **BLEU score**, which measures sequence overlap and is more suitable for such applications.

## Fine-Tuning Methodologies

**Model-centric approaches** involve directly improving the model by tuning hyperparameters, optimizing learning rates, or experimenting with different pre-trained architectures to identify the best fit for the task. Additionally, optimizing the model for CPU inference using techniques like quantization can significantly enhance efficiency. 

**Data-centric approaches** focus on enhancing the quality and relevance of training data. For instance, task-specific datasets such as those for Python script generation or language translation can be used for specialized fine-tuning. Data augmentation and preprocessing are also essential for improving generalization and robustness, enabling the model to perform better on unseen data.

## Improving Model Performance

Combining both approaches can yield significant improvements. By systematically experimenting with both model-centric techniques like architecture changes and data-centric strategies like sourcing domain-specific datasets, you can achieve higher task-specific performance. Demonstrating quantitative improvements through metrics like BERTScore or BLEU will showcase the success of these methods.

## Future Work

Potential future work includes testing additional open-source models for better CPU inference, exploring new evaluation metrics, and building a more intuitive user interface for real-world deployment.
