# 🃏 Qt Memory Card Game

A simple memory matching game built using **C++ and Qt**.  
Flip cards, find matching pairs, and test your memory.

---

## 🎮 Features

- Dynamic grid-based card layout (currently 4x5)
- Image-based cards loaded from a directory
- Card flipping with mouse interaction
- Match detection logic
- Timer-based reset for incorrect matches
- Prevents flipping more than two cards at once
- Clean modular design using custom Qt widgets

---

## 🧠 How It Works

- Each image is duplicated to create matching pairs
- Cards are shuffled randomly at the start
- Player flips two cards:
  - ✅ If they match → they stay face-up
  - ❌ If not → they flip back after a short delay
- Game continues until all pairs are matched

---

## 🛠️ Technologies Used

- C++
- Qt Framework (Qt Widgets)
- QGridLayout (UI layout)
- QTimer (delayed actions)
- Custom QWidget (`FlipLabel`) for card behaviour

---

## 📂 Project Structure
├── mainwindow.cpp / .h # Game logic and UI setup
├── fliplabel.cpp / .h # Custom card widget
├── images/ # Card images
└── main.cpp # Application entry point


---

## ▶️ How to Run

### Option 1: Run in Qt Creator
1. Open the project in Qt Creator
2. Build and run

---

### Option 2: Run exported version
1. Click on the lecture7newnew.exe file


---

## ⚠️ Important

- Make sure the `images/` folder is in the correct path: /images

- 
- If exporting, ensure:
  - `windeployqt` has been run
  - Required Qt `.dll` files are included

---

## 🚀 Future Improvements

- Add scoring system
- Add restart button
- Add animations for card flipping
- Add difficulty levels (different grid sizes)
- Track game completion time

---

## 👨‍💻 Author

Neel Bhavsar

---

## 📄 License

This project is for educational purposes.
