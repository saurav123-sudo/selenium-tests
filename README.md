# Selenium Automation Framework - Advance Level - 100% PASS

**Author:** Saurabh Anjansonde  
**Date:** 20-10-2026  
**Project:** mytest / E-commerce & Login Testing

## 🏆 Results
- **Total Tests:** 7 (2 Search + 5 Login)
- **Passed:** 7
- **Failed:** 0
- **Success Rate:** 100%

![PASS](https://img.shields.io/badge/All%20Tests-PASS-brightgreen)

## 📁 Project Structure (Company Standard)
```
github_selenium_project/
├── pages/
│   └── login_page.py       # Page Object Model (POM)
├── tests/
│   ├── test_search.py      # Flipkart & Amazon Search Tests
│   └── test_login_advanced.py  # 5 Login Scenarios - 100% PASS
├── reports/
│   └── report.html         # HTML Report
├── requirements.txt
├── .gitignore
└── README.md
```

## ✅ Tests Covered

### 1. Search Testing
- Flipkart: `https://www.flipkart.com/search?q=iPhone` - PASS
- Amazon: `https://www.amazon.in/s?k=iPhone` - PASS
- **Exception Handled:** `ElementClickInterceptedException`, `NoSuchWindowException`

### 2. Advance Login Testing (5 Scenarios - 100% PASS)
| Test | User | Expected | Result |
|------|------|----------|--------|
| Valid Login | standard_user | PASS | PASS |
| Locked User | locked_out_user | ERROR | PASS |
| Wrong Password | standard_user | ERROR | PASS |
| Wrong Username | wrong_user | ERROR | PASS |
| Empty User | EMPTY | ERROR | PASS |

## 🧠 Advanced Concepts Implemented
- **Page Object Model (POM)** - `pages/login_page.py`
- **Explicit Wait** - `WebDriverWait`
- **Data-Driven Testing** - 5 users in one file
- **Negative Testing** - Invalid, empty, locked users
- **Exception Handling** - 2 major Selenium exceptions fixed
- **Reporting** - Console + HTML Report

## 🚀 How to Run

```bash
# 1. Clone
git clone https://github.com/YOUR_USERNAME/selenium-tests.git
cd selenium-tests

# 2. Install
pip install -r requirements.txt

# 3. Run Search Tests
python tests/test_search.py

# 4. Run Advance Login Tests (5 Tests)
python tests/test_login_advanced.py
```

## 📊 My Learning Journey
Day 1: `i dont khow` → Google TestCase Studio PASS → Flipkart PASS → Amazon PASS → Basic Login PASS → Advance 5 Tests 100% PASS

## 📝 Resume Line
> Built Selenium automation framework with POM, tested Flipkart/Amazon search and 5 login scenarios (100% PASS), handled ElementClickInterceptedException & NoSuchWindowException, implemented Explicit Waits & Data-Driven Testing.

## 🔗 Website Tested
- https://www.saucedemo.com/ (Login)
- https://www.flipkart.com/search?q=iPhone
- https://www.amazon.in/s?k=iPhone
