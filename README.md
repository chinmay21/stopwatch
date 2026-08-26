# ⏱️ Stopwatch

A simple desktop stopwatch application built with **Python and PyQt5**. The application provides start, stop, and reset controls while displaying elapsed time with centisecond precision.

## 📌 Features

* ▶️ **Start** the stopwatch
* ⏹️ **Stop** the stopwatch
* 🔄 **Reset** the stopwatch back to `00:00:00.00`
* ⏱️ Displays:

  * Hours
  * Minutes
  * Seconds
  * Centiseconds
* 🎨 Simple and clean graphical user interface
* 🖥️ Built as a desktop application using PyQt5

## 🛠️ Technologies Used

* **Python**
* **PyQt5**
* `QTimer` — updates the stopwatch at 10 ms intervals
* `QTime` — keeps track of the elapsed time
* Qt Layouts — used to organize the interface

## 📂 Project Structure

```text
stopwatch/
│
├── main.py
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/chinmay21/stopwatch.git
```

### 2. Navigate into the project

```bash
cd stopwatch
```

### 3. Install PyQt5

```bash
pip install PyQt5
```

### 4. Run the application

```bash
python main.py
```

## 🎮 How to Use

1. Click **Start** to begin the stopwatch.
2. Click **Stop** to pause it.
3. Click **Start** again to continue from the current time.
4. Click **Reset** to stop the stopwatch and return the display to `00:00:00.00`.

## 🧠 What I Learned

This project helped me practice:

* Creating GUI applications with **PyQt5**
* Working with `QWidget`, `QLabel`, and `QPushButton`
* Organizing widgets using `QVBoxLayout` and `QHBoxLayout`
* Handling button events with Qt signals and slots
* Using `QTimer` for repeated operations
* Working with `QTime`
* Formatting time values for display
* Applying styles using Qt Style Sheets
* Managing application state
* Connecting different components of a GUI application

## 🔮 Possible Improvements

Future versions could include:

* Lap time functionality
* Keyboard shortcuts
* Dark/light themes
* More accurate elapsed-time tracking using a monotonic clock
* Millisecond display with greater precision
* Saving and displaying previous lap times

## 👨‍💻 Author

**Chinmay Dhaundiyal**

GitHub: [chinmay21](https://github.com/chinmay21)

---

⭐ If you found this project useful, consider giving the repository a star!