

# Open Radio

**Open Radio** is a community-driven project to build the ultimate Swiss Army knife for amateur radio, leveraging the built-in dual-band DMR radio module in the ComJot CJ-1UV Android 14 device. My mission is to provide a fully-featured, cost-free alternative to subscription-based radio control apps, I welcome any and all help since I am not only barely a developer, but I know basically nothing of Android development when Im starting this project. Cheers

Learn more about the device: https://tait-radio.com/comjot-cj-1/

## 🚀 Features

- **Channel Management**  
  - Configure DMR digital and FM analog channels  
  - Manage talkgroups, color codes, CTCSS/DCS tones, and squelch settings

- **Push-To-Talk (PTT) Control**  
  - Hardware PTT support  
  - Software PTT commands with customizable on/off sequences

- **Event Monitoring**  
  - Real-time RX/TX status events  
  - Unsolicited event parsing (e.g., channel busy, SMS notifications)

- **Short Message Service (SMS)**  
  - Send and receive DMR SDS messages  
  - UTF-16LE encoding support

- **Analog DTMF Dialing**  
  - On-air DTMF digit transmission  
  - Customizable tone duration and inter-digit gap

- **Audio & Gain Settings**  
  - Adjust microphone gain and speaker volume  
  - Power-save and repeater decoupling mode

- **Cross-Platform Compatibility**  
  - Android USB-host support  
  - Open-source Kotlin/Java codebase

## 🛠 Getting Started

### Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/DylanManiatakes/OpenRadio.git
   cd OpenRadio
   ```

2. Import into Android Studio:  
   - File → New → Import Project… → select the cloned folder.  

3. Build & Run:  
   - Connect your Android device via USB-OTG  
   - Ensure USB permission dialog is accepted  
   - Run the `app` module on your device  

## 📚 Documentation

- **RF Cheat Sheet**: Detailed serial protocol reference → [`RF_Cheat Sheet.MD`](RF_Cheat%20Sheet.MD)  
- **API Docs**: Inline documentation in `/app/src/main/java`  

## 🏗 Contributing

Open Radio thrives on community contributions! Whether you’re fixing bugs, adding new features, or improving docs, I welcome your help becuase honestly I have no idea what im doing.:

1. Fork the repo  
2. Create a feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m "Add awesome feature"`)  
4. Push to your fork (`git push origin feature/YourFeature`)  
5. Open a Pull Request   

## 📄 License

This project is licensed under the [MIT License](LICENSE).