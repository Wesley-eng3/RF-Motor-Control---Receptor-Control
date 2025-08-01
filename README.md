# 📡 RF Receiver with HT12D — 4-Channel Remote Control Relay

This project is a **wireless RF receiver** for remote switching of up to **4 independent loads**, using the **HT12D decoder IC**, a 433 MHz RF module, and relay drivers. It’s ideal for building custom **garage openers, lighting control**, or **DIY home automation**.

---

Overview PCB

<img width="780" height="812" alt="Image" src="https://github.com/user-attachments/assets/2d05402b-6d04-4212-89d8-787ee20ec519" />

## 🔌 **How It Works**

1️⃣ The RF module receives a wireless signal from a compatible transmitter.  
2️⃣ The **HT12D** decodes the address and data.  
3️⃣ Valid data triggers output pins, which drive **PNP transistors**.  
4️⃣ The transistors switch **12 V relays** to control external loads.  
5️⃣ A status **LED** indicates a valid transmission.

---

## ⚙️ **Key Features**

- **Up to 4 outputs:** Each output switches a separate relay.
- **12 V relay control:** Suitable for motors, lights, or other devices.
- **Protected outputs:** Flyback diodes protect the circuit.
- **Stable power:** Onboard **LM7805** provides regulated 5 V to the decoder.
- **Plug & play:** Simple pin header for connecting outputs.

---

## 🗂️ **Schematic Overview**

Schematic 
<img width="1237" height="812" alt="Image" src="https://github.com/user-attachments/assets/bd012ab1-6ea7-46b6-a03a-9344152e3c42" />

**Main components:**
- **RF Module** (TR003-500-P02BE)
- **HT12D Decoder IC**
- **LM7805 Voltage Regulator**
- **PNP Transistors (Q1–Q4)**
- **12 V Relays (PR13-12V-450-1C)**
- **Flyback Diodes (1N4001)**

---

## 📁 **Project Structure**

📁 /hardware
├─ Schematic (.SchDoc)
├─ PCB Layout (.PcbDoc)
├─ BOM

## 🚧 **Status**

✔️ Schematic complete  - (Altium Tool)
✔️ PCB design in progress  
✔️ Tested in breadboard prototype  
🚧 PCB fabrication & final tests next

TOP Layer
<img width="1012" height="668" alt="Image" src="https://github.com/user-attachments/assets/9498c772-50a9-4669-82fd-efc9861ee4ca" />

Bottom Layer

<img width="1010" height="672" alt="Image" src="https://github.com/user-attachments/assets/6d0746e4-a00a-4506-81bd-f7eeca691d97" />
