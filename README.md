# Pulmonary Nodule Analysis System

![LangChain](https://img.shields.io/badge/Powered_by-LangChain-blue)
![Ollama](https://img.shields.io/badge/Using-Ollama-important)
![Jupyter](https://img.shields.io/badge/Platform-Jupyter_Notebook-orange)

## Overview

A Jupyter Notebook-based system that analyzes CT scan reports to extract and structure pulmonary nodule information using LangChain and local LLMs via Ollama.

## Features

- **Precise Medical Data Extraction**:
  - Identifies pulmonary nodules with size measurements
  - Extracts anatomical locations (LUL, RLL, etc.)
  - Captures clinical descriptors (calcified, non-calcified)

- **LangChain Integration**:
  - Structured output parsing with validation
  - Response schema enforcement
  - Customizable prompt templates

- **Local LLM Processing**:
  - Runs on Ollama with Gemma2 (or other models)
  - Processes reports without cloud dependencies
  - Maintains data privacy

## Prerequisites

- Python 3.8+
- Jupyter Notebook
- Ollama installed and running locally

## Installation

### 1. Set Up Environment

```bash
# Create and activate virtual environment
python -m venv ct-env
source ct-env/bin/activate  # Linux/Mac
ct-env\Scripts\activate     # Windows

# Install Python dependencies
pip install jupyter langchain requests python-dotenv
