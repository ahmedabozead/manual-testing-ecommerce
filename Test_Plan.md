# 🧾 Test Plan – E-Commerce Website (Manual Testing)

---

## 🎯 1. Objective
The purpose of this Test Plan is to ensure that all core functionalities of the **Demo Web Shop** operate as expected through manual testing.  
The testing focuses on verifying the **Login, Registration, Product Search, Add to Cart, and Checkout** modules, ensuring a smooth and bug-free user experience.

---

## 🧱 2. Scope

### ✅ In Scope
- User Login & Registration (with input validation)
- Product Search functionality
- Add to Cart and Cart Management
- Checkout process and order confirmation
- UI validation and error message handling

### 🚫 Out of Scope
- Performance and Load Testing  
- API Testing  
- Security and Penetration Testing  

---

## 🧭 3. Test Strategy
- **Testing Type:** Manual Functional Testing  
- **Approach:** Positive and Negative test cases will be executed for all user-facing modules.  
- **Test Design Technique:**  
  - Equivalence Partitioning  
  - Boundary Value Analysis  
  - Error Guessing  
- **Test Levels:**  
  - Unit Testing *(handled by dev team)*  
  - Integration Testing *(partial)*  
  - System Testing *(focus of this project)*  
  - Regression Testing *(for fixed bugs)*  

---

## ⚙️ 4. Test Environment

| **Component** | **Details** |
|----------------|-------------|
| **Application URL** | [https://demowebshop.tricentis.com](https://demowebshop.tricentis.com) |
| **Browser** | Google Chrome (Latest Version) |
| **Operating System** | Windows 10 |
| **Network** | Stable Internet Connection |
| **Tools** | Excel, Postman (optional), GitHub |

---

## 👥 5. Roles & Responsibilities

| **Role** | **Name** | **Responsibilities** |
|-----------|-----------|----------------------|
| QA Tester | Ahmed Abozead | Writing and executing test cases, reporting bugs |
| QA Lead | — | Review and approve test cases and test results |
| Developer | — | Fix reported defects |

---

## 📋 6. Test Deliverables

| **Document** | **Description** |
|---------------|----------------|
| **Test Plan** | Defines scope, objectives, and testing approach |
| **Test Cases (.xlsx)** | Detailed steps, expected vs actual results |
| **Bug Report (.xlsx)** | Logged defects with severity, priority, and status |
| **Test Summary** | Overview of test results and defect statistics |

---

## 🚪 7. Entry Criteria
- Functional requirements are clearly defined and approved  
- Application is deployed to a stable test environment  
- All required test data and credentials are available  

---

## 🚪 8. Exit Criteria
- All critical and high-severity defects are fixed  
- At least 95% of test cases executed  
- All test deliverables completed and reviewed  
- Test summary report submitted and approved  

---

## 🕓 9. Test Schedule

| **Activity** | **Duration** | **Owner** |
|---------------|--------------|------------|
| Requirement Analysis | 8 hours | QA Tester |
| Test Case Writing | 1 day | QA Tester |
| Test Execution | 1 day | QA Tester |
| Bug Reporting & Retesting | 1 day | QA Tester |
| Review & Sign-off | 0.5 day | QA Lead |

---

---

## 📊 11. Test Summary Overview

| **Total Test Cases** | **Passed** | **Failed** | **Execution %** |
|------------------------|-------------|-------------|-----------------|
| 34 | 30 | 4 | 100% |

---

## 🐞 12. Defects Found

| **Bug ID** | **Severity** | **Description** |
|-------------|--------------|-----------------|
| BUG001 | High | Account not locked after multiple failed login attempts |
| BUG002 | Medium | Missing password visibility toggle |
| BUG003 | Critical | Password reset email not received |
| BUG004 | Critical | Order confirmation email not sent |

---

## ✅ 13. Conclusion
- All major functionalities are **working as expected**.  
- Minor defects related to **security and email notification** were identified.  
- Application is **ready for user acceptance testing (UAT)** or demo use.  
- Further regression testing is recommended after defect fixes.

---

📌 **Tester:** Ahmed Abozead  
🧑‍💻 **Role:** QA Tester  
🗓️ **Date:** November 2025  
📍 **Testing Type:** Manual Functional Testing  

