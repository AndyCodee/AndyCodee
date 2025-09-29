# 👋 Hi, I'm Andy Shao

🎓 Master's student in **Electrical Engineering** at **National Chung Cheng University**.

---

## 🚀 Core Competencies

- **ARM Cortex-M3 expertise**: Bare-metal to FreeRTOS development on STM32F103  
- **Multi-platform MCU experience**: 8051, Nuvoton (NUC140, M032KG), STM32F1 series  
- **Bootloader & image management**: External **NOR Flash (W25Q64)** → internal Flash, CRC32 validation, vector table relocation  
- **FreeRTOS system design**: Task/queue architecture, ISR handling, timing, runtime profiling
- **Peripheral integration**: SPI, I²C (incl. bit-bang), UART, ADC, PWM, EXTI, GPIO modes with custom drivers  
- **Clean C/C++ firmware**: Maintainable structure, modular design, and project-oriented documentation/diagrams  

---

## 💼 Featured Projects

### 🔧 MCU Applications

**[STM32 External NOR Flash Bootloader (STM32F103 + W25Q64)](https://github.com/AndyCodee/STM32-External-NOR-Flash-Bootloader)**  
• Custom **bootloader** capable of loading multiple firmware images from external **W25Q64 NOR Flash** into STM32 internal Flash  
• Implements **LCD9648 menu UI** with key input for selecting repos (Repo1, Repo2, …)  
• Uses **hardware CRC32** verification to ensure image integrity before execution  
• Supports **multi-firmware management**, safe update, and clean handover via **vector table relocation**  

**[Embedded-FreeRTOS-SensorHub (STM32F103)](https://github.com/AndyCodee/Embedded-FreeRTOS-SensorHub)**  
• Professional firmware project with **FreeRTOS** task scheduling on STM32F103  
• Six concurrent tasks: OLED, LCD Monitor, Rotary Encoder, Motor, IR Sensor, DHT11  
• Implements **real-time motor control**, IR-triggered emergency stop, and dual-display system monitoring  
• Highlights **task modularity, queue-based design, and runtime CPU profiling**  

**[Color Recognition on NUC140](https://github.com/AndyCodee/NuMicro-NUC140_Color_Recognition)**  
• Real-time RGB detection via photoresistors  
• Utilizes ADC, signal preprocessing, and embedded neural network for classification  

**[Banknote Recognition on M032KG](https://github.com/AndyCodee/NuMaker-M032KG_Banknote_Recognition)**  
• Sensed RGB via photoresistors and ADC as time-series signals  
• Preprocessed data and classified with embedded neural network  

**[LCD-Keypad GuessNum Game (8051)](https://github.com/AndyCodee/GuessNumber-LCD-Keypad)**  
• Number guessing game implemented with LCD1602 and 4x4 matrix keypad  
• Developed on STC89C52RC using register-level control  

---

### 🎯 Computer Vision

**[AI CUP 2023: Badminton Judge System](https://github.com/AndyCodee/AI-CUP-2023-Badminton)**  
• Developed a vision-based shuttlecock and player tracking system  
• Used OpenCV and deep learning to automate line judgment in badminton games  

---

## 🧠 Skills & Technologies  

### 🔑 Core Strengths – MCU / Embedded
- **MCUs**: 8051, Nuvoton (NUC140 / M032KG – Cortex-M0), STM32F103 – Cortex-M3
- **RTOS & Firmware**: FreeRTOS design with tasks, queues, mutexes, semaphores, task notifications, and timers; ISR handling and runtime profiling
- **Development Tools**: Keil MDK-ARM, register-level programming  
- **Peripherals & Protocols**: SPI, I²C, UART, ADC, PWM, GPIO/EXTI configuration  
  - Applied in **NOR Flash (W25Q64) driver development** and external image management  

### 🛠 Supporting Skills – Software
- **C / C++**: Embedded systems, hardware abstraction, driver development  
- **Python**: Computer vision, ML prototyping, automation scripting  
- **PHP / SQL**: Basic backend development & data management  
- **Java**: Academic coursework, algorithm implementation  

---

## 📊 GitHub Activity

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AndyCodee&layout=compact&exclude_repo=AndyCodee.github.io,RepoGallery&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515)](https://github.com/anuraghazra/github-readme-stats)

---

## 📫 Contact

- GitHub: [@AndyCodee](https://github.com/AndyCodee)  
- Email: **ouchenhenry@gmail.com**
