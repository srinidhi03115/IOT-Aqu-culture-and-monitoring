# IOT-Aqu-culture-and-monitoring
✅ README.md (Step-by-Step Procedure)
markdown
Copy
Edit
💧AQUACULTURE AND MONITORING   (Arduino Simulation)

This project simulates a basic **aquaculture and monitoring** using an Arduino and potentiometers to represent environmental sensors like:

- pH Level
- Turbidity
- Dissolved Oxygen (DO)
- Ammonia (NH3)
- Water Level

It prints data to the Serial Monitor and provides real-time evaluation of water conditions.

---

📦 Components Required

| Component          | Quantity |
|--------------------|----------|
| Arduino Uno        | 1        |
| Potentiometers     | 5        |
| Breadboard         | 1        |
| Jumper Wires       | Several  |
| USB Cable (for Arduino) | 1    |

---

🧾 Pin Configuration

| Sensor             | Arduino Pin |
|--------------------|-------------|
| pH Sensor          | A0          |
| Turbidity Sensor   | A1          |
| DO Sensor          | A2          |
| Water Level Sensor | A4          |
| Ammonia Sensor     | A5          |

All sensors are simulated using potentiometers.

---

 🛠️ Step-by-Step Setup Instructions

 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/WaterQualityMonitoring.git
cd WaterQualityMonitoring
Replace yourusername with your actual GitHub username.

2️⃣ Open the Code in Arduino IDE
Open Arduino IDE

Go to File > Open

Browse to aquacultureandmonitoring.ino file from the cloned folder

3️⃣ Connect Your Arduino
Plug the Arduino board into your PC via USB cable

4️⃣ Select the Board and Port
Go to:

Tools > Board > Arduino Uno

Tools > Port > (Select your COM port)

5️⃣ Upload the Code
Click on the ✅ Verify button

Then click the ➡️ Upload button

6️⃣ Open Serial Monitor
Go to Tools > Serial Monitor

Set baud rate to 9600

7️⃣ Simulate Readings
Rotate each potentiometer to simulate different values for:

pH level (A0)

Turbidity (A1)

DO (A2)

Water level (A4)

Ammonia (A5)

📊 Output Example
yaml
Copy
Edit
pH Voltage: 2.50 | Turbidity: 420 | DO: 55.00 % | Ammonia: 22.00 % | Distance: 25
Water is clean
Water level: Normal
Dissolved oxygen is within safe range
Ammonia concentration is within safe range
📋 Functional Highlights
Checks if water is clean based on turbidity and pH

Monitors safe levels of:

Dissolved Oxygen (DO)

Ammonia (NH3)

Displays water level status:

Full

Normal

Too Low

