# Fine-Tuning-LLMs-using-LoRA

🚀 Fine-Tuning GPT-2 to Write Positive Movie Reviews with LoRA (Low-Rank Adaptation) 🎬

WHAT IS LoRA?
LoRA (Low-Rank Adaptation)LoRA is a parameter-efficient fine-tuning technique that allows you to adapt large pre-trained language models without updating all of their parameters.

How It Works?
Instead of modifying all the weights in a neural network (which is computationally expensive and memory-intensive), LoRA freezes the original pre-trained model weights and injects trainable low-rank decomposition matrices into each layer of the transformer architecture.

Ever wondered how to teach a Large Language Model (LLM) to develop a specific writing style — like a movie critic who always finds the silver lining?
In this project, I fine-tuned GPT-2 using LoRA (Low-Rank Adaptation) on positive reviews from the IMDB dataset to transform it into a positivity-focused film reviewer! 🍿✨
🧰 Tech Stack
Transformers & Datasets (Hugging Face): For the GPT-2 model and IMDB data
PEFT: Efficient parameter fine-tuning with LoRA
Accelerate: Smooth GPU training setup
🧠 Key Takeaway
With LoRA, we can fine-tune large models efficiently — even on modest hardware — and give them a specific personality or purpose.
