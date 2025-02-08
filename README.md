# Wireless Network Design

## Overview
This project involves designing a **wireless network** based on real-world scenarios, applying **802.11 standards, Wi-Fi 6, and mesh networking technologies** to ensure optimal performance, security, and scalability.

## Objectives
- Design a **wireless network layout** with clear architecture.
- Select appropriate **802.11 standards** (Wi-Fi 5, Wi-Fi 6) for optimal performance.
- Ensure **network security** using WPA3, VLANs, and firewall configurations.
- Optimize **coverage and capacity** for seamless device connectivity.
- Plan for **future scalability** and expansion.

## Network Design Breakdown
### **Scenario: Smart Home Wireless Network**
- Implements **Wi-Fi 5 (802.11ac)** for high-speed data transfer.
- Supports **multiple IoT devices** (smart lights, door locks, appliances).
- Utilizes **beamforming** and **Quality of Service (QoS)** for bandwidth optimization.

### **Network Architecture**
- **Core Layer**: 5506-X ASA Firewall for security.
- **Distribution Layer**: 2950-24 MSW switch for efficient traffic handling.
- **Access Layer**: WRT300N Wireless Router managing IoT and user devices.

### **802.11 Standards**
- **Wi-Fi 5 (802.11ac)** is chosen for **faster speeds** and **less congestion** on the **5GHz band**.
- Supports **high bandwidth demand** for smart home automation.
- Provides enhanced coverage with **beamforming technology**.

### **Coverage & Capacity Optimization**
- **Beamforming** to direct signals toward connected devices.
- **Device segmentation** using VLANs to separate IoT traffic.
- **Wi-Fi extenders or mesh networking** for larger coverage areas.

### **Security Implementation**
- **WPA3 encryption** for all wireless networks.
- **MAC filtering** to allow only authorized devices.
- **Firewall and VLAN segmentation** for isolating IoT devices from critical systems.
- **Regular firmware updates & strong passwords** to prevent vulnerabilities.

### **Scalability Considerations**
- **Additional access points (APs)** can be added for **better coverage**.
- **Switches with spare ports** allow wired expansion.
- **Mesh networking support** for future-proofing the system.

---

## Author
This project was created by the repository owner.
