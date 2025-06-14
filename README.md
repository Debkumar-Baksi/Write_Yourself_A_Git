# 🧠 Wyag — The Stupidest Content Tracker

**Wyag** is a Git-like version control system built from scratch in Python.  
The name stands for **Write Yourself A Git**, inspired by the idea of learning by building.

> 🚀 “The best way to understand Git is to build Git.”

---

## ✨ Features

- `init` – Create a new repository  
- `add` – Stage files to the index  
- `commit` – Save snapshots of your code  
- `log` – View commit history as a DAG  
- `status` – See what's staged, modified, or untracked  
- `ls-files`, `ls-tree`, `rev-parse`, `show-ref`, `tag`, `checkout`, and more  
- `.gitignore` support  
- Compatible with **Windows CMD**, **PowerShell**, and **Linux shell**

---

## 🛠 How to Use

- Clone the project  
  ```bash
  git clone https://github.com/Debkumar-Baksi/Write_Yourself_A_Git.git
  ```
* Move into the project folder

  ```bash
  cd wyag
  ```

* Initialize a new repository

  ```bash
  python wyag init myrepo
  cd myrepo
  ```

* Create a file

  ```bash
  echo Hello, Wyag! > test.txt
  ```

* Add and commit

  ```bash
  python ..\wyag add test.txt
  python ..\wyag commit -m "Initial commit"
  ```

* View status and log

  ```bash
  python ..\wyag status
  python ..\wyag log
  ```

---

## 📦 Available Commands

```bash
python wyag init myrepo
python wyag add file.txt
python wyag commit -m "message"
python wyag status
python wyag ls-files
python wyag log
python wyag ls-tree HEAD
python wyag rev-parse HEAD
python wyag tag v1.0
python wyag tag
python wyag show-ref
python wyag checkout HEAD checkout-dir
python wyag rm file.txt
python wyag hash-object -w file.txt
python wyag cat-file blob <sha>
python wyag check-ignore file.pyc
```

---

## 💡 Why I Built This

I built Wyag to understand how Git works under the hood.
By re-creating Git’s core concepts — blobs, trees, commits, refs — I gained a deeper understanding of version control, file storage, and DAG-based history.

This project helped me master:

* Git internals
* File systems and binary formats
* Hashing and data integrity
* Python I/O and CLI design

---

## 🌱 What’s Next

* Commit graph visualization
* Branching and merging
* Web frontend for viewing repo state
* Improved diff and patching

---

## 📌 License

MIT License — free to use, share, and modify.

---

> Made with 💻 and ☕ by [Debkumar](https://github.com/Debkumar-Baksi)
