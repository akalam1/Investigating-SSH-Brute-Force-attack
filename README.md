# Lab: Investigating SSH Brute-Force Attack

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)  
[![Made with Splunk](https://img.shields.io/badge/Made%20with-Splunk-orange)](https://www.splunk.com/)

---

## 🧠 Overview
This lab demonstrates how to investigate an SSH brute-force attack using Splunk on an Ubuntu server.  
You will learn how to extract user and source IP information from authentication logs and answer these investigation tasks.

---

## 🎯 Tasks (what you must find)
1. **Which user attempted the most brute-force attacks?**  
2. **What is the IP address of that attacker?**  
3. **How many failed login attempts did that user have?**

---

## ⚙️ Platform / Tools Used
Platform: Ubuntu Server (lab VM)
SIEM: Splunk Enterprise / Splunk Search Head
Data Source: /var/log/auth.log (Ubuntu) ingested into Splunk (index=ubuntu_auth)
Language: SPL (Splunk Processing Language)





