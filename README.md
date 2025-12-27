# Small Office LAN

A Cisco Packet Tracer lab demonstrating a basic small office network setup with VLAN configuration, DHCP server, and port security implementation.

## 📋 Project Overview

This project simulates a small office Local Area Network (LAN) using Cisco Packet Tracer. The network includes a single VLAN configuration, DHCP for automatic IP addressing, and port security features to enhance network security.

## 🌐 Network Topology

![image2](image2)

*Network topology showing Router1 (2911) connected to Switch0 (2960) serving 6 end devices: 5 PCs and 1 Printer*

## 🔧 Network Components

- **Router**: Cisco 2911 (Router1)
- **Switch**: Cisco 2960 (Switch0)
- **End Devices**:
  - 5 x Desktop Computers (PC0, PC1, PC2, PC3, PC4, PC5)
  - 1 x Printer (Printer0)

## ✨ Features

- **Single VLAN Configuration**: All devices on the same VLAN for simplified management
- **DHCP Server**: Automated IP address assignment for all connected devices
- **Port Security**: Enhanced security measures to prevent unauthorized access
- **Router-on-a-Stick**: Inter-VLAN routing capability (if needed for future expansion)

## 📁 Project Files

- `Small_Office_LAN.pkt` - Cisco Packet Tracer project file

## 🚀 Getting Started

### Prerequisites

- Cisco Packet Tracer (version 7.0 or higher recommended)
- Basic understanding of networking concepts

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/vihangaNethsara/Small-office-LAN.git
   ```

2. Open Cisco Packet Tracer

3. Load the project file:
   - File → Open → Select `Small_Office_LAN.pkt`

## 🔒 Configuration Details

### Switch Configuration

The switch (Switch0) has been configured with password protection for security:

- **Console Password**: `console123`
- **Enable Secret**: `cisco123`
- **VTY Password**: `vty123`

### DHCP Configuration

The DHCP server automatically assigns IP addresses to all connected devices, eliminating the need for manual IP configuration.

### Port Security

Port security has been implemented to:
- Limit the number of MAC addresses per port
- Prevent MAC address spoofing
- Protect against unauthorized device connections

## 📚 Learning Objectives

This lab helps you understand:

- Basic LAN topology design
- VLAN configuration and management
- DHCP server setup and configuration
- Port security implementation
- Router and switch basic configuration
- Network device connectivity

## 🔍 Testing the Network

1. Open the Packet Tracer file
2. Check device IP configurations (should be assigned via DHCP)
3. Test connectivity using ping between devices
4. Verify port security settings on the switch
5. Test printer connectivity from any PC

## 🛠️ Troubleshooting

If devices cannot communicate:
- Verify all cables are properly connected (check for green triangles)
- Ensure DHCP is properly configured and running
- Check VLAN assignments on all ports
- Verify router interface is up and has the correct IP address

## 📝 Notes

- This is a basic lab setup suitable for learning fundamental networking concepts
- Passwords are configured for educational purposes
- The topology can be expanded to include additional VLANs, servers, or network segments

## 👤 Author

**Vihanga Nethsara**

- GitHub: [@vihangaNethsara](https://github.com/vihangaNethsara)

## 📄 License

This project is available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements or additional features!

---

*Created as part of networking lab exercises using Cisco Packet Tracer*