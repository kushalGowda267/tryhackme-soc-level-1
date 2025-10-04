# Pyramid of Pain
[TryHackMe Room Link](https://tryhackme.com/room/pyramidofpainax)

## Objective
Learn the Pyramid of Pain model and the value of different indicators in disrupting adversaries.

## Key Concepts
- Pyramid levels: Hashes → IPs → Domains → Artifacts → Tools → TTPs  
- Higher levels are harder for attackers to change, more valuable for defenders  
- Balance between detectability and adversary cost

## Tools
- Threat intel platforms (MISP)  
- SIEM correlation rules  
- YARA for file detection  
- EDR for behavior/TTP detection

## Summary & Application
Blocking hashes/IPs has low impact; detecting TTPs forces adversaries to retool. Apply by prioritizing detection of behaviours (like lateral movement) rather than single indicators.
