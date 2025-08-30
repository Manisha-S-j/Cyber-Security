# Port Numbers

## What are Port Numbers?
- Port numbers are **logical endpoints** used to distinguish different types of network services on a single device.
- While an IP address identifies a device on the network, **a port identifies a specific application or process** running on that device.
- Port numbers range from **0 to 65,535**.

---

## Categories of Ports
1. **Well-known Ports (0–1023)**
   - Reserved for common protocols and services.
   - Example: 
     - **HTTP → Port 80**
     - **HTTPS → Port 443**
     - **FTP → Port 21**
     - **DNS → Port 53**

2. **Registered Ports (1024–49,151)**
   - Assigned by IANA for specific applications.
   - Example: 
     - MySQL → 3306  
     - PostgreSQL → 5432

3. **Dynamic / Private Ports (49,152–65,535)**
   - Used by applications dynamically for communication.
   - Example: Browsers often use these for outgoing connections.

---

## Real-world Analogy
- Imagine a **house (IP address)**:
  - The house address = Device (IP Address)
  - Different rooms = Different services
  - **Ports = Door numbers** leading to each room
  - Example: If you want to access the kitchen, you use the "kitchen door" → like accessing HTTP service on port 80.

---

## Common Port Numbers
- **20/21 → FTP (File Transfer Protocol)**
- **22 → SSH (Secure Shell)**
- **25 → SMTP (Simple Mail Transfer Protocol)**
- **53 → DNS (Domain Name System)**
- **80 → HTTP**
- **110 → POP3**
- **143 → IMAP**
- **443 → HTTPS**
- **3306 → MySQL**

---

## Key Takeaways
- IP address → Identifies device  
- Port number → Identifies service/application  
- Combination of IP + Port = **Socket**  
- Without port numbers, computers wouldn’t know *which service* to send data to.

---

[⬅️ Previous](04_IP_Address.md) | [Next ➡️](06_Submarine_Cables.md)
