# GenAI-Medical_Chatbot
This project is an End-to-End AI-powered Medical Chatbot built using Streamlit, OpenAI, LangChain, and Pinecone. It leverages Generative AI and LLMs to provide intelligent and context-aware responses to medical queries. The chatbot can process and retrieve medical information efficiently, ensuring reliable and insightful interactions.

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
