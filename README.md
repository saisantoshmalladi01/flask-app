# 🧮 Mathematics Problem Solver (Flask App)

A lightweight web application built with Flask that performs basic mathematical operations — **addition**, **subtraction**, and **multiplication** — via a clean web interface and simple API endpoints.

---

## 📁 Project Structure


---

## 🚀 Features

- Web UI to enter two numbers and choose an operation
- Backend API routes to:
  - Add (`/sum?num1=...&num2=...`)
  - Subtract (`/sub?num1=...&num2=...`)
  - Multiply (`/mul?num1=...&num2=...`)
- Modular arithmetic logic separated in the `Maths/` folder
- Clean and minimal structure, easy to expand

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/flask-app.git
cd flask-app
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
python server.py

