# Networking & Cloud Fundamentals

## 1. Historical Timeline
- **1960s–70s**: **ARPANET** – early packet-switching network, precursor to the internet.  
- **1980s–90s**:  
  - **DNS (Domain Name System)** introduced.  
  - **WWW (World Wide Web)** emerges – collection of resources accessed via network protocols.  
  - Companies like **AOL, Yahoo, Google** shape the early internet era.  
- **2000s**: Rise of cloud service providers – **AWS, GCP (Google Cloud Platform), Azure**.

---

## 2. Key Concepts & Services
- **DNS (Domain Name System)**: Maps domain names to IP addresses.  
- **WWW (World Wide Web)**: Collection of resources accessible through network protocols.  
- **Cloud Computing**: Renting services (servers, storage, infrastructure) from providers instead of maintaining in-house infrastructure.  
  - Shared space in the cloud → security risks.  
  - Many companies move sensitive data **back on-premise**.  
  - **Hybrid model**: Cloud for some apps, on-premise for critical data.  
- **Infrastructure (Data Center Components)**:  
  - Servers  
  - Switches  
  - Storage  

---

## 3. Networking Basics
- **Protocols** = Standard communication languages between systems.  
- **Ethernet** = Protocol for wired networking.  

### Network Types
- **LAN (Local Area Network)**: Small scale (e.g., one office).  
- **MAN (Metropolitan Area Network)**: Connects multiple buildings across a city.  
- **WAN (Wide Area Network)**: Global connectivity beyond premises.  

### Topologies (physical & logical layout)
- **Point-to-Point**: Direct connection between two devices.  
- **Ring**: Devices connected in a loop.  
- **Star**: All devices connect to a central switch (isolates failures).  
- **Mesh**: Multiple interconnections, reliable but expensive.  
- **Bus**: Shared backbone with terminators at each end.  
- **Tree**: Hierarchical layout.  

---

## 4. Intranet vs Extranet
- **Intranet**: Internal network for employees only.  
- **Extranet**: Controlled access for external partners or vendors.  

---

## 5. OSI vs TCP/IP Models

### OSI Model (7 Layers) – *theoretical, mainly for teaching*
1. **Physical** – electrical signals, cabling.  
2. **Data Link** – switches, framing, error detection.  
3. **Network** – addressing, routing (IP).  
4. **Transport** – QoS, reliability (TCP/UDP).  
5. **Session** – maintains sessions between apps.  
6. **Presentation** – encryption, data formatting.  
7. **Application** – user-facing apps (HTTP, email).  

> Mnemonic: **Please Do Not Tell Secret Passwords to Anyone**

### TCP/IP Model (4 Layers) – *practical, widely used today*
1. **Network Access**  
2. **Internet**  
3. **Transport**  
4. **Application**

---

## 6. Protocols

### TCP (Transmission Control Protocol)
- Connection-oriented.  
- Examples: **Telnet, SSH, HTTP**  

### UDP (User Datagram Protocol)
- Connectionless.  
- Examples: **DNS, SNMP, NTP**  

### Security & Devices
- **Transport Layer**: Port security, firewalls.  
- **Data Link Layer**: Switches.  

---

## 7. Encryption
Data can be encrypted at multiple layers:  
- **Presentation layer**: SSL/TLS (data formatting & encryption).  
- **Application layer**: HTTPS, encrypted apps.  
- **Transport layer**: Secure connections (TLS over TCP).  
- **Network layer**: VPNs, IPsec.  

---

## 8. Advanced Concepts
- **Quantum Computing**: Performs complex calculations in seconds that would take classical computers years.  










