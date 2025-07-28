# laser-security-system
Laser and LDR based security system using transistor and buzzer.
🔒 Laser Security Alarm System

This project is a simple and effective laser-based security alarm system using basic components like a transistor, laser pointer, LDR, and a buzzer.

## 🧰 Components Used
- BC547 Transistor
- Laser Pointer
- LDR (Light Dependent Resistor)
- Buzzer . ṁ
- Resistors
- Breadboard and connecting wires
- 9V Battery
  
## ⚙️ Working Principle

A laser continuously falls on the LDR. When an object interrupts the beam (like a person walking past), the LDR’s resistance changes. This change activates the transistor, which in turn triggers the buzzer to alert intrusion.

## 🔧 Circuit Logic
- The LDR and resistor form a voltage divider.
- When light is present, the LDR has low resistance → transistor stays off.
- When light is blocked, voltage increases → transistor turns on → buzzer sounds.

## ✨ What I Learned
- Basic sensor (LDR) usage
- Transistor as a switch
- Real-time input-output triggering
- Understanding circuit response to light

## 📎 Future Plans
- Convert to PCB version
- Add delay logic or sensitivity control
