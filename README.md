
# OSI Model and Common Cyber Attacks

***Mehmood Ali*** 
``` (Mr.Professor) ```


The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and implement network communication protocols in seven distinct layers. Each layer has specific functions, and different types of cyber attacks can target each one. Here’s a brief overview of the OSI layers and some common attacks associated with them:

## 1. Physical Layer (Layer 1)
- **Function:** Responsible for the physical connection between devices, including cables, switches, and other hardware.
- **Common Attacks:**
  - **Physical Tampering:** Physically damaging or tampering with network devices.
  - **Wiretapping:** Intercepting data by physically accessing network cables.

## 2. Data Link Layer (Layer 2)
- **Function:** Manages node-to-node data transfer and handles error detection and correction from the physical layer.
- **Common Attacks:**
  - **MAC Spoofing:** An attacker changes their MAC address to impersonate another device on the network.
  - **ARP Spoofing:** An attacker sends fake ARP (Address Resolution Protocol) messages to link their MAC address with the IP address of a legitimate device.

## 3. Network Layer (Layer 3)
- **Function:** Handles routing and forwarding of data packets between devices on different networks.
- **Common Attacks:**
  - **IP Spoofing:** An attacker alters the source IP address in a packet to make it appear as though it came from a different source.
  - **DDoS (Distributed Denial of Service):** Overloading a network by flooding it with massive amounts of traffic, often targeting routers.

## 4. Transport Layer (Layer 4)
- **Function:** Ensures complete data transfer and manages end-to-end communication and error recovery.
- **Common Attacks:**
  - **TCP SYN Flood:** An attacker overwhelms a server by sending a series of TCP SYN requests without completing the handshake, leading to resource exhaustion.
  - **Session Hijacking:** An attacker takes control of a session between two devices by intercepting or predicting session tokens.

## 5. Session Layer (Layer 5)
- **Function:** Manages and controls the connections between devices, ensuring sessions are established, maintained, and terminated appropriately.
- **Common Attacks:**
  - **Session Hijacking:** An attacker gains unauthorized access to a session between two devices, often by stealing session cookies or tokens.
  - **Session Fixation:** An attacker forces a user's session ID, making it easier to hijack the session.

## 6. Presentation Layer (Layer 6)
- **Function:** Translates data between the application layer and the network, handling data encryption, compression, and translation.
- **Common Attacks:**
  - **Man-in-the-Middle (MitM):** An attacker intercepts and potentially alters communication between two parties, often targeting data as it is being translated or encrypted.
  - **SSL Stripping:** Downgrading a secure HTTPS connection to an unencrypted HTTP connection.

## 7. Application Layer (Layer 7)
- **Function:** Provides network services directly to the end-users and interfaces with software applications.
- **Common Attacks:**
  - **Phishing:** Deceptive emails or websites designed to trick users into providing sensitive information.
  - **SQL Injection:** An attacker inserts malicious SQL code into a web form to manipulate the database.
  - **Cross-Site Scripting (XSS):** Injecting malicious scripts into web pages viewed by other users.

## Conclusion
Understanding the OSI model and the potential attacks at each layer is essential for developing comprehensive security measures that protect the entire network stack.
