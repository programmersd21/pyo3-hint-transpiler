# 🚀 PyO3 Hint Transpiler

**Generate Python stubs from Rust code effortlessly!**

![Rust](https://img.shields.io/badge/Rust-1.74-orange?logo=rust\&logoColor=white) ![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python\&logoColor=white)

---

## ✨ Features

* Transpile Rust types and functions to Python stubs 🐍
* Automatically maps Rust primitives, collections, and common wrappers 🔄
* Supports structs and impl blocks with methods 💎
* Works seamlessly with PyO3 projects 🦀

---

## 📦 Build from Source

* Clone the repository:

```bash
git clone https://github.com/pyo3-hint-transpiler.git
cd pyo3-hint-transpiler
```

* Build the project:

```powershell
./build.ps1
```

🎉 That's it! You now have the transpiler ready to generate Python stubs from your Rust code.

---

## ⚡ Usage

Once built, simply point the transpiler at your Rust crate, and it will produce Python `.pyi` stub files. Perfect for type hints and IDE autocompletion.

Example:

```bash
# Inside your Rust project
pyo3-hint-transpiler --input src/lib.rs --output stubs/
```

---

## 💖 Contributing

Contributions, issues, and feature requests are welcome! 🌟

1. Fork the repository
2. Create your feature branch
3. Submit a pull request

Let's make Rust <-> Python interop shiny and smooth! 🦄

---

## 🛠 License

MIT License © 2026
