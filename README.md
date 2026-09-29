# FAQ Chatbot

This chatbot reads questions and answers from `faqs.json`, cleans the text
with NLTK stemming, and finds the closest FAQ using TF-IDF and cosine
similarity.

## Install

```bash
cd "project 1"
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

Start an interactive chat:

```bash
python faq_chatbot.py
```

Ask one question:

```bash
python faq_chatbot.py --question "Why am I getting a 429 error?"
```

Add or edit FAQ objects in `faqs.json` to customize the chatbot.
