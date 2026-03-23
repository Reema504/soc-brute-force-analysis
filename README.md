# soc-brute-force-analysis

# SOC Case Study – Brute Force Attack Detection

## 📌 Project Overview
This project simulates a Security Operations Center (SOC) investigation of suspicious login activity.

*This project simulates a real SOC investigation workflow, including log analysis, threat detection, and incident reporting.*

## 🎯 Objective
Analyze login activity logs to identify potential brute-force attack attempts and suspicious behavior.

## 📂 Data Source
Sample authentication logs provided for analysis.

## 🔍 Scenario
Multiple failed login attempts were detected from different IP addresses within a short period.

## 🔍 Analysis
The log data shows multiple failed login attempts from the IP address 192.168.1.10.

A successful login occurred after several failed attempts, indicating a potential brute-force attack.

Another failed login attempt from 10.0.0.5 occurred only once and is considered less suspicious.

## 🚨 Findings
- 4 failed login attempts from 192.168.1.10
- 1 successful login from same IP
- Multiple usernames targeted
- Likely brute-force attack
- Potential account compromise

## 🧾 Conclusion
The investigation confirms a likely brute-force attack followed by successful access, indicating a potential compromise.

## 🛡️ Recommendations
- Enable Multi-Factor Authentication (MFA)
- Implement account lockout policies
- Monitor suspicious IPs
- Enforce strong passwords
- Enable real-time alerting
