Trola Vending Machine Kata
====================

In this exercise you will build the brains of a vending machine.  It will accept money, make change, maintain
inventory, and dispense products.  All the things that you might expect a vending machine to accomplish.

The point of this kata to to provide a larger than trivial exercise that can be used to evaluate your ability to create a more complete solution to a set of problems. You should spend no more than a few hours doing this exercise. 

The solution below assumes a UI based solution. The technologies you use can be anything as long as the code is viewable from the repository link that you submit.

Setup
========

1. Fork this repository. 
2. Commit all solution code to your forked repository.
3. Make sure your final solution is merged into the master branch of your forked repository.

Submitting
========

Please email the link to your repository to [jbarton@trolaindustries.com](mailto:jbarton@trolaindustries.com)

Features
========

We have split the work of creating a vending machine into three user stories.

### Insert Coin

_As a vendor_  
_I want a vending machine that accepts coins_  
_So that I can collect money from the customer_ 

- The vending machine will accept valid coins (nickels, dimes, and quarters). Coins represented by three buttons.
- When a valid coin is inserted (button pressed) the amount of the coin will be added to the current balance and the machine's display will be updated.
- When there are no coins inserted, the machine displays INSERT COIN.

### Select Item

_As a vendor_  
_I want customers to select items_  
_So that I can give them an incentive to put money in the machine_

- The machine shows a list of items with their price and remaining inventory.
- The machine shows the following items: Coke, Sprite, Ice Tea.
- Each item is worth 50 cents.
- You can only select a single item at a time.

### Dispense Item

_As a customer_  
_I want to be told whether my item has been dispensed_  
_So that I can know whether my transaction has completed_  

- A button labeled 'Dispense' when pressed dispenses the selected item if there is enough current balance and the selected item has remaining stock.
- The machine responds with "Insufficient Balance" or "No Inventory Remaining," respectively if there is an error, and cancels dispensing of item.
- The machine responds with success message when item is successfully dispensed.
- The machine deducts item cost after successfully dispensing item.

