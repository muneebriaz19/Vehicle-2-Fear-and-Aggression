# Vehicle 2 – Fear and Aggression (Braitenberg Simulation)

This project is a simulation of **Vehicle 2** from Valentino Braitenberg’s *Vehicles: Experiments in Synthetic Psychology*. Built using **Unreal Engine**, it visualizes emergent behaviors—**fear** and **aggression**—arising from simple sensor-motor wiring in artificial agents.

---

## 🚗 Concept

Vehicle 2 evolves from the simpler **Vehicle 1** by introducing:
- **Two sensors** (left and right)
- **Two motors** (left and right)

The behavior of the vehicle varies based on how the sensors are connected to the motors:

- **Vehicle 2a (Fear)**: Each sensor is connected to the **motor on the same side**.
  - The vehicle turns away from the stimulus (e.g., light or heat) and exhibits avoidance behavior.
  - It speeds up in high stimulus zones, fleeing faster.
  - 🧠 *Emergent behavior: Cowardice*

- **Vehicle 2b (Aggression)**: Each sensor is connected to the **motor on the opposite side**.
  - The vehicle steers toward the stimulus and collides with it head-on.
  - It becomes more excited as it nears the source.
  - 🧠 *Emergent behavior: Aggression*

> These behaviors appear purposeful but arise from simple reactive mechanisms—highlighting how complex psychology can emerge from basic structures.

---

## 🧠 Features

- Real-time simulation of both **Vehicle 2a** and **Vehicle 2b**
- Adjustable environment with **light source(s)** as stimuli
- Visual distinction between sensor-motor wiring types
- Emergent behavior demonstration (avoidance vs. attack)

---

## 🛠️ Requirements

- **Unreal Engine 5.x**
- Windows 10/11 or macOS
- Visual Studio (for C++ modules, if applicable)

---

## 🧪 How to Run

1. Clone or download this repository.
2. Open the project using **Unreal Engine** via `Vehicle_final_2.uproject`.
3. Hit **Play** to simulate the vehicles.
4. Observe how different wiring leads to fear (Vehicle 2a) or aggression (Vehicle 2b) toward the stimulus.

---

## 🔬 Behavior Overview

| Configuration | Wiring Type | Emergent Behavior | Movement |
|---------------|-------------|-------------------|----------|
| Vehicle 2a    | Sensor ➜ Same-side Motor | Fear / Cowardice | Avoids source |
| Vehicle 2b    | Sensor ➜ Opposite-side Motor | Aggression | Seeks out and hits source |

---

## 📚 Inspired By

Valentino Braitenberg – *Vehicles: Experiments in Synthetic Psychology*  
Chapter: **Fear and Aggression**

> “Vehicle 2a is a coward, you would say. Not so Vehicle 2b... It is aggressive, obviously.”

---

## 🤝 Contributions

Feel free to fork and enhance this project. Ideas include:
- Simulating Vehicles 3–4 (love/hate, logic)
- Multiple stimulus sources
- Neural net controlled behaviors

---

> Simplicity breeds complexity. This project demonstrates how minimalist machines can exhibit lifelike psychological traits through nothing but structure and interaction.
