# Incident Response Simulation Report.

**Project:** Simulated system logs with event timestamps and Malware detection alerts.  
**Tools Used:** Splunk  
**Prepared by:** Duncan Maganga  
**Date:** August 22, 2025  
**Task:** 2  

## Executive Summary

This report documents the analysis of simulated system, network, and authentication logs collected from the organization’s SIEM platform. The objective was to detect suspicious activity, classify incidents by severity, and provide guidance on remediation.
During the investigation, five suspicious users were identified, including multiple log-in attempts and several malware signatures. Based on the impact, all the incidents were classified as high priority.	

## Purpose and Scope

**Purpose:** To simulate real-world incident detection and response using sample SIEM logs  
**Scope:** Analysis covered:  
- System logs with timestamps  
- Network connection logs with source and destination IPs  
- Authentication logs with successful and failed logging attempts  
- Malware detection alerts   


Tools and Methodology

•	Tools: Splunk 


•	Methodology:
1.	Correlation and filtering: Applied different SPL queries
2.	Classification: Incident ranked as High, Medium, or Low based on the impact.
3.	Timeline Construction: Events mapped chronologically to understand the attack flow.
4.	Mitigations: Drafted recommended containment and remediation actions.


<img width="468" height="470" alt="image" src="https://github.com/user-attachments/assets/91a90a6d-e40c-4877-a153-933e41c78549" />
