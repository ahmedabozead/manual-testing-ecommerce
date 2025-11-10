🧾 Test Summary Report – E-Commerce Website (Manual Testing)
🧠 Objective

The purpose of this testing was to validate the main user functions of the Tricentis Demo Web Shop website and ensure that all critical workflows operate as expected.

🧩 Scope of Testing

Testing covered:

User registration & login

Product search

Add to cart & remove items

Checkout process

Error message validation

Basic UI and navigation checks

⚙️ Test Environment
Item	Details
Application	Tricentis Demo Web Shop
URL	https://demowebshop.tricentis.com

Browser	Google Chrome (Latest)
OS	Windows 10
Network	Stable internet connection
📋 Test Execution Summary
Total Test Cases	Passed	Failed	Execution Rate
34	30	4	100%
🐞 Defect Summary
Bug ID	Severity	Status	Description
BUG001	High	Open	Account not locked after multiple failed login attempts
BUG002	Medium	Open	Missing password visibility toggle
BUG003	Critical	Open	Password reset email not received
BUG004	Critical	Open	Order confirmation email not sent
📈 Key Findings

All main flows (login, register, cart, checkout) function as expected.

Some email and security-related issues were found.

UI and navigation are smooth with no major usability issues.

🧾 Overall Result

✅ Application Status: Stable
⚠️ Pending Issues: 4 open bugs (to be fixed before release)
📊 Quality Rating: 90% functional stability

💡 Recommendations

Fix critical email and login security bugs.

Add “Show/Hide Password” option for better UX.

Re-run regression test after bug fixes.