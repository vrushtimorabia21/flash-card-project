# Flashy – French Flashcard Learning App

Flashy is a simple **French-English flashcard application** built using **Python, Tkinter, and Pandas**. It helps users learn French vocabulary by showing a French word first and automatically revealing its English meaning after 3 seconds.

## ✨ Features

* 🇫🇷 Displays French words as flashcards
* 🇬🇧 Automatically flips to show the English translation
* ⏱️ Cards flip automatically after 3 seconds
* ❌ Mark a word as unknown and move to the next card
* ✅ Mark a word as known and remove it from the learning list
* 💾 Saves remaining words automatically
* 🔄 Continues learning from where you left off

## 🛠️ Technologies Used

* **Python**
* **Tkinter** – Graphical User Interface
* **Pandas** – Reading and updating CSV files
* **Random** – Selecting flashcards randomly

## 📂 Project Structure

```text
Flashy/
│
├── data/
│   ├── french_words.csv
│   └── words_to_learn.csv
│
├── images/
│   ├── card_front.png
│   ├── card_back.png
│   ├── right.png
│   └── wrong.png
│
└── main.py
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Open the project folder

```bash
cd Flashy
```

### 3. Install the required library

```bash
pip install pandas
```

> Tkinter is usually included with standard Python installations.

### 4. Run the application

```bash
python main.py
```

## 🎮 How It Works

1. A French word appears on the flashcard.
2. After **3 seconds**, the card flips and displays its English meaning.
3. Click ❌ if you don't know the word.
4. Click ✅ if you know the word.
5. Known words are removed from the learning list.
6. The remaining words are saved in `words_to_learn.csv`.

## 💡 Learning Logic

The application first checks whether `words_to_learn.csv` exists.

* If it exists → the app continues with the remaining words.
* If it doesn't exist → the original `french_words.csv` is loaded.
* Whenever a word is marked as known, the updated list is saved automatically.

## 📸 Preview

Add a screenshot of your application here:

```markdown
![Flashy App Screenshot](images/screenshot.png)
```

## 📚 What I Learned

Through this project, I practiced:

* Working with **Tkinter GUI**
* Using **Canvas and Buttons**
* Reading and writing **CSV files**
* Using **Pandas DataFrames**
* Working with **lists and dictionaries**
* Using `random.choice()`
* Using Tkinter's `after()` function for timers
* Managing application state with global variables
* Building a small practical Python project

## 👩‍💻 Author

**Vrushti Morabia**

Built as a Python learning project.
