# Web Shell Detection

A hands-on cybersecurity investigation focused on detecting and analyzing potential web shell activity on a WordPress web server.

The project demonstrates practical techniques for investigating suspicious web activity using **Apache access logs, Wireshark, HTTP analysis, TCP stream analysis, and log filtering** in a controlled lab environment.

---

## 🎯 Project Objectives

The main objectives of this investigation were to:

* Analyze web server access logs.
* Identify suspicious HTTP requests.
* Investigate HTTP response codes.
* Analyze HTTP POST activity.
* Inspect HTTP network traffic using Wireshark.
* Analyze individual TCP streams.
* Investigate potential indicators of web shell activity.
* Practice a structured investigation workflow using multiple sources of evidence.

---

## 🧪 Lab Environment

* **Target:** WordPress Web Server
* **Web Server:** Apache
* **Log Source:** Apache Access Logs
* **Network Analysis:** Wireshark
* **Data Analysis:** CyberChef
* **Environment:** Controlled cybersecurity lab
* **Platform:** TryHackMe

---

## 🔎 Investigation Methodology

The investigation was divided into three main phases:

### 1. Log-Based Detection

Apache web server logs were reviewed to identify suspicious web activity.

The analysis included:

* Reviewing `access.log`
* Inspecting HTTP requests
* Identifying suspicious activity
* Analyzing encoded content using CyberChef

📁 **[Log-Based Detection](./Log-Based-Detection/)**

---

### 2. Network Traffic Analysis

Wireshark was used to investigate network traffic associated with the web activity.

The analysis included:

* HTTP traffic filtering
* TCP stream analysis
* Individual TCP session inspection
* HTTP response code analysis
* Investigation of HTTP `302` responses

📁 **[Network Traffic Analysis](./Network-Traffic-Analysis/)**

---

### 3. Investigation

Apache access logs were further investigated using filtering techniques.

The investigation focused on:

* HTTP `404` responses
* HTTP `200` responses
* HTTP `POST` requests
* Reviewing request patterns
* Identifying activity requiring further investigation

📁 **[Investigation](./Investigation/)**

---

## 🛠️ Tools Used

| Tool               | Purpose                                  |
| ------------------ | ---------------------------------------- |
| Apache Access Logs | Web activity investigation               |
| Linux CLI          | Log filtering and analysis               |
| Wireshark          | Network traffic analysis                 |
| CyberChef          | Encoded data analysis                    |
| TryHackMe          | Controlled cybersecurity lab environment |

---

## 📊 Evidence

The project contains screenshots documenting the investigation process, including:

* Apache access log analysis
* HTTP request analysis
* HTTP response analysis
* TCP stream inspection
* HTTP POST request investigation
* Encoded data analysis with CyberChef

All evidence included in this repository was collected during the lab investigation.

---

## 🧠 Key Takeaways

This project demonstrates how a SOC analyst can combine different sources of evidence when investigating suspected web shell activity.

Important lessons from the investigation include:

* Web server logs can provide valuable indicators of suspicious activity.
* HTTP response codes can help identify unusual request patterns.
* POST requests deserve additional attention during web application investigations.
* Network traffic analysis can provide additional context that may not be visible in application logs.
* TCP stream analysis helps reconstruct individual network conversations.
* Combining log analysis with network analysis provides stronger investigative visibility.

---

## ⚠️ Disclaimer

This project was conducted in a **controlled cybersecurity lab environment** for educational and defensive security purposes.

The techniques demonstrated here should only be used on systems and networks where you have explicit authorization to perform security testing and investigation.

---

## 👤 Author

**Anas Habib**

Cybersecurity | SOC | Blue Team

GitHub: [Anas Habib](https://github.com/anshabib80-source)
