# Home Automation Using Alexa & IoT

A smart home automation system developed during my B.Tech that enables users to control electrical appliances using **Alexa voice commands** and a **mobile application**. This project is implemented using **ESP32** to communicate with appliances and execute voice-based commands.

## 🚀 Features
- **Voice Control with Alexa:** Turn appliances ON/OFF using voice commands.
- **Mobile App Integration:** Control appliances remotely.
- **ESP32-based Implementation:** Efficient and low-power microcontroller for IoT.
- **Real-World Deployment:** Successfully implemented and tested in a real environment.

## 🛠️ Tech Stack
- **Programming Language:** C++
- **Microcontroller:** ESP32
- **Communication Protocol:** MQTT / Wi-Fi
- **Smart Assistant:** Alexa

## 📂 Repository Structure
```
├── main.ino    # Core logic handling Alexa commands & appliance control
├── README.md   # Project documentation
```

## ⚙️ Installation & Setup
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/17devraj/Home-automation-using-alexa_IOT.git
   ```

2. **Flash Code to ESP32:**
   - Install **Arduino IDE** or **PlatformIO**.
   - Add ESP32 board support.
   - Upload `main.ino` to ESP32.

3. **Connect to Alexa:**
   - Use an Alexa-compatible IoT service (e.g., Sinric Pro, AWS IoT, or Blynk).
   - Link your ESP32 with the Alexa skill.

4. **Test the System:**
   - Say commands like _"Alexa, turn on the light"_ to control connected devices.

## 📸 Screenshots
| **ESP32 Setup** | **Alexa Voice Control** |
|:---------------:|:----------------------:|
| ![ESP32](Images/setup.png) | ![Alexa](assets/images/alexa_command.png) |

## 🔮 Future Improvements
- Add support for **temperature and humidity sensors**.
- Implement **energy monitoring** for appliances.
- Extend compatibility to **Google Assistant**.

## 👨‍💻 Author
**Devraj Parmar** | [LinkedIn](https://linkedin.com/in/devraj-parmar)

