# 🧠 French Flashcard App 🇫🇷

A simple and elegant Tkinter GUI app to help you learn French vocabulary through flashcards.

## 📸 Preview

![App Screenshot](images/card_front.png)

## 🔧 Features

- Displays a French word, flips to English after 3 seconds
- Mark words you already know ✅
- Automatically saves progress to `words_to_learn.csv`

## 🚀 How It Works

1. Loads a list of French-English words from `french_words.csv`
2. Shows a random French word on a card
3. After 3 seconds, flips the card to show the English translation
4. You can mark if you **know** or **don't know** the word
5. App will remember known words and remove them from future quizzes

## 🖼️ UI Assets

Make sure the following images are in the `images/` folder:
- `card_front.png`
- `card_back.png`
- `right.png`
- `wrong.png`

## 📦 Dependencies

- `tkinter` (comes with Python)
- `pandas`

Install pandas if not already:

```bash
pip install pandas
```
## 🏁 How to Run:

```bash
python main.py
```






