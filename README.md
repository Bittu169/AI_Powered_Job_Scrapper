
# AI-Powered LinkedIn Job Scraper

An **AI-powered web application** that automates the scraping of job listings from LinkedIn and extracts required skills from job descriptions using **Natural Language Processing (NLP)**. This project combines **web scraping, AI-based skill extraction, and an interactive web interface** for live job search and filtering.

---

## 🔹 Features

- Scrapes job listings based on:
  - Location (city/state/country)
  - Job role/position
  - Experience level (Internship, Entry, Associate, Mid-Senior)
  - Work type (On-site, Hybrid, Remote)
  - Time filter (Past 24 hours, Past week, Past month)
- **AI-powered skill extraction** from job descriptions using Flair NLP
- Filters jobs based on **preferred technologies** (e.g., Python, Machine Learning, AI)
- **Interactive Gradio UI** for live job results
- Export job data to **CSV** for further analysis
- Multi-threaded scraping for better performance

---

## 🔹 Technology Stack

- **Python** – Core programming language
- **Gradio** – Interactive web app interface
- **BeautifulSoup** – HTML parsing and web scraping
- **Requests** – HTTP requests handling
- **Pandas** – Data storage and manipulation
- **Flair NLP** – AI-based skill extraction
- **Threading** – Background scraping and live updates

---

## 🔹 How It Works

1. User enters **cities, states, positions, work types, experience levels, time filter**, and optional technology keywords.
2. The scraper constructs LinkedIn job search URLs based on user inputs.
3. Fetches job cards and visits each job page.
4. Extracts **job description** and uses **Flair NLP** to identify skills.
5. Filters jobs based on preferred technologies.
6. Displays live results in a **Gradio web app**.
7. Optionally exports results to **CSV**.

---
## 🎥 Demo Video
▶️ [Watch Demo on YouTube](https://youtu.be/GG1IQ8yhasg?si=dOBNHOo2QjUmP7Vo)

---
## 🔹 Usage

1. Clone the repository:

```bash
git clone https://github.com/Bittu169/AI_Powered_Job_Scrapper.git
cd AI_Powered_Job_Scrapper
