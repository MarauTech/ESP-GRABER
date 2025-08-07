# 🚀 ESP-GRABER  
**Multiband RF Signal Tool for ESP32 + CC1101**

---

## 🇬🇧 ABOUT

**ESP-GRABER** is a versatile tool for working with radio frequencies in the 315 / 433 / 868 / 915 MHz bands, based on an ESP32 microcontroller with a CC1101 RF module and OLED display.

The firmware allows reading, repeating, analyzing, storing, and — with caution — jamming RF signals. It's intended for **educational and testing purposes only**.

> ⚠️ **Disclaimer**  
> This firmware is for **research and legal RF hardware testing only**.  
> You must comply with the laws in your country.  
> **Jammers are illegal.**  
> By flashing and using this firmware, **you accept full responsibility**.

---

## ⚡ Features

📶 **SubGHz Bands:** 315 • 433 • 868 • 915 MHz  
🛰️ **Capabilities:**
- 🔍 Signal Reader  
- 🔄 Signal Repeater  
- 📊 Frequency Analyzer  
- 🚫 Signal Delete  
- 💾 Signal Storage (up to 20 keys)  
- 🛰️ RF Jammer (**illegal**)  

📡 **Supported Modulations:**
- Princeton  
- RcSwitch  
- Came  
- Holtec  
- Nice  
- StarLine  
- KeeLoq  

---

## 🧩 Hardware Requirements

This firmware runs on:
- ESP32 development board
- CC1101 RF transceiver
- OLED display (I2C)
- 4x buttons for user input

### 📺 Display (I2C)
| Pin | ESP32 |
|-----|-------|
| VCC | 3V3   |
| GND | GND   |
| SCL | G22   |
| SDA | G21   |

### 🔘 Buttons
| Button | GPIO |
|--------|------|
| K1     | G27  |
| K2     | G26  |
| K3     | G33  |
| K4     | G32  |

### 📡 CC1101 Connections
| CC1101 Pin | ESP32 |
|------------|-------|
| 1 (GND)    | GND   |
| 2 (VCC)    | 3V3   |
| 3          | G2    |
| 4          | G5    |
| 5          | G18   |
| 6          | G23   |
| 7          | G19   |

---

## 🧪 Flashing

Use the web flasher to upload firmware directly to your ESP32:

👉 **[FLASH NOW](https://marautech.github.io/ESP-GRABBER-FLASHER/)**

---

## 🛒 Ready-to-use PCBs

Purchase pre-assembled ESP-GRABER boards at:  
🌐 **[https://shop.marautech.pl](https://shop.marautech.pl)**

---

## 📸 Preview

<img width="1160" height="770" alt="ESP-GRABBER Preview" src="https://github.com/user-attachments/assets/030690ab-6242-4c3b-abf2-7c971b649095" />

---

## 👤 Credits

- Firmware created by **Teapot174**  
- Hardware integration and distribution by **MarauTech**

---

---

## 🇵🇱 O PROGRAMIE

**ESP-GRABER** to narzędzie RF oparte na ESP32 z modułem **CC1101**, umożliwiające analizę, odbiór, zapis i nadawanie sygnałów radiowych w pasmach: **315 / 433 / 868 / 915 MHz**.

Projekt jest stabilny, ale może być rozwijany o kolejne funkcje.

> ⚠️ **Zastrzeżenie prawne**  
> Oprogramowanie przeznaczone jest wyłącznie do celów **badawczych i testowych**.  
> Korzystając z firmware’u, użytkownik zobowiązuje się przestrzegać prawa swojego kraju.  
> **Zakłócacze (jammery) są nielegalne.**  
> Korzystanie oznacza pełną akceptację tych warunków.

---

## ⚡ Funkcje

- 📶 Obsługiwane pasma: 315 / 433 / 868 / 915 MHz  
- 🔍 Odczyt sygnałów  
- 🔄 Powtarzanie sygnałów  
- 📊 Analiza częstotliwości  
- 💾 Zapis do 20 sygnałów  
- 🚫 Usuwanie sygnałów  
- 🛰️ **Zakłócanie sygnałów (NIELEGALNE)**

---

## 📡 Obsługiwane modulacje

- Princeton  
- RcSwitch  
- Came  
- Holtec  
- Nice  
- StarLine  
- KeeLoq  

---

## 🔌 Połączenia

### 📺 OLED (I2C)

| Wyświetlacz | ESP32 |
|-------------|-------|
| VCC         | 3V3   |
| GND         | GND   |
| SCL         | G22   |
| SDA         | G21   |

### 🔘 Przyciski

| Przycisk | GPIO |
|----------|------|
| K1       | G27  |
| K2       | G26  |
| K3       | G33  |
| K4       | G32  |

### 📡 CC1101

| Pin | ESP32 |
|-----|-------|
| 1 (GND)  | GND   |
| 2 (VCC)  | 3V3   |
| 3        | G2    |
| 4        | G5    |
| 5        | G18   |
| 6        | G23   |
| 7        | G19   |

---

## 🧪 Flashowanie

Flashuj gotowy firmware bezpośrednio z przeglądarki:  
👉 **[https://marautech.github.io/ESP-GRABBER-FLASHER/](https://marautech.github.io/ESP-GRABBER-FLASHER/)**

---

## 🛒 Gotowe płytki

Płytki i zestawy dostępne na:  
🛍️ **[https://shop.marautech.pl](https://shop.marautech.pl)**

---

## 📸 Podgląd

<img width="1160" height="770" alt="ESP-GRABBER Preview" src="https://github.com/user-attachments/assets/030690ab-6242-4c3b-abf2-7c971b649095" />

---

## 👤 Autorzy

- Firmware: **Teapot174**  
- Integracja i dystrybucja: **MarauTech**

---
