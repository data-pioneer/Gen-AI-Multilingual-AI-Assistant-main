# Gen-AI-Multilingual-AI-Assistant


This repository implements a multilingual conversational AI assistant leveraging Gemini's large language model (LLM) capabilities. The user interface is built with Streamlit for a user-friendly web application. The assistant can be deployed on Amazon EC2 for scalable and accessible interaction.

## Features:

- Multilingual support: Interact with the AI assistant in multiple languages (specify supported languages here).
- Powered by Gemini: Utilize Gemini's LLM capabilities for intelligent and engaging conversation.
- Streamlit UI: User-friendly interface for seamless interaction with the assistant.
- AWS EC2 deployment: Deploy the assistant on Amazon EC2 for scalability and accessibility.
- PaLM2
- s2t
- t2s
  
## Project Structure:

app.py: Contains Streamlit app code for building the user interface and interaction logic.
src/helper.py: Facilitates communication with the Gemini LLM.
requirements.txt: Lists dependencies required to run the project.

## Flowchart of Project Deployement

![GenAI_Project](https://github.com/data-pioneer/Gen-AI-Multilingual-AI-Assistant-main/assets/33811437/097e5e20-e276-436d-ab1a-ce7bc842c831)

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```
