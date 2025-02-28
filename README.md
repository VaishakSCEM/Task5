# Task5
# 2-bit Comparator using VSDSquadron Mini Board

## Overview
This project implements a **2-bit comparator** using the **VSDSquadron Mini Board**. A **2-bit comparator** is a digital circuit that compares two 2-bit binary numbers and determines whether one number is greater than, less than, or equal to the other.

## **Project Objectives**
- Design a **2-bit comparator** using C programming.
- Implement the design on the **VSDSquadron Mini Board**.
- Use **LEDs** to display the comparison results.
- Gain hands-on experience in **digital circuit design**, **C programming**, and **hardware implementation**.

## **Components Required**
| Component                 | Quantity |
|---------------------------|----------|
| **VSDSquadron Mini Board** | 1        |
| **Breadboard**            | 1        |
| **Jumper Wires**          | As needed |
| **LEDs** (Yellow, Red, Green) | 3        |
| **Resistors** (220Ω)      | 3        |

## **Pin Configuration**
| LED  | VSDSquadron Board |
|------|-------------------|
| **LED1 (Yellow - A > B)** | **PD4 (Pin 4)** |
| **LED2 (Red - A < B)**    | **PD5 (Pin 5)** |
| **LED3 (Green - A = B)**  | **PD6 (Pin 6)** |

## **Truth Table**
| A1 | A0 | B1 | B0 | A > B | A = B | A < B |
|----|----|----|----|------|------|------|
| 0  | 0  | 0  | 0  | 0    | 1    | 0    |
| 0  | 0  | 0  | 1  | 0    | 0    | 1    |
| 0  | 0  | 1  | 0  | 0    | 0    | 1    |
| 0  |
