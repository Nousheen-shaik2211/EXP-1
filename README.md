# EXP-1
# Prompt Engineering Lab – Gemini API

## Aim
To establish a working environment for prompt engineering and communicate with a Large Language Model (LLM) using the Google Gemini API.

## Problem Statement
Develop a Python program that loads a Gemini API key securely, sends a predefined prompt to an LLM, displays the response, and handles errors.

## Technologies Used
- Python
- Google Gemini API
- Google GenAI SDK
- Google Colab / Visual Studio Code

## Installation
Install the required dependency:

```bash
pip install -r requirements.txt
```

## Configuration
Generate an API key from [Google AI Studio](https://aistudio.google.com/apikey).

The program requests the key securely when it runs. Never publish your API key.

## Execution
Run the program using:

```bash
python connectivity.py
```

Enter your Gemini API key when prompted.

## Sample Prompt
What is prompt engineering? Answer in one sentence.

## Expected Result
The Gemini model generates a one-sentence explanation of prompt engineering and displays it in the console.

## Output
Execution screenshots are available in the `outputs/` directory.

## Security
API keys and other credentials must not be committed to GitHub.

## Conclusion
The experiment demonstrates secure API key handling, prompt submission, LLM response generation, and basic error handling using the Google Gemini API.
