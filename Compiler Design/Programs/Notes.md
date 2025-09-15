# 🗂️ Organize Me Later

## 📖 Description
Notes and references for foundational programming knowledge.  
This repo is meant as a high-level overview with occasional technical deep dives and examples.

---

## 🔗 Links

1. **Concepts of Programming Languages** by Robert W. Sebesta (12th Edition, Pearson)  
   ISBN-13: 978-0-13-510226-8  
   [📄 PDF Link](https://www.selahattinalan.com/dersler/pl/Concepts%20of%20Programming%20Languages%20-%20Sebesta%20-%20E12.pdf)

---

## 📌 Interesting Sections from the Book
- Compilation Overview  
- Compiler  
- Intermediate Language  
- Abstract Stack Machine  
- Examples  

---

## ⚙️ Compilation Process (High-Level)

**Preprocessor → Compiler → Assembly Language → Assembler → Machine Code → Linker**

---

## 🧩 Detailed Compilation Flow

**Source Program** →  
Lexical Analyzer → *(lexical units / “stream” of lexemes)* →  
Syntax Analyzer → *(parse trees, syntax trees, expression trees…)* →  
Semantic Analyzer →  
Intermediate Language Generator → *(intermediate code)* →  
Intermediate Code Optimizer →  
Assembly Code Generator  

---

## 📝 Notes

### Meta Language
A **meta language** defines the *grammar rules* of a programming language.  
It specifies *what the language should look like*.

---

### Infix vs Postfix Example

- **Infix:**  
  `K = (i * j) * y`

- **Postfix:**  
  `kij*x*=`
