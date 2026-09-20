# 🎯 Hangman Game

A simple and interactive **Hangman word-guessing game built with Python and Pygame**.

The game randomly selects a word from a word list and allows the player to guess the hidden word by selecting letters. Incorrect guesses progressively reveal the Hangman stages.

---

## 🎮 Features

- 🎯 Random word selection
- 🔤 Interactive letter selection
- 🪢 Visual Hangman stages
- 🖱️ Mouse-based letter selection
- ❤️ Limited incorrect attempts
- 📝 Word list stored in a separate file
- 🖼️ Custom Hangman images
- 🎮 Simple Pygame interface

---

## 🛠️ Technologies Used

- **Python 3**
- **Pygame**

---

## 📂 Project Structure

```text
Hangman-Game/
│
├── main.py
├── words.txt
├── hangman0.png
├── hangman1.png
├── hangman2.png
├── hangman3.png
├── hangman4.png
├── hangman5.png
├── hangman6.png
├── README.md
└── .gitignore
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RaavanHrishi07/Hangman-Game.git
```

### 2. Navigate to the Project

```bash
cd Hangman-Game
```

### 3. Install Pygame

```bash
python -m pip install pygame
```

### 4. Run the Game

Because the game loads its assets using the project folder path, run it from the **parent directory**:

```bash
python Hangman-Game\main.py
```

The Hangman game window will open.

---

## 🎮 How to Play

1. Start the game.
2. A random word is selected from `words.txt`.
3. Select letters from the available letter buttons.
4. Correct guesses reveal the letters in the hidden word.
5. Incorrect guesses progress the Hangman image.
6. Try to guess the complete word before the Hangman reaches the final stage.

---

## 🖱️ Controls

| Input | Action |
|-------|--------|
| Mouse Click | Select a letter |
| Window Close | Exit the game |

---

## 📚 Word List

The game uses `words.txt` as its word database.

New words can be added to this file to expand the game's vocabulary.

Example:

```text
python
computer
programming
developer
keyboard
```

---

## 🖼️ Hangman Stages

The project contains seven Hangman images:

```text
hangman0.png
hangman1.png
hangman2.png
hangman3.png
hangman4.png
hangman5.png
hangman6.png
```

Each image represents a different stage of the Hangman drawing as incorrect guesses increase.

---

## 🧪 Testing

The game was tested locally using:

```text
Python 3.11.9
Pygame
```

The game successfully launched and the gameplay, word selection, letter interaction, and Hangman stages were tested.

---

## 💡 Future Improvements

Possible future improvements include:

- 🎨 Modern graphical interface
- 🔄 New Game / Restart button
- 🏆 Score system
- ❤️ Lives counter
- ⏱️ Timer
- 📊 Game statistics
- 🔊 Sound effects
- 🎭 Improved animations
- 🌙 Dark mode
- 📱 Improved responsive layout

---

## 👨‍💻 Author

**Hrishikesh Sharma**

GitHub: [RaavanHrishi07](https://github.com/RaavanHrishi07)

---

## 📄 License

This project is intended for educational and personal use.