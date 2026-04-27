# Quizlet Clone — Flashcard & Quiz App

A feature-rich, single-file study application inspired by Quizlet. This app allows you to create, manage, and study flashcards with a modern, responsive interface and local persistence.

## 🚀 Features

- **Multiple Study Modes**:
  - **Multiple Choice**: Test your knowledge with dynamically generated distractors.
  - **Flashcards**: Interactive 3D flip cards for classic memorization.
- **Persistence**: Your study sets, titles, and preferences are automatically saved to `localStorage`. Refreshing the page won't lose your progress.
- **Advanced Management**:
  - **Search**: Quickly filter through large sets with a real-time search bar.
  - **Bulk Import**: Paste tab-separated text to import hundreds of cards instantly.
  - **Swap Toggle**: Effortlessly switch between "Term → Definition" and "Definition → Term" modes.
- **Backup & Portability**:
  - **JSON Backup**: Download your entire set as a file or upload one to restore it.
  - **Clipboard Export**: Copy your set in TSV (Tab-Separated Values) format for easy sharing.
- **Clean UI**: A polished dark-mode aesthetic with smooth animations and responsive design.

## ⌨️ Keyboard Shortcuts

### Multiple Choice Quiz
- **`1`, `2`, `3`, `4`**: Select answer choices.
- **`Enter` / `Space`**: Advance to the next question (after answering).

### Flashcard Mode
- **`Space`**: Flip the current card.
- **`Enter` / `→` (Right Arrow)**: Next card.
- **`←` (Left Arrow)**: Previous card.

### Results Screen
- **`Enter`**: Restart the session immediately.

## 🛠️ How to Use

1. **Setup**: Enter a title and start adding cards. You can use the **Add card** button or the **Bulk import** area.
2. **Importing**: Use the format `Term [Tab] Definition`.
3. **Study**: Click **Multiple choice** or **Flashcards** to begin.
4. **Save**: The app saves automatically, but you can use the **Download .json backup** button to keep a hard copy of your sets.

## 📄 License
This project is open-source and free to use.
