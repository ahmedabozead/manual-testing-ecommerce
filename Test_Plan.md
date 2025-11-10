🧾 Test Plan – E-Commerce Website (Manual Testing)
🎯 Objective

To verify that all main functions of the demo e-commerce site work properly — login, register, search, add to cart, and checkout.

🧱 Scope

Included:

Login / Register

Search Product

Add to Cart

Checkout Process

Basic UI & Error Message Validation

Excluded:

API testing

Performance testing

⚙️ Environment
Item	Details
URL	https://demowebshop.tricentis.com

Browser	Google Chrome (latest)
OS	Windows 10
Network	Stable internet
🧰 Tools

Excel → Test Cases & Bug Report

Postman → API check (optional)

GitHub → Documentation upload

🕓 Timeline
Task	Duration
Requirement Analysis	 8 hrs
Test Case Writing	1 day
Execution	1 day
Bug Reporting	1 day
📊 Test Summary
Total Cases	Passed	Failed	Execution %
34	30	4	100%
⚠️ Bugs Found
Bug ID	Severity	Description
BUG001	High	Account not locked after multiple failed logins
BUG002	Medium	Missing password visibility toggle
BUG003	Critical	Password reset email not received
BUG004	Critical	Order confirmation email not sent
✅ Conclusion

Most main functions work correctly.
Some bugs found in login security and email notifications.
Overall, the system is stable for training/demo purposes.