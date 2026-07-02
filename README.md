# Network-Lab-Notes
Studies Documentation
🎯 Description
This repository documents Nmap and Netcat scenarios I studied during my personal cybersecurity lab time. It is not a tutorial — it is a structured record of experiments, outputs, and reflections so I can track how my understanding evolves.Built during my cybersecurity studies as a student in Brazil.
📚 Topics covered
TCP scan techniques — SYN, Connect, ACK, UDP, and timing options.
Service discovery — identifying running services and versions.
Banner grabbing — reading service banners manually and with tools.
Netcat reverse shells fundamentals — understanding how reverse shells work in controlled lab environments.
🔧 Lab setupMost experiments are run in one of these safe environments:
A local virtual machine (VirtualBox / VMware).
A dedicated Kali Linux VM.
Legal CTF platforms and intentionally vulnerable machines.
My own isolated home network (no external scanning without permission).
✅ Key learnings
Nmap flags and scan types affect noise level, speed, and reliability.
Service banners can leak useful information, but they should be interpreted carefully.
Netcat is powerful for both troubleshooting and learning how reverse shells work.
Always document the command, expected result, and actual output to learn from mistakes.
🚀 Next steps
Add packet captures and analysis examples with Wireshark.
Compare Nmap results with other scanners to understand differences.
Practice more advanced Netcat use cases, such as file transfers and bind shells.
Document defensive countermeasures for each offensive technique I study.
