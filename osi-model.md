# OSI Model

The OSI (Open Systems Interconnection) model is a conceptual framework used to understand how data is transmitted across a network. It is widely used in **networking and cybersecurity** to analyze how communication works and where attacks can occur.

---

## 📊 OSI Layers
1. Physical – Transmission of raw bits  
2. Data Link – Frame formation and MAC addressing  
3. Network – Logical addressing and routing (IP)  
4. Transport – End-to-end communication (TCP/UDP)  
5. Session – Session management  
6. Presentation – Data formatting and encryption  
7. Application – User interaction (HTTP, FTP, SMTP)  

---

## ⚠️ Common Attacks at Each OSI Layer

### 1️⃣ Physical Layer
**Attacks:**
- Cable tapping
- Hardware damage
- Power disruption
- Physical theft of devices

**Example:** Unplugging network cables or stealing a router.

---

### 2️⃣ Data Link Layer
**Attacks:**
- MAC spoofing
- ARP poisoning
- VLAN hopping

**Example:** Redirecting traffic by faking MAC or ARP responses.

---

### 3️⃣ Network Layer
**Attacks:**
- IP spoofing
- ICMP flooding
- Man-in-the-Middle (MITM)

**Example:** Sending packets with fake IP addresses to bypass filters.

---

### 4️⃣ Transport Layer
**Attacks:**
- TCP SYN flood
- UDP flood
- Session hijacking

**Example:** Overwhelming a server with half-open TCP connections.

---

### 5️⃣ Session Layer
**Attacks:**
- Session hijacking
- Session fixation

**Example:** Stealing a session ID to take over a logged-in user session.

---

### 6️⃣ Presentation Layer
**Attacks:**
- SSL/TLS downgrade attacks
- Data manipulation
- Encryption bypass

**Example:** Forcing a weaker encryption method to read data.

---

### 7️⃣ Application Layer
**Attacks:**
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Command Injection

**Example:** Injecting malicious input into web forms.

---

## 🔐 Relevance to Cybersecurity
- Helps identify **where different attacks occur**
- Useful for **network troubleshooting and defense planning**
- Essential for understanding **firewalls, IDS/IPS, and security monitoring**
- Provides a structured approach to analyzing security threats

---

## 📘 Learning Note
This file is part of my **networking fundamentals** learning, created to strengthen my foundation for **cybersecurity and ethical hacking**.
