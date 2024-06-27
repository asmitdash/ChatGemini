<p align="center">
  
</p>
<p align="center">
    <h1 align="center">ChatGemini</h1>
</p>
<p align="center">
    
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/asmitdash/ChatGemini?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/asmitdash/ChatGemini?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/asmitdash/ChatGemini?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/asmitdash/ChatGemini?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=flat&logo=Streamlit&logoColor=white" alt="Streamlit">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
</p>
<hr>



##  Overview

ChatGemini is a Streamlit web application that allows users to upload multiple PDF files and ask questions about their content. The application leverages Google Gemini, LangChain, and FAISS to process PDF text, create embeddings, and provide answers based on user queries.

---

##  Features

- Upload multiple PDF files and process their content.
- Split PDF text into manageable chunks using LangChain.
- Generate embeddings for text chunks using Google Gemini.
- Store and retrieve embeddings efficiently using FAISS.
- Answer user questions based on the processed PDF content.

---

##  Repository Structure

```sh
└── ChatGemini/
    ├── LICENSE
    ├── app.py
    ├── faiss_index
    │   ├── index.faiss
    │   └── index.pkl
    └── requirements.txt
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                                     | Summary                                      |
| ---                                                                                      | ---                                          |
| [requirements.txt](https://github.com/asmitdash/ChatGemini/blob/master/requirements.txt) | Lists all the Python packages that are required for your project to run. |
| [app.py](https://github.com/asmitdash/ChatGemini/blob/master/app.py)                     | This file contains the main logic and functionality of your Streamlit web application.           |

</details>

---

##  Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **Python**: `version 3.12.4`

###  Installation

1. Clone the ChatGemini repository:

```sh
git clone https://github.com/asmitdash/ChatGemini
```

2. Change to the project directory:

```sh
cd ChatGemini
```

3. Install the dependencies:

```sh
pip install -r requirements.txt
```

###  Running ChatGemini

Use the following command to run ChatGemini:

```sh
streamlit run app.py
```



##  Acknowledgments

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [LangChain](https://github.com/langchain-ai/langchain)
- [Google Generative AI](https://github.com/google/generative-ai-python)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Python Dotenv](https://github.com/theskumar/python-dotenv)



---
