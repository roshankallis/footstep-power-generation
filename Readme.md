# 👣 Footstep Power Generation System ⚡

A renewable energy project that generates electrical power from human footsteps. The system uses pressure applied by a person walking on a specially designed platform to generate electrical energy.

## 📷 Project Prototype

![Footstep Power Generation System](images/project.jpg)

## 📌 Overview

The **Footstep Power Generation System** is designed to convert mechanical energy produced by human footsteps into electrical energy.

When a person steps on the platform, the applied mechanical pressure activates the energy-generating mechanism. The generated electrical energy is then collected, processed, and used to power small electrical loads such as LEDs.

This project demonstrates the concept of **energy harvesting** from everyday human activity.

## ⚙️ Working Principle

The basic working process is:

👣 Human Footstep │ ▼ ┌────────────────┐ │ Pressure/Force │ │ Mechanism │ └───────┬────────┘ │ ▼ ┌────────────────┐ │ Energy │ │ Generation │ └───────┬────────┘ │ ▼ ┌────────────────┐ │ Rectifier & │ │ Power Circuit │ └───────┬────────┘ │ ▼ ┌────────────────┐ │ Energy Storage │ │ / Capacitor │ └───────┬────────┘ │ ▼ 💡 LED Load


## 🔩 Components Used

- Piezoelectric elements / footstep energy generators
- ESP32 development board
- LEDs
- Resistors
- Diodes / rectifier circuit
- Capacitors
- Breadboard
- Connecting wires
- Footstep platform
- Power-conditioning circuit

## 🔋 How It Works

1. A person steps on the footstep platform.
2. Mechanical pressure is applied to the energy-generating elements.
3. The pressure is converted into electrical energy.
4. The generated electrical output is passed through a rectifier/power-conditioning circuit.
5. The electrical energy can be stored in a capacitor or battery.
6. The stored/generated energy is used to power LEDs or other low-power devices.
7. The ESP32 can be used to monitor or display parameters such as generated voltage and footstep count.

## 💡 Applications

This technology can be used in places with heavy pedestrian traffic, such as:

- 🚉 Railway stations
- 🏫 Schools and colleges
- 🏢 Shopping malls
- 🏟️ Stadiums
- 🚶 Pedestrian walkways
- 🚇 Metro stations
- 🏭 Industrial areas
- 🏠 Smart-home demonstrations

## 🌱 Advantages

- Uses renewable human-generated energy
- Environmentally friendly
- Demonstrates energy harvesting
- Can operate from normal human activity
- Useful for low-power applications
- Can be integrated with IoT systems

## 🚀 Future Improvements

- Increase the energy generated per footstep
- Add rechargeable battery storage
- Add an LCD/OLED display
- Monitor voltage and current using ESP32
- Add Wi-Fi-based monitoring
- Develop a mobile application
- Improve mechanical efficiency
- Connect multiple footstep modules
- Develop a custom PCB
- Use the system for smart-city applications

## 📊 Expected Output

The generated power depends on factors such as:

- Force applied by the person
- Number of footsteps
- Type and number of energy-generating elements
- Mechanical design of the platform
- Electrical circuit efficiency

The system is primarily intended for **energy harvesting and low-power applications**.

## 🛠️ Technologies Used

- **ESP32**
- **Embedded C / Arduino**
- **Energy Harvesting**
- **Piezoelectric/Pressure-Based Generation**
- **IoT (optional)**

## 📁 Project Structure

Footstep-Power-Generation/ │ ├── README.md │ ├── images/ │ └── project.jpg │ ├── src/ │ └── main.ino │ └── LICENSE


## 🔌 Circuit

The footstep generators are connected to the rectification and power-conditioning circuit. The conditioned output can then be connected to the load or energy-storage unit.

> ⚠️ The exact circuit and ESP32 GPIO connections depend on the hardware implementation.

## ⚠️ Safety

Do not connect the generated output directly to sensitive electronic components without appropriate voltage regulation and protection.

Make sure the generated voltage remains within the safe operating range of the ESP32 and other connected components.
