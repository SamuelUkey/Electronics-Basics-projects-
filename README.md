# ⚡ Electronics Basics — Foundational Circuit Projects

A collection of foundational analog/digital electronics projects built while
learning core circuit design concepts — timers, counters, and voltage
regulation — before moving into microcontroller-based work (see [Desk Buddy](https://github.com/SamuelUkey/Desk-Buddy)
for my current focus).

---

## 🔋 Mini 5V Power Supply Board

A regulated 5V power supply using the 7805 voltage regulator, converting a
9V DC input into a stable 5V output for powering small electronics.

**Components:** 7805 Voltage Regulator, 9V Battery, 220Ω Resistor, LED,
0.33µF & 0.1µF Capacitors, Input/Output Connectors

**Applications:** Arduino/ESP32 power supply, breadboard power source for
small projects


---

## 🚦 Traffic Light System (555 Timer + CD4017)

A traffic light controller built without a microcontroller. A 555 Timer
(astable mode) generates clock pulses that drive a CD4017 decade counter,
sequentially switching Red → Yellow → Green LEDs to simulate a real traffic
signal.

**Components:** NE555 Timer IC, CD4017 Decade Counter, Red/Yellow/Green
LEDs, Resistors, Capacitors, Transistor (LED driving)

*(Add circuit/simulation image here)*

---

## 🎲 Digital Dice (555 Timer + CD4017)

An electronic dice that simulates a roll using LED patterns. The 555 Timer
generates continuous pulses into a CD4017 counter cycling through LED
combinations; a push button stops the counter at a pseudo-random position
to "roll" a number 1–6.

**Components:** NE555 Timer IC, CD4017 Decade Counter, LEDs, Push Button,
Resistors, Capacitors

*(Add circuit image here)*

---

## 🛠️ Tools Used Across These Projects

- KiCad
- Tinkercad
- Multimeter

## 📚 Skills Practiced

- 555 Timer IC applications (astable mode)
- Decade counter / sequential digital circuits
- Voltage regulation and power electronics basics
- LED interfacing and driving
- Breadboard prototyping and circuit troubleshooting

---

## 🔮 Possible Future Improvements

- PCB versions of each circuit
- Traffic light: pedestrian crossing + vehicle sensors
- Digital dice: 7-segment display output
- Power supply: switch-mode (buck) version for higher efficiency

---

## 👤 Author

**Samuel Ukey**
Electronics & Telecommunication Engineering Student
