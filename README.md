# Understanding-and-maintenance-of-Networks-2
# Q1.Draw a labelled diagram of a typical home WiFi router and a network switch, clearly marking at least 3 different ports (such as WAN, LAN, Console) and the location of status LEDs.
Ans.>![WhatsApp Image](WhatsApp%20Image%202026-10-28%20at%2010.54.16%20AM.jpeg)
# Q2.List 3 key differences between routers and switches in terms of their main functions and how they handle network traffic.<br><br><em><strong>Hint:</strong> Think about how each device deals with IP addresses, MAC addresses, and the types of networks they connect.</em>
Ans.>
## 3 Key Differences Between Routers and Switches

| No. | Router | Switch |
|---|---|---|
| 1. Main Function | Connects different networks, such as a home network to the internet. | Connects multiple devices within the same Local Area Network (LAN). |
| 2. Addresses Used | Uses IP addresses to determine where network packets should be forwarded. | Uses MAC addresses to forward Ethernet frames to the correct device. |
| 3. Network Traffic | Routes data between different networks using a routing table. | Forwards data within a local network using a MAC address table. |

### Conclusion
A router connects different networks and forwards packets using IP addresses, whereas a switch connects devices within a LAN and forwards frames using MAC addresses.
# Q3.Take a real or virtual image of a router and a switch (from your home, lab, or Google Images), and identify the following on each: Power port, at least 2 Ethernet ports, and any LED indicators. Annotate the image or describe their position and purpose.
Ans.>
## Identification of Router and Network Switch

### 1. Router

**Image:** Use a picture of a typical home Wi-Fi router showing its rear ports and front LED indicators.

- **Power Port:** Located on the back of the router. It connects the router to its power adapter.
- **Ethernet Port 1 (WAN):** Usually located on the back and marked WAN or Internet. It connects the router to a modem or internet connection.
- **Ethernet Ports 2 and 3 (LAN):** Usually grouped together on the back and marked LAN. They connect computers, printers, and other wired devices.
- **LED Indicators:** Usually located on the front or top. They indicate power status, internet connectivity, Wi-Fi activity, and LAN connections.

### 2. Network Switch

**Image:** Use a picture of a typical Ethernet network switch showing its power connection and multiple Ethernet ports.

- **Power Port:** Usually located on the back or side. It supplies electrical power to the switch.
- **Ethernet Port 1:** Located on the front or rear panel. It connects a computer or another network device.
- **Ethernet Port 2:** Located beside the other Ethernet ports. It connects another computer, printer, or network device.
- **LED Indicators:** Usually located above or beside each Ethernet port. They show power status and network link or data activity.

### Conclusion

A router connects different networks and commonly provides internet access and Wi-Fi. A switch connects multiple wired devices within a local area network. Power ports supply electricity, Ethernet ports carry network traffic, and LED indicators display device and connection status.
# Q4.Imagine you are setting up a small gaming café network for IPL streaming and multiplayer matches. Write a short scenario explaining which device (router or switch) you would connect first to the ISP line, and how you would connect 8 gaming PCs to the network. Justify your choices.
Ans.>
## Scenario: Setting Up a Gaming Café Network

### Network Setup

Imagine I am setting up a small gaming café with 8 gaming PCs for IPL streaming and multiplayer gaming.

First, I would connect the ISP (Internet Service Provider) line to the modem or ONT, and then connect it to the **WAN port of the router**. The router provides internet access and manages traffic between the café's local network and the internet.

Next, I would connect one of the router's LAN ports to an **Ethernet network switch**. Then, I would connect all 8 gaming PCs to the switch using Ethernet cables.

### Network Diagram

ISP Line → Modem/ONT → Router → Network Switch → 8 Gaming PCs

### Justification

1. **Router:** Connects the café's network to the internet and routes data between the local network and external networks.
2. **Network Switch:** Provides enough Ethernet ports to connect all 8 gaming PCs, even if the router has only a few LAN ports.
3. **Ethernet Cables:** Provide stable, low-latency connections that are suitable for multiplayer gaming and reliable IPL streaming.
4. **Performance:** A Gigabit Ethernet switch and a suitable internet plan help support multiple gaming sessions and video streams simultaneously.

### Conclusion

I would connect the router to the ISP connection first, followed by a network switch, and then connect all 8 gaming PCs to the switch. This setup provides reliable internet access and efficient communication between the gaming PCs.
