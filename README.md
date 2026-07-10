# Playwright Login Automation

## Overview

This project demonstrates basic browser automation using **Microsoft Playwright**.

The script automates the login process on a demo web application by performing the following actions:

- Opens the browser
- Navigates to the login page
- Enters username and password
- Clicks the Login button
- Executes automatically across Chromium, Firefox, and WebKit browsers

> **Target Website:** http://testaspnet.vulnweb.com/login.aspx  
> This is a publicly available vulnerable web application intended for learning and security testing.

---

## Technologies Used

- Playwright
- JavaScript
- Node.js

---

## Project Structure

```
playwright-login-automation/
│
├── tests/
│   └── login.spec.js
│
├── playwright.config.js
├── package.json
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/Gaddambhavyasree/Playwright.git
```

Install dependencies

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

---

## Running the Test

Run all tests

```bash
npx playwright test
```

Run only the login test

```bash
npx playwright test tests/login.spec.js
```

Generate HTML report

```bash
npx playwright show-report
```

---

## Automation Flow

```
Launch Browser
      │
      ▼
Open Login Page
      │
      ▼
Enter Username
      │
      ▼
Enter Password
      │
      ▼
Click Login
      │
      ▼
Complete Test
```

## Author

**Bhavya Sree Gaddam**

Cybersecurity Student | Web Application Pentesting | AI SOC Enthusiast
