# Analog Function Generator using Op-Amps (741)

## 📌 Overview

This project implements an analog function generator capable of producing **sine, square, and triangular waveforms** using operational amplifiers. The design includes a dual power supply and multiple signal processing stages.

---

## 🔹 Block Diagram

![Block Diagram](images/block_diagram.png)

---

## 🔹 Working Principle

### 1. Power Supply Stage

* 230V AC is stepped down using a transformer (12-0-12)
* Full-wave rectifier converts AC to DC
* 1000µF capacitor filters ripple
* Voltage regulators (LM7812, LM7912) provide stable ±12V

---

### 2. Wien Bridge Oscillator (Sine Wave)

* Generates sine wave using RC network
* Frequency controlled using potentiometer

---

### 3. Comparator (Square Wave)

* Converts sine wave into square wave

---

### 4. Integrator (Triangle Wave)

* Converts square wave into triangular wave

---

### 5. Output Selection

* Switch used to select waveform output

---

## 🔹 Circuit Diagram

![Circuit](images/circuit_diagram.png)

---

## 🔹 Hardware Implementation

![Hardware](images/hardware_setup.jpg)

---

## 🔹 Simulation Results

### Circuit (Tinkercad)

![Circuit](simulation/simulation_screenshot.png)

### Output Waveforms

**Sine Wave**
![Sine](simulation/sine_wave.png)

**Square Wave**
![Square](simulation/square_wave.png)

**Triangle Wave**
![Triangle](simulation/triangle_wave.png)

---

## 🔹 Simulation Link

[Tinkercad Simulation](https://www.tinkercad.com/things/your-link)

---

## 🔹 Features

* Generates sine, square, and triangle waves
* Adjustable frequency
* Dual power supply (±12V)
* Real-time waveform visualization

---

## 🔹 Tools Used

* LTspice (Power supply simulation)
* Tinkercad (Circuit simulation)

---

## 🔹 Author

Naraender
