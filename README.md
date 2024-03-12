># DiptiBraille
DiptiBraille is a specialized **low-cost keyboard** designed **for the visually impaired**, enabling them to input text using Braille, a tactile writing and reading system used by people with vision loss. It features **📝 document writing** and **📖 reading capabilities**, allowing users to seamlessly create and access documents in various formats. Additionally, it supports **🎧 audio playback** with audiobooks, providing an inclusive reading experience. Users can also connect an **🔠 external Braille display** for enhanced tactile feedback. Its wireless connectivity options include **📡 WiFi** and **📶 WebShare** for easy data transfer and accessibility. The keyboard also offers essential communication features like **📱 call** and **💬 SMS functionalities**, ensuring seamless interaction for users. With its sleek design and intuitive interface, DiptiBraille provides a modern and user-friendly experience for visually impaired individuals.

## Printed Circuit Boards

| Main Unit PCB Tracing | Main Unit PCB Outlook | Additional Info |
|-------------------------|---------------------------|---------------------------------------------------------|
| <img src="image/mainpcb.PNG" width="400" height="250"> | <img src="image/mainunit.PNG" width="400" height="250"> |  **Printing Website:** [JLCPCB](https://jlcpcb.com/) <br>**Build Time:** 2 days<br>**Min. Quantity:** 5pcs<br>**Price:** $18.10 for 5 pieces ($3.62 each)<br>**Base Material:** FR-4<br>**Layers:** 2<br> **Dimension:** 251.16 mm * 148.16 mm<br> **PCB Thickness:** 1.6 mm<br> **PCB Color:** Green<br>**Surface Finish:** HASL (with lead)<br>**Appearance Quality:** IPC Class 2 Standard<br>**Silkscreen:** White |


| Display Unit PCB Tracing          | Display Unit PCB Outlook          |
|-----------------------------------|-----------------------------------|
| ![pcb1trc](image/displaypcb.PNG)           | ![pcb1shw](image/displayunit.PNG)           |

> ## 🛠️ Hardware List
- ESP32 S3 N16R8 💻 x1
- SIM800L GSM module 📶 x1
- Cherry MX Mechanical keys ⌨️ x16
- Mechanical Key Cap ⌨️ x16
- I2S Amplifier 🔊 x1
- Speaker 3W 🔊 x1
- SD Card Module 📇 x1 (SPI)
- SD Card 📇 x1 (Min:1GB Max:32GB)
- Motor Driver - TB6612FNG ⚙️ x6
- Shift Register - 74HC595 🔄 x2
- 4.2v 2000mAh Li-on Battery 🔋 x3 (Configured in 3S)
- BMS (Circuit Protector) ⚡ x1 (Min. 20A recommended)
- 5V Constant Step Down BUCK Converter ⚡ x2
- 12v Laptop Charger 🔌 x1
- Capacitor ⚡ x2 (1uF,470uF)
- Diode ⚡ x20
- Push Button 🔘 x10
  
>## 🔮 Wishlist
- [📝 **Write**](#-write)
  - [📄 Doc Writing](#-doc-writing)✅
  - [🖋️ Practice Writing](#-practice-writing)✅
  - [📚 Learn Writing](#-learn-writing)✅
  
- [📖 **Read**](#-read)
  - [📜 Doc Reading](#-doc-reading)✅
  - [📖 Practice Reading](#-practice-reading)✅
  - [📘 Learn Reading](#-learn-reading)✅
  
- [🎧 **AudioBook**](#-audiobook)
  - [📕 English Book](#-english-book) ✅
  - [📙 Bengali Book](#-bengali-book) ❌
  - [📗 Math Book](#-math-book) ❌

- [🧮 **Calculator**](#-calculator)

- [📡 **Wireless**](#-wireless)
  - [<img src="https://camo.githubusercontent.com/e80580d13d9769082fdd40894d586e4c8611da7998068ef2294ba35dd5975b15/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313036373930372f313733313732342f37353661333561322d363330662d313165332d383732632d3936323166666364623830322e706e67" alt="WiFi Icon" width="24" height="24"> WiFi](#-wifi) 🔄
  - [<img src="https://static-00.iconduck.com/assets.00/bluetooth-icon-1365x2048-1dbwtuc9.png" alt="Bluetooth Icon" width="16" height="17">Bluetooth](#-bluetooth)❌
  - <img src="https://dbservices.com/assets/article/2019/10/filemaker-cloud-1.png" alt="WebShare Icon" width="24" height="24"> [WebShare](#-webshare)✅ 
  - <img src="https://www.unifiedremote.com/remotes/raw/unifiedremote_remotes_master/main_command/icon_hires.png" alt="RemoteShell Icon" width="20" height="20"> [RemoteShell](#-remoteshell)❌
  - ⌨️ [BLE KeyBoard](#-ble-keyboard) 🔄

- [📱 **Phone**](#-phone)
  - 📞 Call ✅
  - 💬 SMS 🔄

- [⚙️ **Settings**](#-settings)
