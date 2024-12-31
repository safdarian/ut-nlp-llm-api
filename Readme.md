# UT NLP LLM API Workshop

This repository contains the materials and Jupyter Notebook for the **"Hands-On Introduction to LLM APIs"** workshop, conducted as part of the NLP course at the University of Tehran in Fall 2024. The workshop introduces students to using **Large Language Model (LLM) APIs** with an emphasis on **tool use** and **structured outputs**. We focus on building efficient prompting strategies and applying LLMs for practical tasks like **Text-to-SQL**.

---

## Workshop Overview

This workshop, designed for students of the NLP course at the University of Tehran, focused on the following:
- **Setting up and using LLM APIs**: Practical implementation with an introduction to various LLM API services.
- **Tool Use in LLMs**: Exploring the use of additional tools alongside LLMs to solve real-world tasks. This includes **external databases** and **APIs** for enhancing the functionality of LLM-based systems.
- **Structured Outputs for Efficient Prompting**: Learning how to craft better prompts to extract structured data.
- **Case Study: Text-to-SQL**: Applying the learned concepts to implement a Text-to-SQL pipeline using LLM APIs.

---

## Files in This Repository

- **`NLP_Workshop3.ipynb`**: The Jupyter Notebook from the workshop, containing:
  - Practical examples on using LLM APIs.
  - Step-by-step instructions for implementing various methods for **Text-to-SQL** task.
  - Exercises on efficient prompting and structured output techniques.
  - Use of external **tools** (e.g., function calls) integrated with LLMs to enhance the functionality.

---

## Key Concepts Covered

- **LLM API Setup and Use**: Setting up LLM APIs and making API calls.
- **Efficient Prompting with Tools**: Exploring how to use additional tools (e.g., databases, external APIs) in conjunction with LLMs to improve results.
- **Structured Outputs**: Generating structured responses from LLMs and using them in meaningful ways, such as converting natural language queries into SQL.
- **Building Language Agents**: Designing agents that can combine multiple tools and outputs to solve complex tasks.

---

## How to Use This Repository

1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/ut-nlp-llm-api.git
    cd ut-nlp-llm-api
    ```

2. Install the required dependencies (if applicable). Create a virtual environment if needed:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook NLP_Workshop3.ipynb
    ```

4. Follow the instructions in the notebook to explore the examples and implement the exercises, focusing on tool use and structured output generation.

---

## Prerequisites

To run the notebook, you need:
- **Python 3.8+**
- **Jupyter Notebook or Jupyter Lab**
- The following Python libraries (install using `pip install` if not already installed):
  - `openai` (for using OpenAI's API)
  - `pandas` (for working with data)
  - `sqlalchemy` (for working with databases in the Text-to-SQL case study)
  - Additional libraries or tools, as needed for specific tasks

You can install all dependencies via:
```bash
pip install -r requirements.txt
