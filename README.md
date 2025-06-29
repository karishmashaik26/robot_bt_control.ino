# robot_bt_control.ino
# 🤖 Bluetooth-Controlled Robot Car using Arduino

This Arduino project lets you control a 2-wheel drive robot car via Bluetooth using an HC-05/06 module. It supports basic movement commands and LED control via smartphone Bluetooth apps.

---

## 📲 Commands List

| Command | Action               |
|---------|----------------------|
| `F`     | Move Forward         |
| `B`     | Move Backward        |
| `L`     | Turn Right           |
| `R`     | Turn Left            |
| `W`     | Turn LED1 ON         |
| `w`     | Turn LED1 OFF        |
| `X`     | Turn LED2 ON         |
| `x`     | Turn LED2 OFF        |
| `S`     | STOP all motors/LEDs |

---

## 🧰 Components Required

- Arduino UNO
- L298N Motor Driver or 4 GPIOs
- 2x DC Motors
- HC-05/HC-06 Bluetooth module
- 2x LEDs
- Jumper Wires, Breadboard

---

## 🔌 Wiring

| Component      | Arduino Pin |
|----------------|-------------|
| HC-05 Tx       | D2 (RxD)    |
| HC-05 Rx       | D3 (TxD)    |
| Left Motor FWD | D13         |
| Left Motor REV | D12         |
| Right Motor FWD| D11         |
| Right Motor REV| D10         |
| LED1           | D9          |
| LED2           | D8          |

---

## 🔧 How to Use

1. Upload code to Arduino
2. Power the bot
3. Pair Bluetooth from phone (use password `1234` or `0000`)
4. Use an app like **Serial Bluetooth Terminal** or **Bluetooth Controller**
5. Send commands (`F`, `B`, etc.)

---

## 📁 Files

- `code/robot_bt_control.ino` – Main Arduino sketch

---

## 🚀 Future Improvements

- Add distance sensor for obstacle avoidance
- Add speed control via PWM
- Implement Android app for custom buttons

---

