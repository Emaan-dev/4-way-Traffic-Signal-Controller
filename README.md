# 4-Way Traffic Signal Controller Using Digital Logic

## 📌 Project Overview

This project presents the **design and simulation of a 4-way traffic signal controller** using **digital logic and timing circuits**. It is developed as part of the *Digital Logic Design* course at **Ghulam Khan Institute of Engineering Science and Technology (GKIST), Pakistan**.

The system controls traffic flow at a four-way intersection by sequentially activating **Green, Yellow, and Red** signals for each direction while ensuring that **no two directions receive a green signal simultaneously**. The project emphasizes reliability, safety, and scalability using fundamental digital electronics components.

---

## 🎯 Objectives

* Design a safe and efficient 4-way traffic signal system
* Implement traffic control using **digital logic components** (counters, timers, logic gates)
* Simulate and verify system behavior before physical implementation
* Strengthen understanding of **sequential circuits and timing control**
* Explore possibilities for future smart traffic system enhancements

---

## ⚙️ System Description

The traffic signal operates in a cyclic sequence where each direction receives:

1. **Green Light** – Vehicles are allowed to pass
2. **Yellow Light** – Transition warning
3. **Red Light** – Vehicles must stop

The sequence is controlled by a clock-driven logic system that guarantees fairness and prevents conflicts.

### Key Features

* Fully digital logic-based design
* Accurate timing using a clock pulse generator
* Conflict-free traffic flow (only one green light at a time)
* Easily scalable and modifiable

---

## 🧩 Block Diagram Components

* **Pulse Generator (555 Timer)** – Generates clock pulses for timing control
* **Sequential Logic Unit** – Controls state transitions
* **Counters** – Define duration of each light phase
* **Logic Gates** – Ensure safe and valid transitions
* **LED Indicators** – Represent traffic lights for each direction

---

## 🔧 Hardware Components Used

* 555 Timer (Astable Mode)
* 4-bit Decade Counters
* LEDs (Red, Yellow, Green)
* Resistors (Current limiting)
* Transistors (Current amplification)
* Breadboard & Jumper Wires
* DC Power Supply

---

## 💻 Simulation & Testing

The circuit is simulated using **Proteus Design Suite** to validate functionality before hardware assembly.

### Simulation Steps

1. Design the circuit schematic
2. Configure timer intervals
3. Verify correct light sequencing
4. Test state transitions
5. Fine-tune timing values

### Testing Criteria

* Correct sequence of lights
* Accurate timing intervals
* No overlapping green signals
* Continuous cyclic operation

---

## 🚧 Challenges & Limitations

* Timing inaccuracies due to component tolerances
* Breadboard instability during long tests
* Increased complexity for large-scale intersections

---

## 🚀 Future Enhancements

* IR or ultrasonic **vehicle detection sensors**
* **IoT-based communication** between intersections
* Microcontroller-based redesign (e.g., Arduino, PIC)
* Battery backup for power failures
* AI-based adaptive traffic control

---

## 📚 References

* M. Morris Mano, *Digital Design*, Pearson
* T. L. Floyd, *Digital Fundamentals*, Pearson
* P. Horowitz & W. Hill, *The Art of Electronics*
* Proteus Design Suite – Labcenter Electronics
* IEEE & Journal publications on smart traffic systems

---

## 👩‍💻 Authors

* **Emaan Fatima** (2024254)
* **Emaan Tahir Swati** (2024156)

---

## 🏫 Academic Information

* **Course:** Digital Logic Design
* **Instructor:** Dr. Adnan Shah
* **Institute:** Ghulam Khan Institute of Engineering Science and Technology (GKIST)

---

⭐ *If you find this project useful, consider starring the repository!*
