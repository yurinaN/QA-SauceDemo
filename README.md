# QA Portfolio: SauceDemo

This repository contains QA checklists and detailed test cases for practicing **manual testing** on [SauceDemo](https://www.saucedemo.com/).

It covers the full user flow: **Login → Catalog → Product → Cart → Checkout**.

---

## Project Structure

All detailed test cases are in the **Test Cases** folder:

- Login Page.md
- Catalog Page.md
- Cart Page.md
- Checkout page.md
- Product Details Page.md

Each Markdown file contains **table-formatted test cases** with:

- Test Case ID
- Title
- Preconditions
- Steps
- Test Data
- Expected Result
- Actual Result
- Status
- Notes

Test Case IDs are **continuous across pages** to maintain clarity.

Preconditions are simplified when appropriate (e.g., “Product added to cart”) to keep test cases focused.

---

## How to Use

1. Navigate to the **Test Cases** folder.
2. Open the Markdown file for the page you want to test (e.g., `Cart Page.md`).
3. Follow each test case, and mark **Actual Result** and **Status** as you execute the tests.
4. You can also refer to the [Checklists.md](https://www.notion.so/Checklists.md) for a **high-level view** of the test items.

---

## Test Cases Overview

### Login Page

- Valid login
- Invalid username/password handling
- Error messages
- UI elements visibility

### Catalog / Product Page

- Sorting dropdown functionality
- Add/Remove products to/from cart
- Navigation to product detail page
- Cart badge updates
- Edge cases (rapid actions, broken links/images)

### Cart Page

- Product details in cart
- Quantity and removal behavior
- Continue shopping & checkout navigation
- Empty cart behavior

### Checkout Page

- Checkout form validations (First Name, Last Name, Zip/Postal Code)
- Overview page totals and product details
- Finish and Cancel buttons behavior
- Checkout complete confirmation

---

This portfolio demonstrates attention to both **UI elements and functional workflows**, including **edge and negative test cases**, making it a **comprehensive showcase of manual QA skills**.
