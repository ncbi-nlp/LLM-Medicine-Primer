# LLM-Medicine-Tutorial-Internal

## Introduction
This tutorial is an extension of concepts and recommendations outlined in the paper "A Systematic Approach to Utilizing Large Language Models in Medicine". Large language models (LLMs) represent a transformative class of artificial intelligence (AI) tools that can be used for a variety of tasks. Here, we provide example scripts related to a relevant healthcare task - clinical trial matching - and demonstrate important concepts including temperature, chain-of-thought prompting, few-shot learning, retrieval-augmented generation (RAG), and data preparation for fine-tuning.

![Unable to load image](images/fig1.png)

Figure 1. Overview of the proposed systematic approach to utilizing large language models in medicine.

## Formulating the task
When defining a medical need that may be addressed by an LLM, a user must first understand the core capabilities of LLMs. We classify LLM capabilities into five broad categories: structurization, summarization, translation, knowledge & reasoning, and multi-modal data processing.

![Unable to load image](images/fig2.png)

Figure 2. An overview of five common task formulations enabled by LLMs in medicine.

## Choosing a large language model
Users should choose an appropriate LLM based on the task characteristics. We categorize these characteristics into four main categories: model interface, data modality, context length, and medical capability.

![Unable to load image](images/fig3.png)

Figure 3. Considerations for choosing an LLM.

A diversity of LLMs have been evaluated for their medical capability. Below, we summarize several popular LLMs.

Table 1. Characteristics of different LLMs, sorted by the best reported MedQA-USMLE (4 options) score. T: text; I: image; V: video; A: audio.

## Prompt engineering
Once a user has formulated a task and selected an appropriate LLM, they must carefully consider the prompt (input content) given to the model. Additionally, users may consider implementing fine-tuning techniques to improve the performance of their model.

![Unable to load image](images/fig4.png)

Figure 4. An overview of prompt engineering and fine-tuning techniques.

Many techniques have been used within prompt engineering. Common methods includes few-shot learning, tool learning, chain-of-thought prompting, retrieval-augmented generation, and fine tuning.

Table 2. Characteristics of different methods to use LLMs.

## Case studies

Before exploring the example scripts, we also suggest reviewing the following studies which leverage large language models for various healthcare tasks.

Table 3. Representative case studies of utilizing large language models in medicine.

## Configuration
To execute this example code in a Google Colab environment or within your own terminal, one must first set up the OpenAI API either directly through OpenAI or through Microsoft Azure. Here we use Microsoft Azure because it is compliant with Health Insurance Portability and Accountability Act (HIPAA). Ensure that an appropriate PROJECT_HOME path has been set, and please set the enviroment variables accordingly:
```python
export OPENAI_ENDPOINT=YOUR_AZURE_OPENAI_ENDPOINT_URL
export OPENAI_API_KEY=YOUR_AZURE_OPENAI_API_KEY
```
