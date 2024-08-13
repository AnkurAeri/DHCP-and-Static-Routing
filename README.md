# DHCP-and-Static-Routing
A Cisco Packet Tracer Project

Network Design:

Defined IP address ranges for Toronto (192.168.10.64/26) and Brampton (192.168.20.32/27) subnets.
Established a Link Network using the provided IP address range (5.5.5.0/30) to connect both subnets.
2. Router Configuration:

Assigned IP addresses to router interfaces based on the network design:
Toronto router's F0/0: First usable IP from Toronto subnet (e.g., 192.168.10.65)
Toronto router's F0/1: First usable IP from Link Network (e.g., 5.5.5.1)
Brampton router's F0/0: First usable IP from Brampton subnet (e.g., 192.168.20.33)
Brampton router's F0/1: Second usable IP from Link Network (e.g., 5.5.5.2)
Implemented static routes on both routers to enable communication between Toronto and Brampton networks.
3. DHCP Server Configuration:

Configured Brampton router as the DHCP server to provide dynamic IP addresses to user PCs in both networks.
Created separate DHCP pools named after your first name (Toronto) and last name (Brampton) for IP address allocation.

4. DNS Server Configuration:

Set up a static DNS server on a separate PC with the provided IP address (192.168.20.35/27) and hostname "www.ilac.com" for name resolution.
5. Client Configuration:

Verified that user PCs in both networks (Toronto User1, User2, Brampton User3, User4) successfully obtain dynamic IP addresses from the DHCP server.
Confirmed their ability to browse the DNS server's website ("www.ilac.com").


This project demonstrates your understanding of network design, static routing, DHCP server configuration, DNS setup, and client connectivity verification.
