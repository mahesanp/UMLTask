# UMLTask
#Online Shopping system




Sequential Diagram :

Here it shows the interactive behaviour of a Online shopping System, as it shows
the interaction between objects in a sequential order

A sequential diagram in UML consists
*Actors
*Lifelines
*Messages

Actor : Here, Customer is a actor who interacts with the system and its objects for
        placing orders and making payment

Lifelines : Lifeline depicts participant in a sequence diagram for internal interation,
            Here shopping website , Banking server acts as a lifeline.

Messages : It is represented using arrows that has messages interacting with lifelines
           Here, Customer interacts with a lifeline Shoppingsite for searching and placing orders , 
           and this message is represented with arrows.

The customer chooses the payment method after adding the product to cart and the bank server validates the bank
credentials and if the credentials were correct then the bank server approves the payment and the order is confirmed.

Class Diagram:
 
The Online Shopping System has been depicted by the class diagram. For the case of Online Shopping System, the predominant classes to be considered are as follows:
-Customer Login
-Product
-Order
-Cart
-Payment 
-Categories
-Status
Each class has attributes and method. For instance let's consider the class Customer Login which has attributes like
username, password, email, phone number, age group selection and has the previlege to place the order and contains methods like 
updateProfile() to update the foresaid details and plaeorder() function.

The # symbol denotes as if the attribute or function is protected. The '-' and '+' denotes private and public respectively. The relationships among the classes can be association, aggregation, composition and inhertance. In the case of relationship, there comes the concept of multiplicity such as 
1 to 1 or 1 to many.
Each Customer Login has one category page, one cart and can perform multiple orders. Each order contains multiple products, must have a payment and can have a single delivery status. These classes and its relationships are depicted in the class diagram.


Use Case Diagram:

The Online Shopping System has been depicted by the use case diagram. In this case the actors are Customer, Banker, Server, Database and the usecases are
-usecase "Browse Products"
-usecase "Add to cart"
-usecase "Place Order"
-usecase "Make Payment"
-usecase "Responding to Client Requests"
-usecase "Fetching data from Database"

Each actor is perfoming atleast one use case. The "make payment" use case is used by Customer, Banker and Server.
The Card denotes the package of the Use Case Diagram. The packages present are "Actors" and "Use Cases".
