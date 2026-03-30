# Login Page

## Page Layout & UI

- [ ]  Page loads successfully at [saucedemo.com](https://www.saucedemo.com/)
- [ ]  Sauce Labs logo is displayed correctly
- [ ]  Username field is visible
- [ ]  Password field is visible
- [ ]  Login button is visible and enabled

## Functional Tests

- [ ]  Successful login with valid credentials (e.g., standard_user/secret_sauce)
- [ ]  Invalid username shows error message
- [ ]  Invalid password shows error message
- [ ]  Empty username shows error message
- [ ]  Empty password shows error message
- [ ]  Both fields empty shows error message

## Password Field

- [ ]  Password input masks typed charecters
- [ ]  Paste functionality works in password field

## Login Button

- [ ]  Login works on button click
- [ ]  Login works when pressing Enter key in username or password field

## Navigation

- [ ]  Successful login redirects to the Products / Inventory page (title: "Products")

## Negative / Edge Cases

- [ ]  Test SQL/script injection in username and password fields
- [ ]  Test extremly long username or password
- [ ]  Test special characters in username or password

# Products Page

## Page Layout & UI

- [ ]  Page header with "Swag Labs" logo, title "Products", and shopping cart icon is visible
- [ ]  Product images load correctly
- [ ]  Product names are displayed and readable
- [ ]  Product descriptions are visible
- [ ]  Product prices are displayed correctly
- [ ]  “Add to cart” buttons are presented for all products
- [ ]  Page footer is visible
- [ ]  Cart icon badge shows correct item count (starts at 0)

## Product Sorting

- [ ]  Sorting dropdown is visible and functional
- [ ]  Options work correctly: Name (A to Z), Name (Z to A), Price (low to high), Price (high to low)
- [ ]  Sorting changes product order correctly

## Add to Cart / Remove from Cart

- [ ]  Clicking “Add to cart” updates tha cart icon count
- [ ]  Clicking “Add to cart” changes button text to “Remove”
- [ ]  Clicking “Remove” updates tha cart icon count
- [ ]  Clicking “Remove” changes button text to “Add to cart”

## Product Details / Navigation

- [ ]  Clicking produc name navigates to product detail page
- [ ]  Clicking product image navigates to product detail page
- [ ]  “Back to products” button on product page returns to products page

## Responsivness

- [ ]  Page displays correctly on desktop, tablet, and mobile viewports
- [ ]  No overlapping elements, cut-off text, or buttons

## Negative / Edge Cases

- [ ]  Verify "Add to cart" / "Remove" still works correctly after sorting
- [ ]  Verify no broken images or links on the page
- [ ]  Check cart behavior if adding/removing products quickly
- [ ]  Verify cart badge updates in real-time

# Product Details Page

## Page Layout & UI

- [ ]  Product name displayed correctly
- [ ]  Product description visible and readable
- [ ]  Product price displayed correctly
- [ ]  Product image displayed correctly
- [ ]  “Add to cart”/"Remove” button is visible and functional
- [ ]  “Back to products” button is visible and functional
- [ ]  Page layout is correct

## Functional Tests

- [ ]  Clicking “Add to cart”/“Remove” updates the cart icon bage
- [ ]  Button text toggles between "Add to cart" and "Remove”
- [ ]  “Back to products” button returns to products page

# Cart Page

## Page Layout & UI

- [ ]  Cart page opens successfully
- [ ]  List of added products is displayed
- [ ]  Product name, description (short), price, and quantity are shown correctly
- [ ]  “Remove” button is visible and clickable for each item
- [ ]  “Continue shopping” button is visible and clickable
- [ ]  “Checkout” is visible and clickable
- [ ]  Page layout is correct

## Functional Tests

- [ ]  Added product appear in the cart with correct details
- [ ]  Product quantity matches the number added
- [ ]  Clicking “Remove” deletes product from the cart and updates the page
- [ ]  Cart badge count updates after removal
- [ ]  Clicking “Continue shopping” redirects to the products page
- [ ]  Clicking “Checkout” redirects to the checkout page

## Negative / Edge Cases

- [ ]  Cart displays correctly with multiple products
- [ ]  Cart updates correctly when removing multiple products
- [ ]  Cart is empty after removing all products
- [ ]  Empty cart page displays correctly

# Checkout Page

## Page Layout & UI

- [ ]  Page opens successfully
- [ ]  First Name, Last Name, and Zip/Postal Code fields are visible
- [ ]  “Continue” button is visible and clickable
- [ ]  “Cancel” button is visible and clickable
- [ ]  Error messages display for invalid/empty inputs
- [ ]  Page layout is correct

## Functional Tests

- [ ]  User can proceed with valid checkout information
- [ ]  Empty First Name shows error message
- [ ]  Empty Last Name shows error message
- [ ]  Empty Zip/Postal Code shows error message
- [ ]  Clicking “Continue” redirects to overview page
- [ ]  Clicking “Cancel” returns to cart page

## Checkout Overview Page

- [ ]  Page opens successfully
- [ ]  Selected products are listed with correct names, prices, and quantities
- [ ]  Item total, tax, and final total are calculated correctly
- [ ]  “Finish” button is visible and clickable
- [ ]  Clicking “Finish” redirects to order completion page
- [ ]  “Cancel” button is visible and clickable
- [ ]  Clicking “Cancel” redirects to products page

## Checkout Complete Page

- [ ]  Confirmation message is displayed
- [ ]  Page loads correctly
- [ ]  “Back Home” button is visible and clickable
- [ ]  Clicking “Back Home” redirects to products page
