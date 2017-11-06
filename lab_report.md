# Lab Report 02
## Assignment 02 - Use Cases and Class Diagrams
_Authors: Dennis Loska, Tony Dorfmeister, Ai Dong 24.10.2017_

## Use Cases & Scenarios

### Identify the use cases in this description and draw a use case diagram.

- basic idea is to record the situation in which something happens, explain what should happen, and describe any exceptional circumstances which might arise

Users of the site need to be able to search the treats offers - mostly pumpkins, but also all other kinds of Halloween treats. For Pumpkins, they need to **find information** on the type of Pumpkin, it’s size and weight, and of course it’s price and whether it has been carved already.

Users should be able to **buy a pumpkin online** and have it **delivered** to an address of their choice. They can **pay via various payment methods**, at least money transfer, credit card and a popular online payment service called MoneyPal.
...
Users should also be able to rate the treats and post reviews and fotos. Administrators can edit and delete those reviews as needed.

### Possible Use Cases

- Order Substystem
- Information Substystem
- Payment Substystem
- Rating Substystem
- Administration Substystem (Use Case für Administratoren)
- Backend Subsystem


### Then, pick the most important (or interesting) use case. Write down a detailed scenario for that use case (see below).

#### 1. Use Case: Order Substystem

Um im Treats Worldwide Online Shop eine Bestellung zu tätigen, müssen einige Prozesse durchlaufen werden. Der Beschreibung der Applikation in der Aufgabenstellung entsprechend gibt der HTW Shop dem Kunden Informationen über die Kürbisse und Süßigkeiten. Der Kunde kann aus einer Auswahl von Produkten bzw. Kürbissen wählen und diese bestellen. Der HTW Shop kann die bestellten Kürbisse an den Kunden z.B. über ein Liefer bzw- Delivery System zustellen.

Hier ist ein Use Case Diagram für das Bestellsystem des Shops:

![UseCaseSubsystemOrder](/Users/tweak/CloudStation/IMI/03_Semester/Informatik-03/labs/Lab02_UseCaseClassDiagrams/use_cases/UseCaseSubsystemOrder.jpg)

#### Use Case: Checkout

![useCase_checkout](/Users/tweak/CloudStation/IMI/03_Semester/Informatik-03/labs/Lab02_UseCaseClassDiagrams/use_cases/useCase_checkout.jpg)



#### Use Case: Review

![useCase_review](/Users/tweak/CloudStation/IMI/03_Semester/Informatik-03/labs/Lab02_UseCaseClassDiagrams/use_cases/useCase_review.JPG)



## Class Diagram

### Then, draw a Class Diagram for your Application. It should contain associations (aggregations and compositions, association classes as needed), generalizations, as well as the most important fields and method names of the classes.

![class_diagram](/Users/tweak/CloudStation/IMI/03_Semester/Informatik-03/labs/Lab02_UseCaseClassDiagrams/class_diagram.PNG)