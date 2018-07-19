# redbubble

## Instructions
Create a price calculator command-line program. Use any language you like.

### Functional requirements
Your program should take two command-line arguments:
1. a JSON file representing a cart, and
2. a JSON file representing a list of base prices.
* The cart schema is available at: [/cart.schema.json](https://take-home-test.herokuapp.com/cart.schema.json). Some example carts are available at: [/cart-4560.json](https://take-home-test.herokuapp.com/cart-4560.json), [/cart-9363.json](https://take-home-test.herokuapp.com/cart-9363.json), [/cart-9500.json](https://take-home-test.herokuapp.com/cart-9500.json), and [/cart-11356.json](https://take-home-test.herokuapp.com/cart-11356.json). 
* The base price schema is available at: [/base-prices.schema.json](https://take-home-test.herokuapp.com/base-prices.schema.json). An example of base prices is available at: [/base-prices.json](https://take-home-test.herokuapp.com/base-prices.json).
* You can assume that the options for a product-type are constant. 
For example, if the first record with the product-type 'hoodie' in the list of base prices only has the options 'colour' and 'size', all records with the product-type 'hoodie' in the list of base prices will have the options 'colour' and 'size' and will have no other options.
* Calculate the price for one item as follows: (base_price + round(base_price * artist_markup in cents)) * quantity
* Your program should output the total price in cents followed by a newline character. 
As an aid in testing your program, the name of each example cart file mentioned above includes the expected total price for that cart given the base prices in the example base prices file mentioned above.
* Your program should handle products with any options, even ones not found in the sample files.
* The time your program takes to calculate a price should be constant with respect to the number of base prices. (In real life, Redbubble currently has more than 1,000 base prices.)
* You need not test that the input files conform with their schemas or handle errors that arise if they don't conform or if they don't go with each other (e.g. if there is no base price for a product type in the cart). We'd all want those tests in a production application, but in this exercise they tend to take time without adding interest.

### Implementation requirements
* Include thorough automated tests for your code. All of the following applies as much to your tests as to your code.
* Set up your submission and include any necessary instructions to make it as obvious and convenient as possible for the engineer(s) reviewing your submission to install your program, run it, and run the tests.
* Write clean, clear, well-factored code which you would be proud to commit at work or to an open-source project.
* Your code should clearly reflect and explain the problem domain.
* Write code which you can easily extend. We'll ask you to do so later in your interview.
* If you use version control while developing your submission, please include the version history with your submission. This allows us to see the process that you followed while you worked. For example, if you commit to git as you worked, please include the .git directory in the zip file that you send us.

We're not timing you, and you can take as much time as you like, but this test is intended to take you no more than a few hours.

## work log
19 July 2018 Dev Env Setup 2 hours