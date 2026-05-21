# 🎮 Sentiment Analysis on Game Chats

Automatically detects **toxic** vs **neutral** messages in Valorant and Minecraft in-game chats using BERT.

---

## What it does

1. Takes screenshots of in-game chats
2. Extracts text using OCR (Tesseract + EasyOCR)
3. Cleans and preprocesses the text
4. Classifies each message as **Toxic** or **Neutral**

---

## Results

| Model | Accuracy |
|-------|----------|
| **BERT** ✅ | **89%** |
| LSTM | 52% |
| GRU | 50.39% |

---

## Tech Used

`Python` `PyTorch` `BERT` `Tesseract OCR` `OpenCV` `NLTK`

---

## Sample Predictions

```
"GG boys"              → Neutral
"Brainless coward"     → Toxic
"Pass me the cobblestone" → Neutral
"Braindead person"     → Toxic
```

---

## Dataset

- 1,781 chat screenshots from Valorant & Minecraft
- 52.5% Neutral · 47.5% Toxic

---
