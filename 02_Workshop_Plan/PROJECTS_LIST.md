# 📋 Workshop Projects List - Complete Details

## 🎓 3-Day IoT & Robotics Workshop

---

# 🏫 CLASS 9th - 5 Projects (Beginner Level)

---

## Group 1: WiFi Controlled Car 🚗

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain (WiFi enabled) |
| MX1508 Motor Driver | 1 | Motor control |
| DC Gear Motors | 2 | Wheels movement |
| Robot Car Chassis | 1 | Body frame |
| Jumper Wires | Set | Connections |
| Battery Pack | 1 | Power supply |

### Working:
```
📱 Phone → WiFi → ESP8266 → Motor Driver → Motors
```
- ESP8266 creates WiFi Access Point
- Phone connects to WiFi
- Web interface controls car direction
- Forward, Backward, Left, Right, Stop

### Key Learning:
- WiFi AP mode
- Motor control basics
- Web server on ESP8266

---

## Group 2: Smart Blind Stick 🦯

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| Ultrasonic HC-SR04 | 1 | Distance measure |
| Active Buzzer | 1 | Sound alert |
| Jumper Wires | Set | Connections |
| Battery Pack | 1 | Portable power |
| Stick/Cane | 1 | Mounting |

### Working:
```
Ultrasonic → ESP8266 → Buzzer
(Distance)   (Process)  (Alert)
```
- Ultrasonic measures distance to obstacles
- Closer obstacle = Faster beeping
- Far obstacle = Slow/No beeping

### Key Learning:
- Ultrasonic sensor working
- Distance calculation
- Conditional alerts

---

## Group 3: Rain Detection System 🌧️

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| Rain/Water Sensor | 1 | Detect water drops |
| SG90 Servo Motor | 1 | Window/shade control |
| Jumper Wires | Set | Connections |
| Breadboard | 1 | Circuit base |

### Working:
```
Rain Sensor → ESP8266 → Servo Motor
(Water detect) (Process) (Close window)
```
- Rain sensor detects water drops
- Sends signal to ESP8266
- Servo rotates to close window/shade
- Automatic rain protection!

### Key Learning:
- Analog sensor reading
- Servo motor control
- Automation concept

---

## Group 4: Smart Street Light 💡

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| LDR (Light Sensor) | 1 | Light detection |
| Relay Module (5V) | 1 | High power switch |
| LED/Bulb | 1 | Street light |
| 10K Resistor | 1 | LDR voltage divider |
| Jumper Wires | Set | Connections |

### Working:
```
LDR → ESP8266 → Relay → Light
(Dark/Light) (Process) (ON/OFF)
```
- LDR measures ambient light
- Dark = Low resistance = Light ON
- Bright = High resistance = Light OFF
- Auto ON at night, OFF at day

### Key Learning:
- Analog sensor (A0 pin)
- Relay module usage
- Day/Night automation

---

## Group 5: Password Door Lock 🔐

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| 4x3 Matrix Keypad | 1 | Password input |
| SG90 Servo Motor | 1 | Lock mechanism |
| Active Buzzer | 1 | Feedback sound |
| Jumper Wires | Set | Connections |
| Breadboard | 1 | Circuit base |

### Working:
```
Keypad → ESP8266 → Servo
(Password) (Verify) (Lock/Unlock)
```
- User enters password on keypad
- ESP8266 checks if correct
- Correct = Servo opens lock
- Wrong = Buzzer beeps (error)

### Key Learning:
- Matrix keypad scanning
- Password logic
- Servo positioning

---

# 🏫 CLASS 10th - 5 Projects (Intermediate Level)

---

## Group 1: Obstacle Avoidance Car 🚗

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| Ultrasonic HC-SR04 | 1 | Distance measure |
| SG90 Servo Motor | 1 | Sensor rotation |
| MX1508 Motor Driver | 1 | Motor control |
| DC Gear Motors | 2 | Wheels |
| Robot Car Chassis | 1 | Body |
| Battery Pack | 1 | Power |

### Working:
```
Ultrasonic → ESP8266 → Motors
    ↑           ↓
  Servo (scan left/right)
```
- Car moves forward
- Ultrasonic detects obstacle
- Servo rotates sensor to scan left & right
- Car turns to the clearer path
- Self-driving basic concept!

### Key Learning:
- Ultrasonic + Servo combo
- Decision making algorithm
- Autonomous navigation

---

## Group 2: Gesture Control Car 🖐️

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 2 | Car + Remote |
| MPU6050 | 1 | Tilt sensor (remote) |
| MX1508 Motor Driver | 1 | Motor control |
| DC Gear Motors | 2 | Wheels |
| Robot Car Chassis | 1 | Body |
| Active Buzzer | 1 | Horn |
| LED | 1 | Headlight |
| Battery Packs | 2 | Power for both |

### Working:
```
┌─────────┐   ESP-NOW   ┌─────────┐
│ REMOTE  │ ─────────→  │   CAR   │
│ ESP8266 │   Wireless  │ ESP8266 │
│ +MPU6050│             │ +Motors │
└─────────┘             └─────────┘
```
- MPU6050 detects hand tilt angle
- Remote ESP sends data via ESP-NOW
- Car ESP receives and controls motors
- Tilt forward = Car forward, etc.

### Key Learning:
- MPU6050 accelerometer
- ESP-NOW protocol
- Two-way communication

---

## Group 3: Home Automation System 🏠

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| PIR Motion Sensor | 1 | Detect movement |
| Relay Module (5V) | 1 or 2 | Control appliances |
| LED/Bulb | 1 | Light demo |
| Jumper Wires | Set | Connections |
| Breadboard | 1 | Circuit base |

### Working:
```
PIR Sensor → ESP8266 → Relay → Light/Fan
(Motion)     (Process)  (Switch) (Appliance)
```
- PIR detects human movement
- Auto turn ON light when someone enters
- Auto turn OFF after no movement
- Can add web control via phone

### Key Learning:
- PIR sensor working
- Relay for AC appliances
- Smart home concept

---

## Group 4: Air Quality Monitor 🌬️

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| MQ135 Gas Sensor | 1 | Air quality |
| DHT11 Sensor | 1 | Temp & Humidity |
| I2C LCD 16x2 | 1 | Display |
| Jumper Wires | Set | Connections |
| Breadboard | 1 | Circuit base |

### Working:
```
MQ135 + DHT11 → ESP8266 → LCD Display
(Sensors)       (Process)  (Show data)
```
- MQ135 measures air quality (CO2, etc.)
- DHT11 measures temperature & humidity
- LCD shows all readings
- Can add web dashboard

### Key Learning:
- Multiple sensor integration
- I2C LCD communication
- Environmental monitoring

---

## Group 5: Smart Dustbin 🗑️

### Components:
| Component | Quantity | Purpose |
|-----------|----------|---------|
| ESP8266 NodeMCU | 1 | Brain |
| Ultrasonic HC-SR04 | 1 | Hand detection |
| SG90 Servo Motor | 1 | Lid control |
| Jumper Wires | Set | Connections |
| Dustbin | 1 | Body |

### Working:
```
Ultrasonic → ESP8266 → Servo
(Hand detect) (Process) (Open lid)
```
- Ultrasonic detects hand approaching
- Hand within 15cm = Open lid
- Hand moves away = Close lid
- Touchless, hygienic operation

### Key Learning:
- Proximity detection
- Servo for mechanical action
- Practical automation

---

<!-- # 📊 Component Summary

## Common Components (Both Classes):

| Component | Class 9th | Class 10th |
|-----------|-----------|------------|
| ESP8266 NodeMCU | 5 | 6 (G2 needs 2) |
| Ultrasonic HC-SR04 | 1 | 2 |
| SG90 Servo Motor | 2 | 3 |
| MX1508 Motor Driver | 1 | 2 |
| DC Gear Motors | 2 | 4 |
| Active Buzzer | 2 | 1 |
| Relay Module | 1 | 1 |
| LED | 1 | 1 |

## Unique Components:

| Class 9th Only | Class 10th Only |
|----------------|-----------------|
| LDR | MPU6050 |
| Rain Sensor | PIR Sensor |
| 4x3 Keypad | MQ135 Sensor |
| | DHT11 Sensor |
| | I2C LCD 16x2 |

---

# 💰 Estimated Cost

| Class 9th Projects | Cost (₹) |
|-------------------|----------|
| WiFi Car | 800-1000 |
| Smart Blind Stick | 400-500 |
| Rain Detection | 350-450 |
| Smart Street Light | 300-400 |
| Password Lock | 450-550 |
| **Total Class 9th** | **~2500** |

| Class 10th Projects | Cost (₹) |
|-------------------|----------|
| Obstacle Avoidance Car | 900-1100 |
| Gesture Control Car | 1200-1500 |
| Home Automation | 400-500 |
| Air Quality Monitor | 600-750 |
| Smart Dustbin | 450-550 |
| **Total Class 10th** | **~3800** | -->

---

*Connect Shiksha Workshop - December 2025*
