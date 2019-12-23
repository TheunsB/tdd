# TDD example

For this example, the requirement is to build the functionality of a vending machine using a springboot commandline runner application.

Requirement:

The vending machine should accept the following coins; 
50 cent
1 euro
2 euro

The vending machine should offer the following choices of drinks, each with its own price; 
Cola (0.50)
Fanta (1.50)
Sprite (1)

The vending machine should start up with a given amount of stock (i.e. 10 cola, 10 fanta, 10 sprite) and should keep track of the stock.
The vending machine should provide a menu of choices, accept the choice as input. It should then require money to be input in the form of coins. It should then vend the drink if sufficient money was provided and also refund the user with change if too much was paid.

To run the application:

mvn clean install

mvn spring-boot:run
