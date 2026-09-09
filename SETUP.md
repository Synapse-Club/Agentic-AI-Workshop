# 🤖 Synapse Agentic AI Workshop — Setup Guide

This guide will help you set up your environment for the workshop.

---

## 1. Prerequisites

Before the workshop, make sure you have:

- **Python 3.10 or newer**
- **Jupyter Notebook** or **JupyterLab**
- **Git** (only required if you want to clone the repository)
- A **GitHub account**

Check your Python version:

```bash
python --version
```
## 2. Install Libraries

### Option 1 — Install Libraries Directly

If you don't want to download the repository, you can install all the required libraries directly from Jupyter Notebook.

Open a Jupyter Notebook and run:

```bash
%pip install langchain langgraph chromadb mcp
```

Wait for the installation to finish.

Note: Restart the Jupyter kernel after installation if required.


### Option 2 — Clone This Repository

If you have Git installed, open Command Prompt / PowerShell / Terminal and run:
```bash
git clone https://github.com/Synapse-Club/Agentic-AI-Workshop.git
```

Move into the repository folder:
```bash
cd Agentic-AI-Workshop
```
Install all required libraries:
```bash
pip install -r requirements.txt
```
If pip doesn't work, use:
```bash
python -m pip install -r requirements.txt
```

## 3. Verify Your Setu
Run the following code in a new Jupyter cell:
```bash
import langchain
import langgraph
import chromadb
import mcp

print("✅ All libraries installed successfully!")
print("🚀 You are ready for the workshop!")
```


