# HP-ZBook-G1-OpenCore
A repository for OpenCore boot-loader for HP ZBook G1.
This repository will be updated weekly!

---------------
## 💻 Hardware


- Laptop: HP ZBook 15 G1


- CPU: Intel Core i7 4900MQ 3.8GHz


- GPU: Intel HD 4600 Mobile


- Removeable GPU: nVIDIA Quardo K1100M (Not working on macOS so I disabled it for power saving)



---------------
## 🛠 Features:

- Fully supported for all channels for the Wi-Fi. ❄️

- Fully DSDT patching which means it will be supported for most of the HP ZBook G1 laptops specs so you don't have to worry about changing your BIOS settings. 🔌

- Fully accelerated graphics video for Intel HD 4600 which is replaced by the name "Intel Iris Pro Graphics" and has 4096MB Video RAM for doing heavy task. 🕹

- Fully supported for sleep and hibernate mode 3-25. 💤

- Fully supported for macOS 10.10 to 10.15 out-of-the-box. 📈

- Fully supported for Intel Virtualization which means you can run Virtual Machines with ease, tested on Parallels Desktop, VMWare Fusion, Docker, Android Studio, Xcode Simulator. 📡


### You will need to change some kexts or I will update it soon for macOS 10.16. If you are insisting of install macOS 10.16 soon, you can install it normally but the Wi-Fi functionality will not be working either the bluetooth functionality.


- Fan control is working perfectly. 🦄

- Support for multi-gesture touchpad such as 2,3,4-fingers. 👋


### There is a small change that it will fail to load the touchpad kext so you will need to restart for sometimes to get it working. For me there is a 40% it will not be loading by booting up.


- USB Ports are fully patched and ready to be used. ⌨️

- Webcam is working normally. 📷


----------------
## ❌ Not working


- Internal SD Card Reader. 📬

- Display output (HDMI - DisplayPort) is not working due to the removeable GPU is not working. If you still insisting of remove that GPU and it still not works. 🖥

- There is a very small percentage that the in-board (speaker) audio will not be working so you will have to fake plug in a headphone jack then remove it and you will be able to listen to the speaker again. 🧭
----------------
### 💌 Credits

- Acidanthera for his awesome bootloader and kexts to make this works.
- Apple Inc.