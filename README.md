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

- app.py: Contains Streamlit app code for building the user interface and interaction logic.
- src/helper.py: Facilitates communication with the Gemini LLM.
- requirements.txt: Lists dependencies required to run the project.

## Flowchart of Project Deployement

![GenAI_Project](https://github.com/data-pioneer/Gen-AI-Multilingual-AI-Assistant-main/assets/33811437/097e5e20-e276-436d-ab1a-ce7bc842c831)

# How to run?
### STEPS:

### STEP 01-  Create GOOGLE_API_KEY to run Genimi api 
https://deepmind.google/technologies/gemini/#introduction


### Create .env file in the root directory and add your GOOGLE_API_KEY credentials as given bellow
### GOOGLE_API_KEY = "------------------"

### STEP 02- Create a conda environment after opening the repository

```bash
conda create -n multilingual python=3.9 -y
```

```bash
conda activate multilingual
```


### STEP 03- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up localhost:
```


###  STEP 04 - How to Deploy Streamlit app on EC2 instance
1. Login with your AWS console and launch an EC2 instance
2. Run the following commands
Note: Do the port mapping to this port:- 8501

```bash
sudo apt update
```

```bash
sudo apt-get update
```

```bash
sudo apt upgrade -y
```

```bash
sudo apt install git curl unzip tar make sudo vim wget -y
```

```bash
git clone "Your-repository"
```

```bash
sudo apt install python3-pip
```

```bash
pip3 install -r requirements.txt
```

# Temporary running
```bash
python3 -m streamlit run app.py
```

# Permanent running
```bash
nohup python3 -m streamlit run app.py
```
Note: Streamlit runs on this port: 8501