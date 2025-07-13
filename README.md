# 📅 Day 10 – VLSI + Embedded Systems

---

## 🔷 VLSI Topic: Ripple Carry Adder (RCA)

### ✅ What I Learned

- A **Ripple Carry Adder** (RCA) connects multiple Full Adders in series.
- Each adder takes a **Carry-In** from the previous stage (this causes a ripple delay).
- It's simple but slow due to **carry propagation**.

### 🧠 Example

Adding A = 1101 and B = 1011:

| Bit Position | A | B | Cin | Sum | Cout |
|--------------|---|---|-----|-----|------|
| FA0 (LSB)    | 1 | 1 | 0   |  0  |  1   |
| FA1          | 0 | 1 | 1   |  0  |  1   |
| FA2          | 1 | 0 | 1   |  0  |  1   |
| FA3 (MSB)    | 1 | 1 | 1   |  1  |  1   |

**Final Output**: Sum = `1000`, Carry = `1`

---

## 🔶 Embedded Systems: Introduction

### ✅ What I Learned

- An **embedded system** is a dedicated system with hardware + software.
- It uses a **microcontroller** to perform a single task.
- Found in many everyday devices like washing machines, smartwatches, and microwave ovens.

### 🔍 Components Table

| Component       | Role                            |
|----------------|----------------------------------|
| Microcontroller| Main controller with CPU, RAM    |
| Sensor         | Detects input from environment   |
| Actuator       | Performs output action           |
| Power Supply   | Powers the system                |

---

## 📝 Real-Life Device Examples

- 🌀 Washing Machine (Embedded)
- 🧮 RCA used in basic arithmetic units in digital circuits (VLSI)

---

## 🔚 Summary

Today I learned:
- How ripple carry adders work and their role in digital logic.
- Basics of embedded systems and real-time applications.

---

