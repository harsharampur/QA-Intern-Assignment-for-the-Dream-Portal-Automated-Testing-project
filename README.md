# QA-Intern-Assignment-for-the-Dream-Portal-Automated-Testing-project
This project is a comprehensive UI Functional Test Automation suite for the Dream Portal web app, developed as part of a QA Intern Assignment. The automation suite is built using Selenium with Java, following the Page Object Model (POM) design pattern and TestNG for assertions and test management. 
# Dream Portal - QA Automation Assignment 🚀

This project automates the functional testing of the Dream Portal web app using Selenium (Java) with TestNG and Page Object Model (POM).

🔗 Live site: https://arjitnigam.github.io/myDreams/

---

## ✅ Features Covered

### 🔹 index.html – Home
- [x] Loading animation visibility
- [x] Main content and "My Dreams" button visibility
- [x] Button click opens `dreams-diary.html` and `dreams-total.html`

### 🔹 dreams-diary.html – Log Table
- [x] Exactly 10 dream entries
- [x] Valid dream types ("Good" / "Bad")
- [x] Each row has all 3 columns filled

### 🔹 dreams-total.html – Summary Page
- [x] Good Dreams = 6
- [x] Bad Dreams = 4
- [x] Total Dreams = 10
- [x] Recurring Dreams = 2
- [x] Recurring names include:
  - "Flying over mountains"
  - "Lost in maze"

---

## 🧠 Optional AI-Based Validation (Pending / Optional)

- [ ] Uses OpenAI or similar to classify dream names
- [ ] Compares AI classification to actual dream type

---

## 🛠 Tech Stack

- Java + Selenium WebDriver
- TestNG (Assertions + Reports)
- Bonigarcia WebDriverManager
- Page Object Model (POM)

---

## 📂 How to Run

1. Clone the repo
2. Install dependencies via Maven/Gradle
3. Run with:

```bash
mvn clean test
# OR
testng testng.xml
