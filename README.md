># DiptiBraille
DiptiBraille is an affordable keyboard designed for the visually impaired, enabling text input using Braille. It supports document writing, reading, and audio playback for audiobooks. Users can connect an external Braille display for enhanced feedback.

Wireless options include WiFi and WebShare for easy data transfer. Essential communication features like call and SMS are included for seamless interaction.

With a sleek design and intuitive interface, DiptiBraille offers a modern, user-friendly experience for visually impaired individuals.
># Operating System
DiptiOS/1 is a pioneering operating system meticulously crafted to cater to the unique needs of braille users. Rooted in the robust framework of FreeRTOS, DiptiOS/1 sets a new standard for accessibility, seamlessly integrating with braille display hardware to deliver unparalleled functionality and ease of use.
| OS Feature                      | Description                                                                                               |
|------------------------------|-----------------------------------------------------------------------------------------------------------|
| Optimized Braille Support   | Comprehensive support for braille display devices ensures smooth input and output.                        |
| Intuitive Interface         | User-friendly interface tailored for braille users prioritizes ease of navigation.                          |
| Real-Time Responsiveness    | Built on FreeRTOS for instant feedback and interaction.                                                    |
| Customization Options       | Personalize braille experience with customizable settings.                                                  |
| Seamless Connectivity       | Effortless data exchange with other devices and platforms.                                                  |
| Enhanced Accessibility     | Enjoy voice feedback and screen magnification.                                                             |
| Reliability and Stability  | Backed by FreeRTOS for consistent performance and uptime.                                                   |


># Hardware
### Printed Circuit Boards
|**Base Material:** FR-4|**Layers:** 2|**Thickness:** 1.6 mm|**Surface:** HASL(with lead)|**Quality:** IPC 2|**Silkscreen:** White|
|-----------------------|-------------|---------------------|----------------------------|------------------|---------------------|

| Main Unit PCB Outlook | Additional Info | **Display Unit PCB Outlook**  | **Additional Info** |
|---------------------------|---------------------------------------------------------|---------------------------|---------------------------------------------------------|
| <img src="image/mainunit.PNG" width="300" height="180"> |**Price:** $13<br> **Dim:** 251x148<br> **Color:** Green<br> | <img src="image/displayunit.PNG" width="300" height="180"> | **Price:** $7<br>**Dim:** 116x77<br> **Color:** Black |

### 🔧 Components List
| Component                           | Quantity | Component                           | Quantity |
|-------------------------------------|----------|-------------------------------------|----------|
| 💻 ESP32 S3 N16R8                   | x1       | 📶 SIM800L GSM module               | x1       |
| ⌨️ Cherry MX Mechanical keys        | x16      | ⌨️ Mechanical Key Cap               | x16      |
| 🔊 I2S Amplifier                    | x1       | 🔊 Speaker 3W                       | x1       |
| 📇 SD Card Module                   | x1       | 📇 SD Card                          | x1       |
| ⚙️ Motor Driver - TB6612FNG         | x6       | 🔄 Shift Register - 74HC595         | x2       |
| 🔋 4.2v 2000mAh Li-on Battery       | x3       | ⚡ BMS (Circuit Protector)          | x1       |
| ⚡ 5V Constant Step Down BUCK Converter | x2    | 🔌 12v Laptop Charger               | x1       |
| ⚡ Capacitor                        | x2       | ⚡ Diode                            | x20      |
| 🔘 Push Button                      | x10      |                                     |          |


  
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
