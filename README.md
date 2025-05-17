# 🌐 Language Detection API  

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Dockerized](https://img.shields.io/badge/Containerized-Docker-blue)  
![Deployment](https://img.shields.io/badge/Deployed-Heroku-purple)  

---

## 🚀 Overview  

This project provides an end-to-end **Language Detection API** powered by machine learning and deployed using **FastAPI**, **Docker**, and **Heroku**. It takes raw text input and accurately predicts the language using a trained ML pipeline. The solution is scalable, containerized, and ready for deployment.

---

## 📂 Project Features  

- 📌 **FastAPI** backend for blazing-fast API responses  
- 📖 **Pre-trained ML Model** using scikit-learn pipeline (included as `.pkl` file)  
- 📊 **Dataset:** Uses language samples provided in `Language Detection.csv`  
- 📦 **Dockerized:** Fully containerized for easy deployment  
- ☁️ **Heroku-Ready:** Pre-configured with `heroku.yml` for cloud deployment  
- 🧩 **Extensible:** Easily swap out models or expand to detect additional languages  

---

## 📖 Installation  

### 🐍 Create Environment  

```bash
git clone https://github.com/Himanshu12328/Language_Dectection.git
cd Language_Dectection
pip install -r requirements.txt
