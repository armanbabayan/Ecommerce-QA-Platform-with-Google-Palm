
# Ecommerce Q&A platform with Google PaLM in LangChain

## Overview

This E-commerce Q&A platform is designed to intelligently answers user questions by analyzing previously asked questions from other users. This project leverages the capabilities of Language Model Models, with a specific focus on the `Google PaLM` model incorporated within LangChain. To enhance the data management aspect, is utilized `FASSI from META` as a vector database. The data source is Kaggle. You can find it by following this [link](https://www.kaggle.com/datasets/saadmakhdoom/ecommerce-faq-chatbot-dataset).
The end result is a user-friendly `Streamlit` application.

## Features

- Load json file to fetch the content using LangChain's JSONLoader.
- Construct embeddings vector using HuggingFaceInstructEmbeddings. 
- Leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information.
- Interact with the LLM (Google PaLM) by inputting queries and receiving answers.

## Project Flowchart

![Flowchart](demo/Project_Flowchart.png)

## Demo
![](demo/demo.gif)

## Environment Variables

To run this project, you will need to add `GOOGLE_API_KEY` environment variable to your .env file. To generate an API key, please go to the `MakerSuite` web page using the following [link](https://makersuite.google.com/).

## Run Locally

## Prerequisites

Before using this tool, make sure you have the following prerequisites installed:

- Python 3.11
- [Poetry](https://python-poetry.org/): You can install it following the [Poetry installation guide](https://python-poetry.org/docs/#installation).
- All dependencies can be installed using poetry. Simply run `poetry install` command.

Clone the project

```bash
  git https://github.com/armanbabayan/News-research-tool-with-LangChain.git
```

Go to the project directory

```bash
  cd Ecommerce-QA-Platform-with-Google-Palm-in-LangChain
```

Install dependencies

```bash
  poetry install
```

Start the server

```bash
 poetry run streamlit run  main.py
```


## Tech Stack
**Language:**  Python 3

**Library:** LangChain, Faiss, Streamlit

**Model:** Google PaLM

[![python](https://camo.githubusercontent.com/3cdf9577401a2c7dceac655bbd37fb2f3ee273a457bf1f2169c602fb80ca56f8/68747470733a2f2f666f7274686562616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667)](https://www.python.org/)  

<div style="flex: 50%; padding: 5px;">
    <img src="https://seeklogo.com/images/G/google-palm-logo-D04D962B7F-seeklogo.com.png" alt="OpenAI" style="width:10%;">
    <img src="https://avatars.githubusercontent.com/u/126733545?s=48&v=4" alt="LangChain" style="width:10%;">
    <img src="https://avatars.githubusercontent.com/u/45109972?s=200&v=4" alt="Streamlit" style="width:10%;">
  </div>


## Authors

- [@armanbabayan](https://github.com/armanbabayan)

