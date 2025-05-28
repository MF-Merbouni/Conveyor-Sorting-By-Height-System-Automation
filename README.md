# Conveyor Sorting System (Factory I/O + CODESYS)
An automated conveyor sorting system that sorts items by height using Factory I/O and CODESYS.

## Features
- Sorts items using height sensors and actuators
- Built with Structured Text (ST)
- Fully simulated using Factory I/O

---

## Tools Used
- Factory I/O
- CODESYS
- Structured Text (ST)

---

## How it Works
Here’s a clearer and more professional version of your **"How it Works"** section for your GitHub `README.md`:

---

## How It Works

* A **feeder conveyor** introduces pallets carrying boxes onto the main conveyor line.
* Each box passes through a **height detection sensor** positioned above the conveyor.
* Based on the measured height:

  * **Tall boxes** are diverted to the **left side**.
  * **Short boxes** are diverted to the **right side**.
* At the end of each sorting line, a **sensor detects the presence of a pallet** and **increments a counter** to track the number of sorted items.

---

 ## How to Run
1. Open the Factory I/O scene
2. Open the CODESYS project
3. Establish Modbus/TCP communication
4. Run the system and observe the sorting process

---


 
