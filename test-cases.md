# My QA Test Cases

## Test Case 1 — Valid Login
Site: saucedemo.com
Steps:
1. Go to saucedemo.com
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click Login button

Expected Result: User lands on the home page
Status: Pass

---

## Test Case 2 — Invalid Login
Site: saucedemo.com
Steps:
1. Go to saucedemo.com
2. Enter wrong username and password
3. Click Login button

Expected Result: Error message appears
Status: Pass

---

## Test Case 3 — Empty Login
Site: saucedemo.com
Steps:
1. Go to saucedemo.com
2. Leave username and password empty
3. Click Login button

Expected Result: Error message "Username is required" appears
Status: Pass

---

## Test Case 4 — Add item to cart
Site: saucedemo.com
Steps:
1. Login with valid credentials
2. Click on any product
3. Click "Add to Cart" button

Expected Result: Cart icon shows 1 item
Status: Pass

---

## Test Case 5 — Logout
Site: saucedemo.com
Steps:
1. Login with valid credentials
2. Click the menu icon (top left)
3. Click Logout

Expected Result: User is redirected back to login page
Status: Pass
