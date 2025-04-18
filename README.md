# 🐳 Python Flask App — CI/CD Pipeline with Docker & GitHub Actions

This project is a minimal Python Flask web application with a fully working CI/CD pipeline using **GitHub Actions** and **Docker**.

It was built as a personal DevOps learning project by [Umesh Thorat], step by step — from source code to running container.

---

## 🚀 Features

- Simple Flask app (`app.py`) that returns a greeting
- Dockerfile to containerize the app
- GitHub Actions workflow to:
  - Set up Python environment
  - Install dependencies
  - Run unit tests
  - Build Docker image
  - Run the container inside CI
  - **Test the running container** using `curl` + response validation

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Python + Flask | Web application |
| Pytest | Testing |
| Docker | Containerization |
| GitHub Actions | CI pipeline |
| YAML | Workflow definition |

---

## 🛠️ How to Run Locally

1. Clone this repo  
2. (Optional) Create a virtual environment  
3. Install dependencies  
4. Run Flask server

```bash
pip install -r requirements.txt
python app.py
