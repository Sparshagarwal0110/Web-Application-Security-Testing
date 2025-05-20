
# 🔐 Wi-Fi Security Assessment Report

**Cyber Security Internship – Task 3**

## 📝 Objective
Conduct a Wi-Fi security assessment on my home network, identifying vulnerabilities such as weak passwords, open ports, and unauthorized devices.

---

## 🧰 Tools Used
- **Wireshark** – Network traffic capture and analysis
- **Aircrack-ng** – Wi-Fi password testing
- **Nmap** – Port scanning and device discovery

---

## 🔍 Assessment Summary

### 1. **Wi-Fi Password Security**
- **Encryption Type:** WPA2-Personal (AES)
- **Password Strength:** Medium (dictionary attack vulnerable)
- **SSID:** Broadcasted and easily identifiable

**🛡️ Recommendations:**
- Use a strong, complex passphrase (15+ chars)
- Hide or rename SSID
- Upgrade to WPA3 (if supported)

---

### 2. **Port Scanning (Nmap)**
- **Open Ports Identified:** 80, 443, 1900, 2872, 5068, 8443, 7443
- **Insecure Services Detected:** TELNET, HTTP, UPNP, SIP
- **Issues:** Expired or mismatched SSL certificates

**🛡️ Recommendations:**
- Disable TELNET and unused ports
- Restrict HTTP access or force HTTPS
- Regularly update router firmware

---

### 3. **Unauthorized Device Detection**
- **Unknown Device Found:** 1 unrecognized MAC address
- **Known Devices:** 6 (laptops, phones, TV)

**🛡️ Recommendations:**
- Change Wi-Fi password
- Enable MAC address filtering
- Disable WPS

---

### 4. **Packet Analysis (Wireshark)**
- **Findings:** Unencrypted HTTP and DNS traffic
- **Captured ICMP and IGMPv3 packets**

**🛡️ Recommendations:**
- Use encrypted DNS (DoH/DoT)
- Monitor unusual traffic regularly

---

## 🖼️ Screenshots
Screenshots include:
- Nmap scan results
- Wireshark packet capture
- Router settings and device logs

(Refer to the `/screenshots` folder in this repo)

---

## ✅ Conclusion
The assessment revealed moderate risk factors that can be mitigated through stronger authentication, port restrictions, and encrypted communication. Proactive network hygiene helps defend against common home-network threats.

---

## 📁 Files Included
- [`Task3_Report.pdf`](./Task3_Report.pdf) – Final report

---

## 📌 Tags
`#CyberSecurity` `#WiFiAssessment` `#Nmap` `#Wireshark` `#AircrackNG` `#InternshipTask`
