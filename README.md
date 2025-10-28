🧠 Parking Lot Management System using Stack (LIFO) — Explanation

Concept Used: Stack (Last In, First Out) — the last car parked is the first to leave.



---

⚙️ Main Components

1. struct Car – stores each car’s number.


2. struct Stack – represents the parking lot as a stack with:

cars[MAX] → array to store cars

top → index of the top car





---

🔹 Functions

initialize() → sets top = -1 (empty stack).

isFull() / isEmpty() → check parking status.

parkCar() → adds a car (push).

removeCar() → removes the top car (pop).

displayParking() → shows all currently parked cars.



---

🚗 Flow

1. User selects an option from the menu.


2. Cars are parked or removed using stack operations.


3. Program continues until user exits.


