[🇰🇷 한국어](./README.ko.md) | 🇺🇸 English

# kobraille ⠿

> Standard Python library for translating LaTeX math expressions
> into Korean Braille (KS X 1107)

by [Qualia Bridge](https://github.com/qualia-bridge)

---

## ✨ Why kobraille?

In Korea, visually impaired students often cannot access
math education in Braille.
Existing tools lack accuracy, transparency, and extensibility.

kobraille is built by someone who sits at a rare intersection:

- 📖 Braille specialist — every rule grounded in KS X 1107
- 📊 Statistics & Data Science M.S. — rigorous, evidence-based approach
- 📈 Data visualization developer — clarity in how information 
     is structured and delivered

---

## 🚧 Status

Currently in active development (stealth mode).
Star this repo to follow along!

### Roadmap
- [x] v0.1 — Basic arithmetic (+, -, *, /) & parentheses
- [x] v0.2 — Fractions (`\frac`) & mixed numbers
- [x] v0.3 — Exponents & subscripts (`^`, `_`)
- [x] v0.4 — Square roots (`\sqrt`)
- [x] v0.5 — Trigonometric functions
- [x] v1.0 — PyPI release 🚀

---

## 📦 Installation

pip install kmathbraille

from kmathbraille import to_braille as tb

tb(r"\frac{1}{2}")   # ⠼⠃⠌⠼⠁  
tb(r"x^{2}")         # ⠭⠘⠼⠃  
tb(r"\sqrt{2}")      # ⠜⠼⠃  
tb(r"\sin{x}")       # ⠖⠎⠭  

---

## 🤝 Contributing

Contributions welcome!
Especially from Braille specialists and math educators.

---

## 📄 License

MIT License © 2026 Qualia Bridge
