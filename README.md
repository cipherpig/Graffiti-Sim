# Graffiti Simulator 🎨

A simple spray-paint style graffiti simulator built with Python and Pygame.
Designed for fast tagging, smooth strokes, and a more realistic spray feel.

---

## Features

* Continuous spray strokes (no dotted lines)
* Soft spray effect (less grainy)
* Adjustable brush size
* Randomized spray spread for realism
* Clean, minimal interface

---

## Controls

* **Left Click + Drag** → Spray paint
* **Scroll Wheel** → Change brush size
* **C Key** → Clear canvas
* **ESC** → Quit

---

## Installation

Make sure you have Python installed (3.10–3.13 recommended).

### 1. Create a virtual environment

```bash id="7o8v8u"
python3 -m venv venv
```

### 2. Activate it

```bash id="s1j4c9"
source venv/bin/activate
```

### 3. Install dependencies

```bash id="p3k2r1"
python3 -m pip install pygame-ce
```

---

## Running the App

```bash id="x9m2t4"
python3 graffiti.py
```

---

## Project Structure

```id="f2l8q6"
graffiti-sim/
│
├── graffiti.py
├── venv/
└── README.md
```

---

## Environment

Developed and tested using **zsh** on macOS (Monterey).

---

## Notes

* If you’re on newer Python versions (like 3.14), use `pygame-ce`
* Performance and smoothness depend on your system and frame rate
* This is a lightweight tool — not a full art program

---

## License

Do whatever you want with it 👍
