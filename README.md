<div align="center">
  <img src="portada.png" alt="Portada" width="800"/>
</div>

# Credits

This project, **BPSR Meter**, is a modified and customized version of the original work by 

*   **dmlgzs**: [StarResonanceDamageCounter](https://github.com/dmlgzs/StarResonanceDamageCounter).
*   **MrSnakke** - [MrSnakke BPSR-Meter](https://github.com/mrsnakke/BPSR-Meter)

We greatly appreciate their contribution to the community.  
You can find more details about the authors and contributors in [AUTHORS.md](AUTHORS.md).

---
---

# BPSR Meter

BPSR Meter is a desktop application that functions as a real-time **DPS (Damage Per Second)** meter for the game.  
It overlays the game window to provide detailed combat statistics without interrupting gameplay.

![DPS Meter in action](medidor.png)

## Features

1.  **Player Name:** Your in-game identifier shown on the meter.  
2.  **Current and Max Health:** A visual health bar.  
3.  **DPS (Damage Per Second):** Damage dealt per second.  
4.  **HPS (Healing Per Second):** Healing done per second.  
5.  **DT (Damage Taken):** Total damage received during combat.  
6.  **Contribution %:** Your share of the total party damage.  
7.  **CRIT ✸:** Critical hit percentage.  
8.  **LUCK ☘:** Lucky hit percentage.  
9.  **MAX ⚔ (Max DPS):** Your highest recorded DPS peak.  
10. **GS (Gear Score):** A score reflecting your equipment and skill power.  
11. **🔥 (Total Damage):** Total accumulated damage in the encounter.  
12. **⛨ (Total Healing):** Total accumulated healing in the encounter.

---

> ### Responsible Use  
> This tool is designed to help you improve your own performance.  
> **Please do not use it to insult, harass, or discriminate against other players.**  
> The goal is personal improvement and shared enjoyment of the game.

---

## Installation

1. **Install Npcap:**  
   The app requires Npcap to capture the game’s network traffic.  
   If you don’t have it installed, go to the “Releases” section of this GitHub repository and download the latest installer (`npcap-1.83.exe`).  

2. **Download the Installer:**  
   Go to the “Releases” section of this GitHub repository and download the latest version of the installer (`BPSR Meter Setup X.X.X.exe`).  

3. **Run the Installer:**  
   Execute the downloaded `.exe` file and follow the on-screen instructions to install the application on your computer.

---

## Usage Instructions

### Video Tutorial  
For a visual guide on how to install and configure the meter, check out this video:

[![YouTube Tutorial Video](PORTADA2.jpg)](https://youtu.be/QvGLjNvhKsw)

---

## How to Use

Once installed, you can start the application from the Start Menu or desktop shortcut.

The app opens as an overlay window. When you start the game, it will automatically detect traffic and display combat statistics in real time.

### Controls

| ![DPS Image](Advanced.png) | ![DPS Image](DPS.png) | ![Healer Image](Lite.png) |
| :---: | :---: | :---: |

- **Drag:** Click and drag the arrow indicator to move the window.  
- **Lock/Unlock:** Click the padlock button to lock or unlock the window’s position. When locked, it ignores mouse clicks.  
- **Zoom:** Use the `+` and `-` buttons to resize the interface.  
- **Close:** Click the `X` button to close the application.

---

## Troubleshooting

If the application isn’t working properly, check the `iniciar_log.txt` file located in the app’s data directory.  
You can find this directory by searching `%APPDATA%/bpsr-meter` on Windows.  
You can send any errors to me via Discord or get in touch directly, and I’ll do my best to resolve them.

---

## Frequently Asked Questions (FAQ)

**Is using this meter bannable?**  
> It operates in a “gray area.” It doesn’t modify game files, inject code, or alter memory. Historically, tools that only read data have an extremely low ban risk. However, **use it at your own risk.**

**Does it affect my game’s performance (FPS)?**  
> No. The impact is virtually zero, as packet capturing is passive and very lightweight.

**Why does it need administrator privileges?**  
> So that the Npcap library can access network adapters at a low level and monitor the game’s packets.

**The meter isn’t showing any data — what should I do?**  
> 1. Make sure the game is running **before** launching the meter.  
> 2. Confirm you are running the meter **as administrator**.  
> 3. Check that your firewall or antivirus isn’t blocking it.  
> 4. If you have multiple network connections (Ethernet, Wi-Fi, VPN), the meter might be listening to the wrong one.

**Can the meter be hidden?**  
> Yes. You can hide it by clicking its icon on the taskbar.

**Can I hide more data?**  
> Yes. The “Advanced” and “Lite” buttons allow switching between detailed and simplified modes.

**Does it work with other games?**  
> No. It’s specifically designed to decode the network packets for this game.

**Does it work on the Chinese server?**  
> Yes, it works correctly on the Chinese server.

**Is there a version for healers?**  
> Yes. In “Lite” mode, a side button lets you switch between DPS and Healer modes.  
> You can now optimize your rotations and view your healing per second (HPS) and total contribution.

---

## Social Media
[![Twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://www.twitch.tv/avoel)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@avoel)

---


