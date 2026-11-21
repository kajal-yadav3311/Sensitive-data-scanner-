# 🔌 Python TCP Client-Server Chat Application

A simple and robust implementation of **TCP Socket Programming** in Python, enabling structured message exchange between a client and a server.

## 🚀 Features

* Establishes a stable TCP/IP connection using Python's built-in `socket` module.
* Real-time 3-way bidirectional message exchange loop.
* Exception handling for connection errors (`ConnectionRefusedError`, `OSError`).
* Clean resource management with proper socket closing (`finally` blocks).

## 🛠️ Tech Stack

* **Language:** Python
* **Modules:** `socket`

## ⚙️ How to Run

1. Run the **Server** script first:
```bash
python server.py

```


2. In a separate terminal, run the **Client** script:
```bash
python client.py

```



#### Step 3: Name the Files Properly

Make sure your code files are saved with the proper names:

* Name the server code **`server.py`**.
* Name the client code **`client.py`**.

#### Step 4: Commit the Code

Push your changes to GitHub:

```bash
git add .
git commit -m "Add TCP client-server socket communication script and documentation"
git push origin main

```
