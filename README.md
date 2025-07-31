# MulticalcQE (Multicalc 0.2QE)
Created by Vardhan,it has various types of CLI calculators
🧮 A Command-Line Python Calculator with Multiple Modes and Questionary Support  
*By Vardhan | AV Technologies*

---

## 🔍 What is MulticalcQE?

MulticalcQE is a simple yet powerful **Python-based command-line calculator** that supports:
- 📈 **Finance** mode: Calculate Simple Interest (SI) or Compound Interest (CI)
- 💱 **Currency Conversion**: Convert USD to INR or EUR (static rates)
- ➕ **Basic Arithmetic**: Add, Subtract, Multiply, Divide
- 🧠 **Interactive CLI** with **questionary** (with fallback to classic input)

---

## 🚀 Features
- ✅ User-friendly UI using `questionary`
- 🔁 Runs in a loop, can exit with option 4
- 📦 Built as `.deb` package for easy Debian installation
- 💡 Fallback system: Works even if `questionary` isn't installed
- 🪵 Future plans: error logging (MulticalcFF), light & scientific editions (LE, SE)

---

## 🖥️ Requirements

- Python 3.x
- [colorama](https://pypi.org/project/colorama/)
- [questionary](https://pypi.org/project/questionary/)

Install with:
```bash
pip3 install colorama questionary
