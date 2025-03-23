# 🧮 Mathematics Problem Solver (Flask App)

A lightweight web application built with Flask that performs basic mathematical operations — **addition**, **subtraction**, and **multiplication** — via a clean web interface and simple API endpoints.

---

## 📁 Project Structure

hjbsk-build_deploy_app_flask/ ├── server.py # Main Flask app ├── Maths/ │ └── mathematics.py # Functions for basic arithmetic ├── templates/ │ └── index.html # Home page ├── static/ # Static files (CSS, JS, images) ├── requirements.txt # Python dependencies ├── .gitignore ├── README.md 

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

### 1. Steps

```bash
git clone https://github.com/yourusername/flask-app.git
cd flask-app
python3 -m venv venv
source venv/bin/activate      # On macOS/Linux
# OR
venv\Scripts\activate         # On Windows
pip install -r requirements.txt
python server.py


Visit the app in your browser at:
http://localhost:8080
📡 API Endpoints
Route	Description	Query Parameters
/	Render homepage	–
/sum	Adds two numbers	num1, num2 (floats)
/sub	Subtracts two numbers	num1, num2 (floats)
/mul	Multiplies two numbers	num1, num2 (floats)

