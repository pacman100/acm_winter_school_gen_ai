# Hands on session for the ACM Winter School focused on Generative AI

## Explore the Hugging Face Hub 
 - [Models](https://huggingface.co/models)
 - [Datasets](https://huggingface.co/datasets)
 - [Spaces](https://huggingface.co/spaces)
 - [Tasks](https://huggingface.co/tasks)
 - [Chat](https://huggingface.co/chat/)


## Module 1: Prompt Engineering
- We start by covering the fundamentals of Prompting. We utilize the `mistralai/Mistral-7B-Instruct-v0.2` open access model, which excels at following instructions. We demonstrate how to enable token streaming and employ chat templates.
- We dive into powerful prompting techniques like few-shot, chain-of-thought (CoT), Self Consistency, ReACT (Reason & Act), and Tree of Thoughts (ToT) with coding examples. We'll showcase a Breadth First Search based ToT example and Langchain tools for ReACT example.
- Explore JSON-only outputs, prompt chaining, and LLMs for evaluation. Plus, discover how to create a Gradio chatbot 🚀. Share your feedback and queries.

## Module 2: Question Answering Chatbot using Retrieval Augmented Generation (RAG) 

![RAG Conversation Assistant](https://drive.google.com/uc?id=1uZppqKTPFt0zfrTsA-76AGRfPcp-PY-a)

- We will see how Langchain makes it easy as a framework to bring together most of the steps aboves in simple APIs. We will be using open source models from 🤗 Hub, Langchain and Chroma vector DB.