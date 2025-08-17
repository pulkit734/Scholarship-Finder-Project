# Scholarship Finder

## Overview

**Scholarship Finder** is a full-stack web application that helps students discover and apply for the best scholarships tailored to their academic profile. The platform scrapes data from major scholarship sources, stores it in MongoDB, and uses AI-based ranking algorithms to recommend the most relevant scholarships through a modern, responsive frontend.

---

## Features

- **User Registration & Authentication**
  - Register, login (JWT-secured), and maintain personal/educational profiles.
- **Personalized Recommendations**
  - AI/ML-powered engine matches scholarships using location, gender, CGPA, academic qualification, and sentiment analysis of descriptions.
- **Automatic Scholarship Aggregation**
  - Python scripts scrape scholarships from platforms like Scholarships.com, Fastweb, and Buddy4Study; ingest into MongoDB in real time.
- **Modern Frontend Dashboard**
  - Built with React and Tailwind CSS for a fast, intuitive user experience, including profile editing and instant recommendation updates.
- **API-driven Backend**
  - Node.js/Express REST API manages users, scholarships, authentication, and profile updates.
- **Robust Architecture**
  - Modular, extensible codebase ready for scale and new features.

---

## Tech Stack

| Layer      | Technology                                      |
| ---------- | ----------------------------------------------- |
| Frontend   | React.js, Tailwind CSS                          |
| Backend    | Node.js, Express.js, JWT                        |
| Database   | MongoDB (Atlas)                                 |
| Scrapers   | Python (Selenium, PyMongo, dateutil, regex)     |
| AI Logic   | TextBlob & VADER Sentiment (Python)             |

---

## Getting Started


### 1. Setup Backend

cd backend>
npm install>
npm start>


### 2. Setup Frontend

cd frontend>
npm install>
npm start



### 3. Run Web Scrapers

- Ensure Python 3 with all dependencies: `selenium`, `pymongo`, `dateutil`, `textblob`, `vaderSentiment`.
- Update ChromeDriver paths in `.py` files if required.
- Run:
python scholarships_com.py > 
python buddy4u_com.py > 
python fastweb_com.py

---

## 👨‍💻 Author
**Pulkit Jain**  
💼 GitHub: [@pulkit734](https://github.com/pulkit734)

---

⭐ If you like this project, don’t forget to give it a **star** on GitHub! ⭐
