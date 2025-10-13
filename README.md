# LangChain Academy Assignment

This repo has my work from LangChain Academy.  
After each video I note what I learned, the tweak I made, and link the code.

## Progress

### Module 1  

**Video 1**  
- Learned basics of LangChain.  
- Tweaked system prompt.  


**Video 2**  
- Learned retrievers for RAG.  
- Changed similarity search settings.  
 

**Video 3**  
- Learned OpenAI integration.  
- Used `gpt-4o-mini` instead of default.  
  

---

### Module 2  

**Lesson 1**  
- Learned about LangChain tools and how they extend LLM functionality.  
- Added a custom tool for testing.  


**Lesson 2**  
- Learned about agents and how they use tools to decide actions.  
- Tweaked the agent prompt to make it more direct.  
  

**Lesson 3**  
- Learned how to add memory to an agent for conversation.  
- Changed memory type from Buffer to SummaryMemory.

---

### Module 3  

**Lesson 1: Playground Experiments**

**Summary:**
This lesson introduced me to using the LangSmith Playground as a fast way to experiment with different prompt templates instead of relying on fixed, hardcoded ones. I explored how easily one can compare the outputs of multiple LLMs on a given dataset, testing various configurations and observing differences in their behavior.

Source File:
- https://github.com/langchain-ai/intro-to-langsmith/blob/661952bca6c5196a8d60c5a3d64448206ca07ba4/notebooks/module_3/playground_experiments.ipynb

Changes Made:
I personalized the notebook by replacing the default questions with general knowlege questions like the capital off the country ones and increased the temperature settings.


**LESSON 2:-Prompt Engineering**  
In this lesson, I learnt how to connect prompts stored in LangSmith with a Retrieval-Augmented Generation (RAG) pipeline. The notebook shows how a prompt can be pulled directly from LangSmith and used in the application instead of writing it manually. We here used the tracing feature using @traceable to see how each step in the chain runs and how data flows from retriever to model.This is honestly far more better way.

Source File:-
-https://github.com/langchain-ai/intro-to-langsmith/blob/661952bca6c5196a8d60c5a3d64448206ca07ba4/notebooks/module_3/prompt_hub.ipynb

- Changes/ Examples here i tweaked with:-
- Made the dataset to focus on Technology and Global Challenges (AI, climate change, renewable energy).
- Added traceable decorators to check the performance of each function.
- Tested the RAG app with different questions related to technology and tracing in LangSmith.
  

**LESSON 3: Prompt Hub**  
This notebook demonstrates how to connect and use LangSmith Prompts with both LangChain and the OpenAI API.
It shows how to pull prompts directly from LangSmith, invoke them to get structured outputs, and even create and test new multilingual prompt templates.

Source File:
- https://github.com/langchain-ai/intro-to-langsmith/blob/661952bca6c5196a8d60c5a3d64448206ca07ba4/notebooks/module_3/prompt_engineering_lifecycle.ipynb


- EXAMPLES THAT I HAVE TAKEN HERE:->

- What caused the French Revolution?
- When did World War II begin?
- What were the causes of the American Civil War?
- Added a Spanish-language historical assistant that provides responses in Spanish.
- Experimented with prompt templates and RAG-style structure for consistency.
