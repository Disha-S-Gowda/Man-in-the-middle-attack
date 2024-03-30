# Man-in-the-middle-attack

The **"ARP Attack"** project is designed to provide hands-on experience in understanding and executing ARP (Address Resolution Protocol) attacks. The project consists of several tasks aimed at setting up the SEED Lab environment, performing ARP cache poisoning attacks, launching Man-in-the-Middle (MITM) attacks on Telnet and Netcat communications

**Inintial Setup(Tast 0):**
I set up the SEED Lab environment on DigitalOcean.

**ARP Cache Poisoning (Task 1):**
I performed  ARP cache poisoning attacks using ARP request, ARP reply, and ARP gratuitous message methods.
These attacks involved manipulating ARP packets to associate a target IP address with a different MAC address, potentially redirecting traffic intended for the target to the attacker's machine.

**MITM Attack on Telnet (Task 2):**
I set up a Man-in-the-Middle (MITM) attack scenario where Hosts A and B were communicating via Telnet.
Using ARP cache poisoning, I intercepted the traffic between A and B, enabling me to monitor or modify the data exchanged between them.

**MITM Attack on Netcat (Task 3):**
Similar to Task 2, but this time, Hosts A and B communicated using Netcat instead of Telnet.
I performed ARP cache poisoning to intercept and manipulate the data exchanged between A and B.

**Write-Up (Task 4):**
I provided a comprehensive write-up summarizing my learnings about ARP attacks, including how ARP works, the different types of ARP attacks, and the implications of these attacks on network security.
I discussed interesting observations, such as how easily ARP cache poisoning can be executed and the potential for attackers to intercept sensitive information.
I also highlighted any challenges faced during the lab, such as setting up the environment or troubleshooting issues with the attacks.

Overall, this lab provided hands-on experience with ARP attacks, helping me understand their mechanisms and the importance of mitigating such threats in real-world networks.
