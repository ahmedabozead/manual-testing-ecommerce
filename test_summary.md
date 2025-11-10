# 📊 Test Summary Report – E-Commerce Website (Manual Testing)

## 🧩 1. Overview
This Test Summary Report provides a comprehensive overview of the **manual functional testing** performed on the *Demo Web Shop* application.  
Testing focused on verifying critical user flows such as **Login, Registration, Product Search, Cart Management, and Checkout** to ensure a smooth and reliable shopping experience.

---

## 🧱 2. Test Execution Details

| Item | Description |
|------|--------------|
| **Project Name** | E-Commerce Website (Demo Web Shop) |
| **Testing Type** | Manual Functional Testing |
| **Tester** | Ahmed Abozead |
| **Test Environment** | Windows 10 / Google Chrome (Latest) |
| **Execution Period** | 3 Days (Including Bug Reporting) |
| **Tools Used** | Excel (Test Cases & Bug Report), Postman (optional), GitHub (Documentation) |

---

## 🧪 3. Test Summary Statistics

| Metric | Count | Percentage |
|--------|--------|-------------|
| **Total Test Cases** | 34 | 100% |
| **Passed** | 30 | 88% |
| **Failed** | 4 | 12% |
| **Execution Coverage** | 100% | ✅ Fully Executed |

---

## 🐞 4. Defect Summary

| Bug ID | Severity | Description | Status |
|--------|-----------|--------------|---------|
| **BUG001** | High | Account not locked after multiple failed login attempts | Open |
| **BUG002** | Medium | Missing password visibility toggle | Open |
| **BUG003** | Critical | Password reset email not received | Open |
| **BUG004** | Critical | Order confirmation email not sent | Open |

### 🔍 Severity Distribution
- 🟥 **Critical:** 2 Bugs (50%)  
- 🟧 **High:** 1 Bug (25%)  
- 🟨 **Medium:** 1 Bug (25%)

---

## ⚙️ 5. Major Findings
1. **Email System Defects:** Password reset and order confirmation emails are not being delivered.  
2. **Security Flaw:** The system does not lock the user account after repeated failed login attempts.  
3. **UI Improvement:** Missing password visibility toggle impacts usability.  
4. **Overall Stability:** Core user flows (search, add to cart, checkout) functioned correctly with minor UI issues.

---

## 📈 6. Recommendations
- Implement and test **email notification fixes**.
- Add **account lock mechanism** for failed logins.
- Enhance **UI/UX** by including password visibility toggle.
- Conduct **regression testing** after applying all fixes.
- Optionally perform **performance & API testing** in future iterations.

---

## ✅ 7. Conclusion
All **critical business workflows** have been successfully verified.  
Despite a few medium and high-severity issues, the system remains **functionally stable** and suitable for demonstration or user acceptance testing (UAT).  
Further testing is recommended post-defect resolution to ensure system reliability.

---

**📅 Date:** November 2025  
**👤 Tester:** Ahmed Abozead  
**🧑‍💻 Role:** QA Tester  
**📍 Testing Type:** Manual Functional Testing  
