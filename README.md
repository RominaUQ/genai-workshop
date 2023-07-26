# genai-workshop

This workshop is aimed to familarise users with the foundations of deploying and working with LLMs on Amazon SageMaker.

There are three labs in this workshop

Lab 1:
Contains 4 sections
Section 1: a guide to show you how simply deploy LLMs from SM jumpstart UI
Section 2: demonstrates how to user Hugging face Deep Learning Container (DLC) to deploy modles on SageMaker
Section 3: demonstrates zero shot prompt with Flan_T5_XXL model to extract the information user need ( in this scenario the intent or topic of a coversation)
Section 4: demonstrates additional promot engineering via zero shot learning that allows the user to pass on specific labels and ask the model to pick one of those classes ( useful for hierarchy of intents/topics or sub intent/topics for example)

Lab 2:
Walks you through some fundamental apis of langchain and how to usetilse them with SageMaker Models

Lab3: uses Lab 1 and Lab2 as a foundation to build and end to end RAG (Retreival Augmented Generation) application using Langchain and an LLM

