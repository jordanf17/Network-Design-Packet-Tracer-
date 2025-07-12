### Project Skills and Technologies Showcase

This project demonstrates a comprehensive skill set in designing, building, and securing a modern enterprise network from the ground up. The goal was to create a robust and reliable infrastructure for a business with multiple departments, focusing on security and efficiency. Below is a summary of the key skills and technologies implemented.

#### Core Network Architecture & Design

* [cite_start]**Network Segmentation (VLANs)**: I digitally divided the company's network into isolated zones for each department (Sales, Finance, HR, etc.)[cite: 13, 98]. [cite_start]This is like putting up digital walls to ensure that traffic from one department doesn't spill over into another, which enhances security and improves network performance[cite: 13, 97].

* [cite_start]**Efficient Network Routing (Router-on-a-Stick)**: I designed a cost-effective and centralized system for managing all the data traffic between the different departmental VLANs[cite: 12, 95]. [cite_start]This streamlined approach reduces hardware costs and simplifies network management[cite: 95].

* [cite_start]**Automated IP Management (DHCP)**: I set up a dedicated server to automatically assign network addresses to all computers and devices[cite: 15, 301, 503]. [cite_start]This eliminates manual configuration errors and makes it easy to manage a large number of devices across different departments[cite: 503, 505].

* [cite_start]**Wireless Connectivity (WPA2-PSK)**: I deployed secure wireless access for each department, ensuring employees can connect their mobile devices safely without compromising the network[cite: 16, 517]. [cite_start]Each department has its own unique SSID and password for controlled access[cite: 510, 512].

#### Advanced Security Implementation

* [cite_start]**Multi-Layered Firewall Protection (Zones of Trust & ZBF)**: I built a robust security posture by creating three distinct security zones: a trusted **Internal** zone for employees, an untrusted **External** zone for the internet, and a semi-trusted **DMZ** to safely host public-facing servers (like the company website and email server)[cite: 20, 679]. [cite_start]A Zone-Based Firewall acts as an intelligent security guard, inspecting all traffic that moves between these zones to block threats[cite: 22, 23].

* [cite_start]**Secure Remote Office Connectivity (Site-to-Site IPsec VPN)**: I constructed a secure, encrypted "tunnel" over the internet to connect the main office with a remote branch[cite: 26]. [cite_start]This VPN uses powerful AES-256 encryption to ensure that all data transmitted between the sites remains confidential and protected from eavesdropping[cite: 27, 1312].

* [cite_start]**Centralized Administrator Access Control (AAA Server)**: I implemented a centralized AAA (TACACS+) server to manage who can log in and make changes to critical network equipment[cite: 29]. [cite_start]This system ensures that only authorized administrators have access, with different privilege levels assigned to different users[cite: 30, 1362], providing a single point of control for device security.

* [cite_start]**Granular Traffic Control (Access Control Lists - ACLs)**: I wrote specific rule sets (ACLs) to control exactly what kind of traffic is allowed to flow between different network segments[cite: 22, 1114]. [cite_start]For example, these rules can be configured to prevent one department from accessing another's sensitive servers while still allowing access to shared resources[cite: 1115, 1116].
