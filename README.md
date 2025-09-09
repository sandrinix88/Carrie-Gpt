### Carrie GPT – A Persona-Based Conversational Agent

Inspired by Sex and the City, this project generates responses in the voice of Carrie Bradshaw using GPT-2 Medium fine-tuned with LoRA and integrated with RAG.

<img src="https://i.pinimg.com/1200x/7c/e5/98/7ce59868bbf1f90c850513b7060cebf3.jpg" alt="Carrie Inspiration" width="300"/>

___
### Project Overview

Carrie GPT is a persona-based chatbot designed to respond like Carrie Bradshaw. The system combines:

GPT-2 Medium: Base language model.

LoRA (Low-Rank Adaptation): Efficient fine-tuning for personality-specific responses.

RAG (Retrieval-Augmented Generation): Adds context from a curated script dataset for coherent, context-aware replies.

The goal is to explore NLP techniques in persona-based conversational AI while demonstrating practical fine-tuning and retrieval strategies.
___
### Features

Generates Carrie-style responses to user inputs.

Maintains consistent persona across multiple turns.

Can retrieve relevant context from a script-based dataset for more accurate replies.

Lightweight fine-tuning with LoRA reduces resource requirements.
__
### Clone the repository

`git clone https://github.com/sandrinix88/carrie-gpt.git
cd carrie-gpt`

### Install dependencies
`pip install -r requirements.txt`
___
### Dataset

Curated from Sex and the City scripts.

Preprocessed to maintain dialogue structure and character-specific phrases.

Used for RAG context retrieval during conversation.
___
### Fine-Tuning with LoRA

GPT-2 Medium base model.

LoRA reduces the number of trainable parameters for efficient fine-tuning.

Scripts used as training data to maintain Carrie's voice.

| User Input                             | Carrie GPT Response                                                                                          |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| “What do you think about dating apps?” | “Darling, dating apps are like choosing shoes… some fit, some hurt, and some just look good on Instagram.”   |
| “I’m nervous about my first date.”     | “Oh honey, nerves are proof you care… just remember to bring your wit and a little champagne in your heart.” |

### Skills Demonstrated

NLP & Conversational AI: GPT-2, RAG pipelines, LoRA fine-tuning

Data Processing: Dataset curation, script preprocessing

Python & Libraries: PyTorch, Hugging Face Transformers
___
### Potential Improvements

Expand dataset with additional dialogue sources.

Add evaluation metrics for persona consistency and response coherence.

Deploy as a web demo with Gradio or Streamlit.
___

### License

MIT License

