# LLM-Medicine-Tutorial-Internal

## Introduction
This tutorial is meant to outline some of the basic commands and coding structures used when leveraging large language models (LLMs) in medicine. LLMs can be used for a variety of tasks such as structurization, summarization, translation, knowledge & reasoning, and multi-modal processing. Here, we provide example scripts designed for summarization and knowledge & reasoning. We also show the importance of LLM concepts like temperature and few-shot learning.

## Configuration
To execute this example code in a Google Colab environment or within your own terminal, one must first set up the OpenAI API either directly through OpenAI or through Microsoft Azure. Here we use Microsoft Azure because it is compliant with Health Insurance Portability and Accountability Act (HIPAA). Ensure that an appropriate PROJECT_HOME path has been set, and please set the enviroment variables accordingly:
```python
export OPENAI_ENDPOINT=YOUR_AZURE_OPENAI_ENDPOINT_URL
export OPENAI_API_KEY=YOUR_AZURE_OPENAI_API_KEY
```
