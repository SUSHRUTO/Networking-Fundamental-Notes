# 🌐 Networking Fundamentals for Web Developers

This repository contains my structured notes and diagrams on core Internet and Networking concepts that every Web Developer should understand before building applications.

These concepts were covered as part of Web Dev Cohort 2026 – Peer Spotlight submission.

---

## 📚 Topics Covered

- 🌍 What is the Internet?
- 🖥 Client–Server Architecture
- 📍 IP Address & Ports
- 🌐 DNS (Domain Name System)
- 🔐 HTTP vs HTTPS
- 🔄 TCP vs UDP
- 🚀 Complete Request–Response Flow

---

## 🌍 What is the Internet?

The Internet is a global network of interconnected networks that communicate using standardized protocols. Data travels in packets across routers and switches to reach its destination.

---

## 🖥 Client–Server Model

- Client: Browser or user device
- Server: Machine that stores and serves resources
- Communication happens via request and response

Example:
When we type `google.com`, the browser sends a request to Google's server and receives an HTML response.

---

## 📍 IP Address & Ports

### IP Address
A unique address assigned to each device on a network.
Example: `192.168.1.1`

### Ports
Logical endpoints that allow multiple services to run on the same IP.

Common Ports:
- 80 → HTTP
- 443 → HTTPS
- 3000 → Development server
- 22 → SSH

---

## 🌐 DNS (Domain Name System)

DNS translates domain names into IP addresses.

Flow:
1. User enters domain name
2. DNS resolves it into IP address
3. Browser connects to server using that IP

DNS acts like the phonebook of the Internet.

---

## 🔐 HTTP vs HTTPS

### HTTP
- HyperText Transfer Protocol
- Not encrypted
- Uses Port 80

### HTTPS
- Secure version of HTTP
- Uses SSL/TLS encryption
- Uses Port 443
- Protects data during transmission

---

## 🔄 TCP vs UDP

### TCP
- Reliable
- Ordered
- Connection-based
- Used in web browsing and banking

### UDP
- Faster
- No delivery guarantee
- Used in streaming and gaming

---

## 🚀 Complete Website Request Flow

1. User enters domain name
2. DNS resolves domain to IP
3. TCP handshake establishes connection
4. HTTPS request is sent
5. Server responds with HTML
6. Browser renders webpage

---

## 🎯 Why These Concepts Matter

Understanding networking fundamentals helps in:
- Debugging backend issues
- Understanding deployment
- Optimizing performance
- Securing applications
- Becoming a better full-stack developer

---

📌 Created as part of Peer Teaching Submission  
👨‍💻 Author: Sushruto Majumdar  
