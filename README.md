%%writefile README.md
# 😄 EmojiMoodAI

EmojiMoodAI is an interactive web app that predicts emojis matching the emotional tone of your text input!
It uses **sentence-transformers** to analyze your sentence and returns emojis representing the mood behind your words.

Built using **Gradio** for a simple, user-friendly interface and **Sentence-BERT** embeddings for semantic similarity.

## 🚀 Features
✅ Predict emojis that represent the mood of any text input  
✅ Uses pretrained NLP model `all-MiniLM-L6-v2`  
✅ Clean, interactive Gradio interface  
✅ Adjustable emoji count slider  

## 🧠 How It Works
1. Encode sentences using SentenceTransformer.  
2. Compute cosine similarity between your input and mood samples.  
3. Return emojis from the most similar moods.  

## ▶️ Run
```bash
!pip install -q sentence-transformers gradio
