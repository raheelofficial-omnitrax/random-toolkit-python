# 🎲 Random Toolkit

A lightweight Python toolkit demonstrating the core capabilities of the built-in `random` module — random number generation, random selection, and list shuffling — wrapped in clean, reusable functions with a runnable demo.

![Python](https://img.shields.io/badge/python-3.6%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 📖 Overview

**Random Toolkit** is a small educational project that shows how to work with Python's `random` module through simple, well-documented functions. It's a great reference for beginners learning randomness in Python, or a quick starting point for projects that need random number generation, selection, or shuffling logic.

## ✨ Features

| Feature | Description |
|---|---|
| 🔢 Random Integer | Generate a random integer within a given range |
| 🔣 Random Float | Generate a random decimal between `0.0` and `1.0` |
| 🎮 Random Choice | Pick a random item from a list or tuple (e.g. Rock/Paper/Scissors) |
| 🃏 List Shuffling | Randomly shuffle a list in place (e.g. a deck of cards) |

## 🗂️ Project Structure

```
random-toolkit/
├── random_toolkit.py   # Main program with all functions and demo
├── README.md            # Project documentation
├── LICENSE               # MIT License
└── .gitignore            # Python-specific ignore rules
```

## 🚀 Getting Started

### Prerequisites
- Python 3.6 or higher (no external dependencies required)

### Installation

```bash
git clone https://github.com/<your-username>/random-toolkit.git
cd random-toolkit
```

### Usage

Run the script directly:

```bash
python random_toolkit.py
```

## 💻 Example Output

```
=============================================
        RANDOM TOOLKIT v1.0
=============================================

🎲 Random Number:
42

🔢 Random Decimal Number:
0.7381902456321

🎮 Computer Choice:
Rock

🃏 Shuffled Cards:
['9', 'K', '3', '10', 'A', '5', 'Q', '2', '7', '4', 'J', '8', '6']

=============================================
Program Completed Successfully ✅
=============================================
```

## 🧩 Function Reference

| Function | Parameters | Returns | Description |
|---|---|---|---|
| `generate_random_number(start, end)` | `start: int`, `end: int` | `int` | Random integer between `start` and `end` (inclusive) |
| `generate_random_float()` | — | `float` | Random float between `0.0` and `1.0` |
| `choose_random_option(options)` | `options: list \| tuple` | any | Randomly selected item from the input |
| `shuffle_cards(cards)` | `cards: list` | `list` | Shuffles the list in place and returns it |

## 🛣️ Roadmap

- [ ] Add unit tests with `pytest`
- [ ] Add a CLI interface with argument parsing
- [ ] Add weighted random selection example
- [ ] Add random string / password generator utility

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Raheel Babar**

---

<p align="center">⭐ If you found this useful, consider giving it a star!</p>
