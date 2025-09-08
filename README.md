# RFID Door Lock System

This project is an **Arduino-based RFID Door Lock System**, inspired by the tutorial from SriTu Hobby. It uses an RFID reader (RC522) to scan cards/tags and a servo motor to lock/unlock a door. The system provides a simple and effective way to control access.

---

## 📺 Reference Video
This project is based on the tutorial: [RFID door lock access control system](https://www.youtube.com/watch?v=GOO84CGBPz8)

---

## 🔧 Components Used
- Arduino Uno  
- RFID Reader (RC522)  
- RFID Tags / Cards  
- Servo Motor  
- Jumper Wires  
- Breadboard  

---

## ⚙️ Procedure
1. Connect the Arduino with the RFID reader and servo motor according to the circuit diagram.  
2. Install the **Arduino IDE** and add the **MFRC522 library** from the Library Manager.  
3. Upload the Arduino sketch (`rfid_doorlock.ino`) to your board.  
4. Register the RFID card/tag IDs in the code.  
5. When an authorized RFID tag is scanned, the servo rotates to unlock the door.  
6. If the tag is not authorized, the servo remains locked.  

---
