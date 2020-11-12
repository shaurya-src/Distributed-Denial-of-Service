# Distributed-Denial-of-Service

An Information Security Analysis and Audit Project at VIT, Vellore.

## How to run?

### Requirements:

- 3 VMs:
  * Kali Linux (Attacker)
  * Ubuntu (Agent)
  * Ubuntu (Victim)
- Nginx server
- Python 2.x
- C
- Nmap
- OpenSSH
- Wireshark

### Workflow:

1. Host a test website on Victim VM using **nginx** server.
2. Clone the repository on both Agent and Attacker VM.
3. Setup static IP for all VMs on the same network.
4. Enable SSH connection between the machines.
5. Use 
