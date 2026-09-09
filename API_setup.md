# 🔑 API Key Setup

## 🤖 Synapse Agentic AI Workshop

For the workshop, you will need access to an LLM API.

You can use **either Groq or Azure OpenAI**.

> ⭐ **Recommended Groq**

---

# 🚀 Groq API (Recommended)

## Step 1 — Create a Groq Account

Go to:

https://console.groq.com/

Sign up or log in using your account.

---

## Step 2 — Create an API Key

After logging in, open the Groq API Keys page:

https://console.groq.com/keys

Click:

**Create API Key**

Give your key a name, for example:

```text
synapse-workshop
```
Create the key and copy it.

⚠️ IMPORTANT: Your API key is secret. Never share it with anyone or upload it to GitHub.


## Step 3 — Add Your API Key to Jupyter

In your Jupyter Notebook, run:
```bash
import os

os.environ["GROQ_API_KEY"] = "PASTE_YOUR_API_KEY_HERE"
```
Replace:
```text
PASTE_YOUR_API_KEY_HERE
```

with your actual Groq API key.

