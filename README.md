# Parallel Workflows with LangGraph

This repository contains a pair of example notebooks that demonstrate how to build and run state-based workflows with LangGraph.

## What is included?

- [employee_analytics_non_llm.ipynb](employee_analytics_non_llm.ipynb)  
  A non-LLM workflow that processes employee data to compute yearly salary, bonus amount, project evaluation status, and a final summary.

- [essay_workflow_llm.ipynb](essay_workflow_llm.ipynb)  
  An LLM-powered workflow that evaluates an essay across multiple dimensions such as language quality, depth of analysis, and clarity, then combines the results into an overall review.

## Features demonstrated

- Building state graphs with LangGraph
- Connecting multiple nodes in a workflow
- Running parallel branches and aggregating their outputs
- Using structured LLM responses for evaluation tasks

## Prerequisites

- Python 3.10 or newer
- Jupyter Notebook or VS Code with Python/Jupyter support
- A Google Gemini API key (for the essay workflow)

## Installation

Install the required packages:

```bash
pip install langgraph langchain-google-genai python-dotenv pydantic
```

Set your Gemini API key in your environment or in a `.env` file:

```bash
GOOGLE_API_KEY=your_api_key_here
```

## How to run

1. Open the notebook you want to explore in Jupyter or VS Code.
2. Run the cells in order.
3. For the essay workflow, ensure the Gemini API key is available before executing the LLM cells.

## Notes

These notebooks are intended as simple learning examples for understanding LangGraph workflows, state handling, and basic orchestration patterns.