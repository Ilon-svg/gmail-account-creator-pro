# 📐 Technical Specifications & Benchmark Sheet
**Module:** Gmail & Automation Provisioning Engine  
**Architecture:** Asynchronous Multi-Threaded Worker Pool  

---

## 1. System Requirements & Compatibility
* **Supported OS:** Windows 10/11 (x64), Ubuntu 20.04/22.04 LTS, Debian 11+
* **Minimum Hardware:** 2 vCPU, 4 GB RAM, 100 Mbps Network Throughput
* **Recommended Hardware:** 8 vCPU, 16 GB RAM (for running 50+ concurrent threads)

## 2. Network & Proxy Architecture
* **Supported Protocols:** SOCKS4, SOCKS5, HTTP, HTTPS
* **IP Rotation Handling:** Webhook Trigger, Time-based, or Session-based
* **Fingerprint Randomization:** Canvas Noise Algorithm v4.2, WebGL Vendor Spoofing, AudioContext Frequency Jitter

## 3. Benchmark Metrics
| Metric | Standard Thread | High-Concurrency Thread |
| :--- | :--- | :--- |
| **Creation Rate** | 120-150 accounts/hr | 800+ accounts/hr |
| **PVA Success Rate** | ~92% (Quality Dependent) | ~90% |
| **Cookie Persistence** | High (Netscape Standard) | High |

