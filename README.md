## 🎓 Smart Campus AI — Decision Support System

An end-to-end AI pipeline built as an AL2002 (AI) Capstone Project.

### 🤖 What it does
A Flask-based web system that handles student/faculty campus requests 
through a modular AI pipeline — from natural language-style input to 
a fully structured decision response.

### ⚙️ Modules
| Module | Role |
|---|---|
| Preprocessor | Input validation & normalization |
| Router | Selects which AI modules to run |
| ANN (Perceptron + MLP) | Priority prediction (urgent / normal / low) |
| Logic KB (FOL) | Eligibility & policy checking via First-Order Logic |
| CSP Scheduler | Room/slot assignment using Constraint Satisfaction |
| Search (BFS, A*, UCS+) | Campus navigation with multiple algorithms |
| Response Builder | Final structured JSON response |

### 🚀 Run locally
pip install flask
cd smart_campus
python app.py
# Open http://localhost:5000

### 🛠️ Tech Stack
Python · Flask · Vanilla JS · ANN from scratch · FOL inference engine · 
CSP solver · 8 search algorithms (BFS, DFS, A*, UCS, IDS, RBFS...)
