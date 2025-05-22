# 🌿 Smart Greenhouse Management System

This project automates a greenhouse using Arduino. It monitors temperature, humidity, soil moisture, and light intensity, and controls irrigation via a relay module.

## 🛠 Components Used

- Arduino UNO
- DHT22 Temperature & Humidity Sensor
- Soil Moisture Sensor
- Light Sensor / Potentiometer
- Relay Module
- Water Pump (or LED for testing)

## ⚙️ How It Works

- Reads data from DHT22, soil moisture, and light sensors.
- If soil moisture < 40%, the irrigation system turns ON.
- Data is printed to the Serial Monitor every 2 seconds.

## 🔌 Wiring

| Sensor/Module       | Arduino Pin |
|---------------------|-------------|
| DHT22 (Data)        | D2          |
| Soil Moisture       | A0          |
| Light Sensor        | A4          |
| Relay Module (IN)   | D3          |

## 🧪 Simulation

This code works with [Wokwi Simulator](https://wokwi.com), using a potentiometer for the light sensor.

## 📄 License

MIT License
