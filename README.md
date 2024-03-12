# writing-test-specifications

# Unit Tests:
 1. A function called "multiplication" that returns the      product of the two input numbers.

# Tests = 
 - Expect multiply(a, b) to be a number
 - Expect multiply(2, 3) to be equal to 6
 - Expect mutliply("b", 3) to be an error
 - Expect multiply(0, a) to be 0

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]

* Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:

* What should happen with unexpected inputs?

* What kinds of unexpected inputs should we worry about?

* What should happen when there are multiples of the same odd number in the arrays? (Hint: We gave you the answer to this one in the example above.)

# Tests =
- Expect multiple of the same odd number to be only one of that odd number
- Expect array to be from least to greatest
- Expect function to combine both arrays
- Expect function to push both arrays into an empty array


# Functional Tests:
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

* Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:

* What should happen if the cart is empty?

* What needs to be shown to the user at each step of check out?

* What behaviors of this feature does the prompt miss or gloss over?

* Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!

- When accessing the checkout page, verify that the page displays options for logging in or checking out as guest.
Test both options are clickable and lead to their directed inputs.
- When choosing the "checkout as guest". Verify that the user is prompted to enter their payment method info and that they are able to input the information and save it.
- When choosing the "log in" option, verify that the user is prompted to enter their username and password. Additionally, test if there's an option to sign up for a new account if they don't have one