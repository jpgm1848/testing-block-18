# Workshop 1 - Writing Test Specifications

## Unit Tests

## A function called multiplication | multiply (x: number, y: number)

### Happy Path

- Expect multiply (x,y) to be a number.
- Expect x and y parameters to be numbers.
- Expect if one of the parameters is negative for the product to be negative.
- Expect if both of the parameters are negative for the product to be negative.
- Expect if either of the parameters are 0 for the product to be zero.

### Unhappy Path

- Expect x and/or y to be a non-number data type to return an "error" message.
- Expect for any empty parameters to return an "error" message.

## A function called concatOdds(a, b)

### Happy Path

- Expect concatOdds(a, b) to return an array of the odd numbers in both arrays in ascending order.
- Expect a and b to be arrays.
- Expect if a and b are arrays without odd numbers to return a "There are no odd numbers in either array." message.
- Expect if any of the odd numbers are repeated, to only display them once.

### Unhappy Path

- Expect if one of the two parameters to not be array data types to return a message saying "Odd numbers of only one parameter are being displayed.".
- Expect if both of the parameters are not array data types to display an "error" message.

## Functional Tests

## Shopping Cart

## Happy Path

- Once I hit the checkout button, I should be prompted to have the option to create an account if I hit guest.
- Regardless of either outcome, I should be taken to a screen where I can begin to checkout.
- The checkout screen should have forms to fill out my shipping and billing information.
- After the shipping form, I should have an option to paste it to the billing information.
- The billing form should have an option to link to an outside payment service, such as PayPal or Shop.
- The end of the forms should have optional buttons to opt-in for marketing emails.
- The end of the forms should have an optional form to input a coupon code.
- Before finalizing the purchase, a screen should show a screen with the total price divided by costs (shipping, taxes, discounts, etc.).
- Upon finalizing the purchase, the screen should a screen indicating that the purchase was successful, a confirmation code, a receipt, and shipping information.
- Upon finalizing the purchase, the cart will be emptied.

### Unhappy Path

- If I select the checkout button with an empty cart, I will receive a message prompt notifying me that I cannot proceed with an empty cart.
- If I attempt to create an account that already exists, I will be prompted with an error message indicating that the account already exists. I will be given the option to reset my password.
- If I input incorrect payment information, I will be prevented from saving or using that card. I will be prompted to re-enter the correct payment details.
- If I do not complete the shipping information, I will not be allowed to finish the order until I fill out the shipping form.
- If I enter an incorrect coupon code, I will receive a message saying the coupon is incorrect or expired.
- If the card payment processing fails, I will be taken back to the checkout page with the cart intact.
