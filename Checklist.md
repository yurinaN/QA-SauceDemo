# Checklist for SauceDemo

# Login page

## Page Layout & UI

- Page loads successfully
- Logo is displayed correctly
- Username field is visible
- Password field is visible
- Login button is visible

## Functional Tests

- User can login with valid credentials
- Invalid username shows error message
- Invalid password shows error message
- Empty username shows error message
- Empty password shows error message

## Password Field

- Password input masks typed charecters
- Paste functionality works in password field

## Login Button

- Login works on click
- Login works when pressing Enter key

## Navigation

- Successful login redirects to the catalog page

## Negative / Edge Cases

- Test SQL or script injection in username and password fields
- Test extremly long username or password
- Test special characters in username or password

# Catalog page

## Page Layout & UI

- Page header is visible
- Product images are displayed correctly
- Product names are displayed and readable
- Product prices are visible
- “Add to cart” buttons are presented for all products
- Page footer is visible

## Product Sorting

- Sorting dropdown works (e.g., Name A-Z, Price Low-High)
- Sorting changes product order correctly

## Add to Cart / Remove from Cart

- Clicking “Add to cart” updates tha cart icon count
- Clicking “Add to cart” changes button text to “Remove”
- Clicking “Remove” updates tha cart icon count
- Clicking “Remove” changes button text to “Add to cart”

## Product Details / Navigation

- Clicking produc name navigates to product detail page
- Clicking product image navigates to product detail page
- “Back to products” button on product page returns to catalog page

## Responsivness

- Page displays correctly on different screen sizes
- Buttons and text are not cut off

## Negative / Edge Cases

- Verify “Add to cart” works after sorting products
- Verify no broken images or links on the page
- Check cart behavior if adding/removing products quickly

# Product Details

## Page Layout & UI

- Product name is displayed correctly
- Product description is visible and readable
- product price is displayed correctly
- Product image is displayed correctly
- “Add to cart” button is visible and clickable
- “Back to products” button is visible and clickable
- Page layout is correct

## Functional Tests

- Clicking “Add to cart” updates tha cart icon count
- Clicking “Add to cart” changes button text to “Remove”
- Clicking “Remove” updates tha cart icon count
- Clicking “Remove” changes button text to “Add to cart”
- “Back to products” button on product page returns to catalog page

# Cart page

## Page Layout & UI

- Cart page opens successfully
- List of added products is displayed
- Product name is displayed correctly
- Product discription is displayed correctly
- Product quantity is displayed correctly
- “Remove” is visible and clickable for each product
- “Continue shopping” is visible and clickable
- “Checkout” is visible and clickable
- Page layout is correct

## Functional Tests

- Added product appear in the cart
- Correct products are displayed in the cart
- Product quantity matches number of added items
- Clicking “Remove” deletes product from cart
- Cart updates after removing product
- Clicking “Continue shopping” redirects to catalog page
- Clicking “Checkout” redirects to checkout page

## Negative / Edge Cases

- Cart displays correctly with multiple products
- Cart updates correctly when removing multiple products
- Cart is empty after removing all products
- Empty cart page displays correctly

# Checkout page

## Page Layout & UI

- Checkput page opens successfully
- First Name field is visible
- Last Name field is visible
- Zip/Postal Code field is visible
- “Continue” button is visible and clickable
- “Cancel” button is visible and clickable
- Error messages are displayed correctly
- Page layout is correct

## Functional Tests

- User can proceed with valid checkout information
- Empty First Name shows error message
- Empty Last Name shows error message
- Empty Zip/Postal Code shows error message
- Clicking “Continue” redirects to overview page
- Clicking “Cancel” returns to cart page

## Checkout Overview Page

- Overview page opens successfully
- Selected products are displayed correctly
- Product names, prices, and quantities are correct
- Total prices is calculated correctly
- “Finish” button is visible and clickable
- Clicking “Finish” redirects to order completion page
- “Cancel” button is visible and clickable
- Clicking “Cancel” redirects to catalog page

## Checkout Complete Page

- Confirmation message is displayed
- Order completion page loads correctly
- “Back Home” button is visible and clickable
- Clicking “Back Home” redirects to cataloge page