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

`EDIT SOURCE AND DESTINATION IP ADDRESS IN ALL THE ATTACK SCRIPTS.`

### Workflow:

1. Host a test website on Victim VM using nginx server.
2. Clone the repository on both Agent and Attacker VM.
3. Setup static IP for all VMs on the same network.
4. Enable SSH connection between the machines.
5. Execute `botSearcher.py` on Attacker machine to get availabe hosts in the network
6. Run `botMaker.c` and give credentials of the Agent VM.
7. After gaining access to the Agent, execute the attack scripts.
8. *The attack will be initiated.*
9. Use wireshark on Victim machine to observe attack packets.
10. Use different tools to compare results like `LOIC, TorsHammer, Slowloris, etc.`

#### Project Demonstration: https://www.youtube.com/watch?v=01LLvJILuos


