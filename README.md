# Analyzing Wireless Access Points

## 🎯 Objective
In this project, I explored wireless network security by identifying rogue access points (APs) using tools like `netsh` and `InSSIDer`. Understanding the significance of rogue APs, assessing potential security risks, and evaluating the limitations of these tools in a practical setting.

## 🛠️ Tools Used
- **Netsh**: Command-line utility for managing network configurations on Windows.
- **InSSIDer**: Wireless network scanner providing a graphical representation of nearby networks.

## 🧠 Skills Learned
- Understood wireless network security and the role of rogue APs.
- Used command-line tools to gather detailed network information.
- Employed graphical tools for network analysis.
- Identified security threats posed by rogue APs.
- Recognized tool limitations in detecting and locating rogue APs.

## 📝 Steps
<div align="center">
  <img src="https://imgur.com/4ELX8hj.png" alt="Wireless Network Analysis">
  <p><em>Figure 1: Wireless Network Analysis using Netsh</em></p>
</div>

![Wireless Network Analysis](https://imgur.com/BwNluOQ.png)
<p align="center"><em>Figure 1.1: Possible Rogue Access Points</em></p>

![Image 2](https://imgur.com/gn4W0MR.png)
<p align="center"><em>Figure 2: Analyzing Wireless Environment using inSSIDER</em></p>

![Image 3](https://imgur.com/7q6jh8a.png)
<p align="center"><em>Figure 2.1: Possible Rogue Access Points</em></p>

![Image 4](https://imgur.com/GqgclNK.png)
<p align="center"><em>Figure 2.2: Locating Rogue APs</em></p>


### 1. Preparation
- Installed **InSSIDer** on my computer.
- Used Command Prompt or PowerShell with administrative rights to use `netsh`.
- Reviewed fundamental `netsh` commands for exploring wireless networks.
- Understood the project objectives.

### 2. Observation
- Compared the usability and data detail between `netsh` and InSSIDer.
- Recognized the importance of signal strength in identifying rogue APs using InSSIDer.

### 3. Using Netsh
#### Exploring the Wireless Environment
Execute the following command to display active wireless networks with their details:

```sh
netsh wlan show networks mode=bssid


