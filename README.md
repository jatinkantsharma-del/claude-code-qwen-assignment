# Claude Code + Qwen Model Assignment

## Overview

This repository contains the solution for the Claude Code + Qwen Model Setup Assignment. The project demonstrates the installation and usage of Claude Code, Ollama, and the Qwen3:4B model, along with Python integration for interacting with the model locally.

## Objectives

* Install Claude Code
* Install and configure Ollama
* Download and run the Qwen3:4B model
* Integrate the model with Python using the Ollama API
* Upload the project to GitHub

## Technologies Used

* Python 3
* Ollama
* Qwen3:4B
* Claude Code
* Requests Library
* Git & GitHub

## Project Structure

```text
claude-code-qwen-assignment/
│
├── app.py
├── README.md
```

## Setup Instructions

### 1. Install Ollama

Verify installation:

```bash
ollama --version
```

### 2. Download Qwen Model

```bash
ollama pull qwen3:4b
```

Verify:

```bash
ollama list
```

### 3. Run the Model

```bash
ollama run qwen3:4b
```

### 4. Install Python Dependency

```bash
pip install requests
```

### 5. Run the Application

```bash
python app.py
```

## Sample Output

```text
Enter your question:
What is Generative AI?

Model Response:
Generative AI is a type of artificial intelligence that can create new content such as text, images, audio, and code.
```

## Author

Name: Hemant Kumar

## GitHub Repository

This repository was created as part of the Claude Code + Qwen Model Setup Assignment.