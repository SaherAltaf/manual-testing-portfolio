# Test Plan – Sauce Demo

## 1. Objective
Make sure the main shopping flow of Sauce Demo works correctly: login, products, cart, checkout and logout.

## 2. Scope
- **In scope:** login, product list and sorting, product details, cart, checkout, logout
- **Out of scope:** performance, security, API and mobile testing

## 3. Test Approach
- Manual functional testing with positive and negative test cases
- UI checks for buttons, labels and error messages
- Exploratory testing with `problem_user` to find bugs

## 4. Test Environment
- **URL:** https://www.saucedemo.com
- **Browser:** Google Chrome (latest) on Windows
- **Test users:** `standard_user`, `locked_out_user`, `problem_user` (password: `secret_sauce`)

## 5. Entry and Exit Criteria
- **Start testing when:** the site is up and test users can log in
- **Stop testing when:** all test cases are run and every bug is reported with steps and a screenshot

## 6. Deliverables
- Test cases: `test-cases.csv`
- Bug reports: GitHub Issues of this repo
- Test summary: in `README.md`
