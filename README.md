# HP-ZBook-G1-OpenCore
A repository for OpenCore boot-loader for HP ZBook 15 G1.
This repository will be updated weekly!

- 🥲 Current OpenCore bootloader version: 0.7.0 ( Jun 8th 2021)

### New updates:
<ul>
    <li>Added support for macOS 12 Monterey Beta (Currently tested working on Beta 1).</li>
    <li>Replaced AppleALC.kext with VoodooHDA.kext for external microphone working and so on.</li>
    <li>Tweaked some OC configuration to make macOS working smoothly.</li>
    <li>Kexts are up-to-date by hand-compiled kexts on Acidanthera repositories.</li>
</ul>


### Reminder for those who are going to install macOS 12 Beta!!


- Please consider disabling these following kexts due to (currently not) support. Waiting for developer to fix it.

+ BrcmBluetoothInjector.kext
+ BrcmPatchRAM3.kext
+ BrcmFirmwareData.kext


---------------
## 💻 Hardware


- Laptop: HP ZBook 15 G1


- CPU: Intel Core i7 4900MQ 3.8GHz


- GPU: Intel HD 4600 Mobile


- Wi-Fi Card: Broadcom BCM94352HMB


- Removeable GPU: nVIDIA Quardo K1100M (Not working on macOS so I disabled it for power saving)



---------------
## 🛠 Features:

- Fully supported for all channels for the Wi-Fi. ❄️

- Fully DSDT patching which means it will be supported for most of the HP ZBook G1 laptops specs so you don't have to worry about changing your BIOS settings. 🔌

- Fully accelerated graphics video for Intel HD 4600 which is replaced by the name "Intel Iris Pro Graphics" and has 4096MB Video RAM for doing heavy task. 🕹

- Fully supported for sleep and hibernate mode 3-25. 💤

- Fully supported for macOS 10.10 to 10.16 out-of-the-box. 📈

- Fully supported for Intel Virtualization which means you can run Virtual Machines with ease, tested on Parallels Desktop, VMWare Fusion, Docker, Android Studio, Xcode Simulator. 📡


### Wi-Fi and Bluetooth are fully supported for macOS 10.14 -> 10.16 (with Broadcom BCM943xxx)


- Fan control is working perfectly. 🦄

- Support for multi-gesture touchpad such as 2,3,4-fingers. 👋

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
