# Abstraction-trialPython Appliance Management System (OOP Abstract Class Demo)
A Python demonstration illustrating  (OOP) concepts, specifically Abstraction using Python's Built-in abc (Abstract Base Class) module.

## Project Overview
This project models a set of household appliances (WashingMachine, Refrigerator, and Microwave) derived from a common abstract base class (Appliance).

It enforces a standard interface requiring every appliance subclass to implement both turn_on() and turn_off() methods.

## Key Concepts Covered
1. Abstraction (ABC, @abstractmethod): Defines a template/contract in the Appliance class that child classes must implement.

2. Inheritance: WashingMachine, Refrigerator, and Microwave inherit structure from Appliance.

3. Polymorphism: Each subclass provides its own specific behavior for turn_on() and turn_off().

## Requirements
Python 3.6+ (No external third-party libraries required).

## Code Structure
Python
Appliance (Abstract Base Class)
- WashingMachine
- Refrigerator
   - Microwave
##  How to Run
Clone or download the script file (e.g., appliances.py).

Open your terminal or command prompt.

Run the script using Python:
