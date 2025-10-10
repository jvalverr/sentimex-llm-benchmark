# Spanish Political Sentiment Analysis of Social Media Data in the 2024 Mexican Elections

The growing influence of social media on electoral processes underscores the need for robust sentiment analysis methods capable of handling informal, noisy, and politically charged discourse. This challenge is particularly acute in Spanish, where resources and benchmarks remain limited compared to English. This study makes two main contributions:

1. We introduce a novel human-annotated corpus of 2,000 posts from Facebook, Instagram, X, and YouTube during the 2024 Mexican presidential elections. An annotation process was performed independently by multiple native speakers and consolidated into a reliable ground truth, ensures consistency across positive, negative, and neutral categories.
2. We propose an evaluation framework that benchmarks pre-trained transformer models, including BERT, BETO, RoBERTa, and pysentimiento, against large language models (LLMs) such as GPT-3.5, GPT-4o-mini, o1-mini, Llama-3, and Llama-3.1, under zero-shot and few-shot prompting. Results show that recent LLMs consistently surpass both pre-trained transformers and open-source alternatives, achieving stronger and more stable performance across platforms.
  
To support future research, we release both the annotated dataset and the complete evaluation results.
