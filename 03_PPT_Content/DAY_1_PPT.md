# 🎨 DAY 1 PPT - Theory & Introduction

## Total Slides: 15 | Time: 45 Minutes

---

## 📊 SLIDE 1: Title Slide (30 sec)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│          🤖 IoT & ROBOTICS WORKSHOP 🚀                 │
│                                                         │
│                  DAY 1: Introduction                    │
│                                                         │
│              Connect Shiksha Presents                   │
│                                                         │
│           "Machines को Smart बनाना सीखो!"              │
│                                                         │
│                   Class 9th / 10th                      │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 2: What We'll Learn Today (30 sec)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              📚 आज क्या सीखेंगे?                        │
│                                                         │
│    ┌─────────────────────────────────────┐             │
│    │  1. IoT क्या है?                    │             │
│    │  2. Robotics क्या है?               │             │
│    │  3. ESP8266 - Robot का Brain       │             │
│    │  4. Sensors - Robot की आँखें        │             │
│    │  5. Actuators - Robot के हाथ-पैर    │             │
│    │  6. आपके Projects!                 │             │
│    └─────────────────────────────────────┘             │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 3: What is IoT? (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              🌐 IoT क्या है?                            │
│                                                         │
│         IoT = Internet of Things                        │
│                                                         │
│    "जब Normal चीज़ें SMART बन जाती हैं!"               │
│                                                         │
│    ┌────────────────────────────────────┐              │
│    │  Normal        →      Smart        │              │
│    ├────────────────────────────────────┤              │
│    │  💡 Bulb       →   Smart Light     │              │
│    │  ❄️ AC         →   Smart AC        │              │
│    │  ⌚ Watch      →   Smart Watch     │              │
│    │  🚗 Car        →   Smart Car       │              │
│    └────────────────────────────────────┘              │
│                                                         │
│         Examples: Alexa, Google Home, Smart TV          │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 4: What is Robotics? (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              🤖 Robotics क्या है?                       │
│                                                         │
│     "Machines जो खुद DECISIONS ले सकती हैं!"           │
│                                                         │
│                                                         │
│         ┌───────┐   ┌───────┐   ┌───────┐             │
│         │ SENSE │ → │ THINK │ → │  ACT  │             │
│         │  👁️   │   │  🧠   │   │  💪   │             │
│         └───────┘   └───────┘   └───────┘             │
│                                                         │
│                                                         │
│    Examples:                                            │
│    • Self-driving Cars (Tesla)                         │
│    • Delivery Drones (Amazon)                          │
│    • Robot Vacuum Cleaners                             │
│    • Factory Robots                                    │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 5: The Brain - ESP8266 (2 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           🧠 ESP8266 = Robot का BRAIN                  │
│                                                         │
│    ┌─────────────────────────────────────┐             │
│    │         [ESP8266 IMAGE]             │             │
│    │    ┌───────────────────────┐        │             │
│    │    │  D0 D1 D2 D3 D4 D5    │        │             │
│    │    │     ESP8266           │        │             │
│    │    │     NodeMCU           │        │             │
│    │    │  VIN GND 3V3 A0       │        │             │
│    │    └───────────────────────┘        │             │
│    └─────────────────────────────────────┘             │
│                                                         │
│    Features:                                            │
│    ✅ Built-in WiFi                                    │
│    ✅ GPIO Pins (D0-D8)                                │
│    ✅ Analog Pin (A0)                                  │
│    ✅ USB Programming                                  │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 6: ESP8266 Pins (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              📌 ESP8266 के Pins                         │
│                                                         │
│    ┌─────────────────────────────────────┐             │
│    │  Pin Type     │  Use               │             │
│    ├───────────────┼────────────────────┤             │
│    │  VIN / 5V     │  Power Input       │             │
│    │  3.3V         │  Low Power Output  │             │
│    │  GND          │  Ground (-)        │             │
│    │  D0 - D8      │  Digital I/O       │             │
│    │  A0           │  Analog Input (1!) │             │
│    └─────────────────────────────────────┘             │
│                                                         │
│    ⚠️ Important:                                       │
│    • Only 1 Analog pin (A0)                            │
│    • Logic Level = 3.3V (not 5V!)                      │
│    • WiFi built-in                                     │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 7: What are Sensors? (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           👁️ SENSORS = Robot की आँखें, कान, नाक        │
│                                                         │
│                                                         │
│         Sensor → ENVIRONMENT को SENSE करता है          │
│                                                         │
│                                                         │
│    ┌─────────────────────────────────────┐             │
│    │                                     │             │
│    │   🌡️ Temperature    👁️ Light        │             │
│    │                                     │             │
│    │   📏 Distance       💨 Air Quality  │             │
│    │                                     │             │
│    │   🏃 Motion         💧 Water/Rain   │             │
│    │                                     │             │
│    └─────────────────────────────────────┘             │
│                                                         │
│         "Sensor data देता है, Brain decide करता है"    │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 8: Types of Sensors (2 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              🔬 Different Sensors                       │
│                                                         │
│  ┌────────────────────────────────────────────────┐    │
│  │  Sensor       │  Detects        │  Projects    │    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  Ultrasonic   │  Distance       │  Blind Stick │    │
│  │  (HC-SR04)    │                 │  Obstacle Car│    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  LDR          │  Light          │  Street Light│    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  PIR          │  Motion         │  Home Auto   │    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  Rain Sensor  │  Water          │  Rain Detect │    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  MQ135        │  Air Quality    │  Air Monitor │    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  DHT11        │  Temp/Humidity  │  Air Monitor │    │
│  ├───────────────┼─────────────────┼──────────────┤    │
│  │  MPU6050      │  Tilt/Angle     │  Gesture Car │    │
│  └───────────────┴─────────────────┴──────────────┘    │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 9: What are Actuators? (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           💪 ACTUATORS = Robot के हाथ-पैर              │
│                                                         │
│                                                         │
│         Brain Command देता है → Actuator ACTION करता है │
│                                                         │
│                                                         │
│    ┌─────────────────────────────────────┐             │
│    │                                     │             │
│    │   ⚙️ Motors        🔊 Buzzer        │             │
│    │   (Movement)       (Sound)          │             │
│    │                                     │             │
│    │   🔄 Servo         💡 LED/Relay     │             │
│    │   (Angle rotate)   (Light/Switch)   │             │
│    │                                     │             │
│    └─────────────────────────────────────┘             │
│                                                         │
│         "Sensor INPUT, Actuator OUTPUT"                │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 10: Types of Actuators (2 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              ⚙️ Different Actuators                     │
│                                                         │
│  ┌────────────────────────────────────────────────┐    │
│  │  Actuator     │  Action          │  Projects   │    │
│  ├───────────────┼──────────────────┼─────────────┤    │
│  │  DC Motor     │  Continuous      │  Cars       │    │
│  │               │  Rotation        │  Robots     │    │
│  ├───────────────┼──────────────────┼─────────────┤    │
│  │  Servo Motor  │  Fixed Angle     │  Lock       │    │
│  │  (SG90)       │  (0°-180°)       │  Dustbin    │    │
│  ├───────────────┼──────────────────┼─────────────┤    │
│  │  Relay        │  High Power      │  Light      │    │
│  │               │  ON/OFF          │  Fan        │    │
│  ├───────────────┼──────────────────┼─────────────┤    │
│  │  Buzzer       │  Sound Alert     │  Blind Stick│    │
│  ├───────────────┼──────────────────┼─────────────┤    │
│  │  LED          │  Visual Light    │  Indicators │    │
│  └───────────────┴──────────────────┴─────────────┘    │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 11: Motor Driver (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           🔌 MOTOR DRIVER क्यों?                        │
│                                                         │
│                                                         │
│    ESP8266 (3.3V) ──❌──→ Motor (6-12V)                 │
│           "Direct नहीं चलेगा!"                          │
│                                                         │
│                                                         │
│    ┌─────────┐    ┌──────────────┐    ┌─────────┐     │
│    │ ESP8266 │ →  │ Motor Driver │ →  │  Motor  │     │
│    │ (Signal)│    │ (L298N/MX1508)│   │ (Power) │     │
│    └─────────┘    └──────────────┘    └─────────┘     │
│                          ↑                             │
│                     Battery 🔋                         │
│                                                         │
│    Motor Driver:                                        │
│    • Signal को Power में convert करता है               │
│    • Direction control (Forward/Reverse)               │
│    • Speed control (PWM)                               │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 12: Complete Flow (1 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│              🔄 IoT PROJECT FLOW                        │
│                                                         │
│                                                         │
│    ┌─────────┐    ┌─────────┐    ┌─────────┐          │
│    │ SENSOR  │ →  │  ESP    │ →  │ACTUATOR │          │
│    │ (Input) │    │ (Brain) │    │(Output) │          │
│    └─────────┘    └─────────┘    └─────────┘          │
│         │              │              │               │
│     Sense karo    Process karo   Action lo            │
│                                                         │
│                                                         │
│    Example: Smart Street Light                         │
│    ┌─────────────────────────────────────┐            │
│    │  LDR  →  ESP8266  →  Relay  →  💡   │            │
│    │"Dark" → "Light ON" → Switch → Light │            │
│    └─────────────────────────────────────┘            │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 13: Your Projects! - Class 9th (1.5 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           🏫 CLASS 9th PROJECTS                        │
│                                                         │
│  ┌──────┬────────────────────┬─────────────────────┐   │
│  │Group │ Project            │ Components          │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  1   │ WiFi Controlled Car│ ESP, Motors, Driver │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  2   │ Smart Blind Stick  │ ESP, Ultrasonic,    │   │
│  │      │                    │ Buzzer              │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  3   │ Rain Detection     │ ESP, Rain Sensor,   │   │
│  │      │                    │ Servo               │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  4   │ Smart Street Light │ ESP, LDR, Relay     │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  5   │ Password Door Lock │ ESP, Keypad, Servo  │   │
│  └──────┴────────────────────┴─────────────────────┘   │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 14: Your Projects! - Class 10th (1.5 min)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           🏫 CLASS 10th PROJECTS                       │
│                                                         │
│  ┌──────┬────────────────────┬─────────────────────┐   │
│  │Group │ Project            │ Components          │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  1   │ Obstacle Avoidance │ ESP, Ultrasonic,    │   │
│  │      │ Car                │ Servo, Motors       │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  2   │ Gesture Control Car│ ESP×2, MPU6050,     │   │
│  │      │                    │ Motors              │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  3   │ Home Automation    │ ESP, PIR, Relay     │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  4   │ Air Quality Monitor│ ESP, MQ135, DHT11,  │   │
│  │      │                    │ LCD                 │   │
│  ├──────┼────────────────────┼─────────────────────┤   │
│  │  5   │ Smart Dustbin      │ ESP, Ultrasonic,    │   │
│  │      │                    │ Servo               │   │
│  └──────┴────────────────────┴─────────────────────┘   │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📊 SLIDE 15: Component Time! (30 sec)

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│           🛠️ COMPONENT DISTRIBUTION TIME!              │
│                                                         │
│                                                         │
│         ┌─────────────────────────────┐                │
│         │                             │                │
│         │   📦 अपनी Kit लो            │                │
│         │                             │                │
│         │   🔍 Parts Identify करो     │                │
│         │                             │                │
│         │   ❓ Doubts पूछो            │                │
│         │                             │                │
│         └─────────────────────────────┘                │
│                                                         │
│                                                         │
│            कल से Building शुरू! 🔧                     │
│                                                         │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 📋 Slide Summary

| Slide | Content | Time |
|-------|---------|------|
| 1 | Title | 30 sec |
| 2 | Today's Agenda | 30 sec |
| 3 | What is IoT | 1 min |
| 4 | What is Robotics | 1 min |
| 5 | ESP8266 Brain | 2 min |
| 6 | ESP8266 Pins | 1 min |
| 7 | What are Sensors | 1 min |
| 8 | Types of Sensors | 2 min |
| 9 | What are Actuators | 1 min |
| 10 | Types of Actuators | 2 min |
| 11 | Motor Driver | 1 min |
| 12 | Complete Flow | 1 min |
| 13 | Class 9th Projects | 1.5 min |
| 14 | Class 10th Projects | 1.5 min |
| 15 | Component Time | 30 sec |
| **Total** | | **~18 min** |

*Remaining ~27 min for physical demo, distribution, and Q&A*

---

*Day 1 PPT Complete!*
