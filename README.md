# Relay Protection System using MATLAB Simulink

## 📌 Project Overview

This project demonstrates the development of **protective relay logics** using **MATLAB Simulink** for power system protection. Two types of relays are modeled:

1. **Under-Voltage Relay** – Detects abnormal drop in system voltage and generates a **trip signal** to the circuit breaker.
2. **Over-Current Relay** – Detects excessive current in the system and generates a **trip signal** to the circuit breaker.

The project showcases the **design, simulation, and validation** of relay logic in Simulink, highlighting their importance in ensuring the **safety and reliability** of power systems.

---

## 🎯 Objectives

* To develop **under-voltage relay logic** in MATLAB Simulink.
* To generate the **trip signal** for the circuit breaker under under-voltage conditions.
* To develop **over-current relay logic** in MATLAB Simulink.
* To generate the **trip signal** for the circuit breaker under over-current conditions.

---

## ⚙️ System Specifications

* **Software Used:** MATLAB Simulink
* **Components:**

  * Voltage measurement block
  * Current measurement block
  * Comparator logic (for relay settings)
  * Circuit breaker block
  * Relay logic subsystem

---

## 📖 Theory

### 🔹 Under-Voltage Relay

An under-voltage relay monitors the supply voltage of the system. When the voltage drops below a **preset threshold value**, the relay issues a trip command to the circuit breaker. This prevents unstable operation and protects sensitive equipment.

### 🔹 Over-Current Relay

An over-current relay protects the system by continuously monitoring the line current. When the current exceeds the **preset current limit**, it triggers the circuit breaker to disconnect the faulty section, thereby preventing equipment damage.

---

## 🛠️ Implementation Steps

1. **Model setup in Simulink** with voltage and current sources.
2. **Relay logic design** using comparator blocks for threshold detection.
3. **Trip signal generation** connected to the circuit breaker.
4. **Simulation under fault conditions** to verify relay operation.
5. **Validation of relay responses** under normal and abnormal conditions.


## Diagram of the logic
<img width="725" height="469" alt="image" src="https://github.com/user-attachments/assets/d44b2d27-63c9-4fbe-8b6e-13709cd640fc" />

---

## 📊 Results

* The **under-voltage relay** successfully detects voltage drops and sends a trip signal to the circuit breaker.
* The **over-current relay** correctly identifies over-current conditions and isolates the system through the circuit breaker.
* Simulation results confirm the effectiveness of the designed protection system.



## MATLAB structure of the project 
<img width="721" height="347" alt="image" src="https://github.com/user-attachments/assets/39fb04d9-99fc-4c6a-b02b-cffb391f8fa4" />

---

## 🚀 Applications

* Power system protection in transmission and distribution networks.
* Industrial protection systems for sensitive electrical equipment.
* Educational demonstration for relay operation using MATLAB Simulink.

---


## 📌 Future Work

* Implementation of **time-delay logic** for relay operation.
* Integration of **directional relays** for selective protection.
* Development of **adaptive relay settings** using AI/ML techniques.






