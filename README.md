# Python-AI-Chatbot

> 참고: [나만을 위한 AI 심리상담 챗봇 만들기](https://www.youtube.com/watch?v=VVArHrsxrYU&t=601s)

![image](https://user-images.githubusercontent.com/84761609/181522223-29e29a7b-4570-4744-989e-1a58016ca1a0.png)

## Pretrained Model

SentenceBERT [jhgan/ko-sroberta-multitask](https://huggingface.co/jhgan/ko-sroberta-multitask)

## Dataset

웰니스 대화 스크립트 데이터셋

## Dependency

- streamlit
- streamlit-chat
- pandas
- sentence-transformers
- scikit-learn

## Sequence

1. Download Dataset: `wellness_dataset_original.csv`
2. Data Preprocessing
    - `wellness_dataset_original.csv` -> `wellness_dataset.csv`
    - See `wellness_dataset.ipynb`
3. Making a ChatBot

## How to Install

### 1. Download to local folder

```
$ git clone git@github.com:dnya0/Python-AI-Chatbot.git
```

### 2. Open VSCode of Anaconda

### 3. Download Dependencies From the terminal in VSCode of Anaconda

```
$ pip install streamlit
$ pip install streamlit-chat
$ pip install pandas
$ pip install sentence-transformers
```

### 4. Run `main.py` From the terminal in VSCode of Anaconda

```
streamlit run main.py
```
