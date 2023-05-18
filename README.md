
# Ecommerce Web Shop

A mock Ecommerce web shop meant to simulate the shopping experience from a web shop such as Amazon. Features include a visually pleasing user interface, a shopping cart, a checkout page allowing users to enter in personal and payment information, and the sending of a confirmation email after a purchase.

Item List
![Item list](https://github.com/MatthewAu3/ecommerce-web-shop/blob/main/item-list.PNG?raw=true)

Shopping Cart
![Item list](https://github.com/MatthewAu3/ecommerce-web-shop/blob/main/shopping-cart.PNG?raw=true)

Enter Personal Info
![Item list](https://github.com/MatthewAu3/ecommerce-web-shop/blob/main/checkout-page.PNG?raw=true)

Enter Payment Info
![Item list](https://github.com/MatthewAu3/ecommerce-web-shop/blob/main/checkout-page2.PNG?raw=true)

## How it was made

**Languages Used:** HTML, CSS, Javascript

**Tech Stack:** React.js, Commerce.js, Stripe

**Motivation:** The goal was to make a project to showcase my skills using React.js. 

**Challenges Faced:** An initial hurdle I had to overcome was how to implement that growing snake. I had to come up with a way to have to expand from the tail. I also had to take into account that when the snake changes direction, not all the parts of the snake move in that same direction. The solution that I came up with and implemented is to
use a resizable array that adds a new body segment each time the snake eats an apple. Another issue was to deal with the snake changing directions. My initial approach was to just have all the body segments move in the same direction as the user input. However, I realized that this was not sufficient because of the complex nature of how the snake moves around the grid.
So the solution I came up with was to just move the head of the snake in the direction of the user input, but have the rest of the body segments move to where the previous part of the snake was.

**Lessons Learned** Through working on this project, I set up a stronger foundation for my HTML, CSS, and Javascript skills. The project placed a greater emphasis on my critical thinking and logic skills regarding how to implement the different aspects of the games such as the user input, snake movement, and snake growth. Overall, I believe that this project, while not the most complex from a technological standpoint, proved to be decently complex from a logical standpoint.