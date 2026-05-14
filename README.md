# 🧪 Test Documentation — Etsy.com

Manual QA artifacts for [Etsy.com](https://www.etsy.com/) — a global marketplace for handmade, vintage, and creative goods.

---

## 📌 About This Repository

This repository contains manual testing documentation created as part of my QA practice. The goal is to demonstrate skills in test design, defect reporting, and structured QA documentation.

**Testing scope:** Web application (desktop browser)  
**Environment:** Chrome 148 / Ubuntu 20  
**Testing type:** Functional, UI, Regression (manual)

---

## 📁 Repository Structure

```
test-documentation/
│
├── test-plan/
│   └── test-plan.md               # Scope, objectives, approach, risks
│
├── test-cases/
│   ├── TC_auth.md                 # Registration & Login
│   ├── TC_search.md               # Search & Filters
│   ├── TC_product-page.md         # Product page
│   ├── TC_cart.md                 # Shopping cart
│   └── TC_checkout.md             # Checkout flow
│
├── checklists/
│   ├── CL_homepage.md             # Homepage smoke checklist
│   ├── CL_mobile-adaptive.md      # Mobile responsiveness
│   └── CL_cross-browser.md        # Cross-browser compatibility
│
└── bug-reports/
    ├── BUG-001_search-filter.md
    ├── BUG-002_cart-quantity.md
    └── BUG-003_auth-error-message.md
```

---

## 📋 Test Plan

**Tested modules:**
- Authentication (sign up / sign in / OAuth via Google)
- Search & Filters (keyword, category, price range, location)
- Product Page (images, reviews, seller info, favourites)
- Shopping Cart (add/remove items, quantity update)
- Checkout Flow (address, payment, order confirmation)

**Out of scope:** Payment processing (real transactions), seller dashboard, mobile apps

**Test approach:** Black-box, exploratory + scripted testing

---

## ✅ Test Cases Overview

| ID | Module | Title | Priority |
|----|--------|-------|----------|
| TC001 | Reg | Successful user registration with valid data via email | High |
| TC002 | Reg | Successful user registration with valid data via Google | High |
| TC003 | Reg | Successful user registration with valid data via Apple account | High |
| TC004 | Reg | Successful user registration with valid data via Facebook account | High |
| TC005 | Reg | Successful user registration with valid data via email and password | High |

> Full test cases with steps and expected results: [`test-cases/`](./test-cases/)

---

## 🐛 Bug Reports Overview

| ID | Title | Severity | Status |
|----|-------|----------|--------|
| ETSY-1 | No warning for empty coupon activation. | Minor | Open |
| ETSY-2 | "City" field accepts numeric values without error | Minor | Open |
| ETSY-5 | Invalid profile image upload redirects to another page | Minor | Open |

> Full bug reports with screenshots and steps to reproduce: [`bug-reports/`](./bug-reports/)

---

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| Chrome DevTools | Console errors, network tab, responsive mode |
| Jira (local) | Bug tracking practice |
| Markdown | Documentation format |
| Git / GitHub | Version control |

---

## 👤 Author

**[roman m.]**  
Junior QA Engineer  
📧 2698092@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dotdev/)  

> Open to Junior QA opportunities — manual testing with basic Java/Selenium skills.
