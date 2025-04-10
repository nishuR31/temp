
# 🕒 Real-Time Digital Clock (Terminal Edition)

This is a simple Python script that displays the current system time in real-time using the terminal. It updates the time continuously with minimal delay — basically, a tiny terminal time machine that keeps ticking!

## 🚀 Features

- Displays the **current system time** using `time.ctime()`
- Continuously updates in place using carriage return `\r`
- Super lightweight and minimal
- Great for practicing terminal output techniques

## 🧠 Code

```python
import time as t
while True:
    print("\r", t.ctime(), end="")
    t.sleep(0.0001)
```

> ⚠️ Heads-up: This runs in an infinite loop. Close the terminal or stop the process manually (`Ctrl+C`) to exit.

## 🔧 Requirements

- Python 3.x (tested with Python 3.6+)
- No external libraries needed — just the standard `time` module

## 📦 How to Run

1. Clone the repository or copy the script.
```bash
git clone https://github.com/nishuR31/temp.git
cd temp
```

2. Save it as `clock.py`
3 Open a terminal and run:

```bash
python clock.py
```

## 💡 Notes

- This script pushes the update frequency to the edge with `0.0001` second delay. You might want to increase it to something like `0.5` seconds for a human-readable refresh rate.
- Want to style it up or add a digital interface? Fork it and go wild!

## 📄 License

This project is open source and free to use. Attribution is appreciated but not required.

---

**Stay synced, stay sharp.** 🧭
