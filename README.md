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
## What We Learned

* How to design and simulate a real-time **automated sorting system** using Factory I/O
* Practical experience with **PLC programming** using Structured Text (ST) in **CODESYS**
* Implementing **sensor-based decision logic** to control actuators (e.g., diverters, conveyors)
* Establishing **communication between CODESYS and Factory I/O** using Modbus TCP
* Tracking system performance with **counters and sensors** for item verification
* Organizing a complete automation project with **GitHub**

---

## Author

**Mohamed Fathi Merbouni**  
_Aspiring Automation Engineer_

---

## Contributing
Feedback and improvements are welcome. Fork the repo and submit a pull request!
 
