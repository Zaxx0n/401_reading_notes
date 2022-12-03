# Sniffing Attacks

Two types, active and passive.
Passive sniffing happens at the hub.  
Active sniffing the sniffer floods the switch with bogus requests so that the CAM table gets full.  Once it is full, the switch will send the network traffic to all ports, like a hub.

MAC flooding: Flooding the switch with MAC addresses so that it overflows.
DNS cache poisoning: Altering the DNS cache records to redirect to a malicious website where the attacker can then capture the traffic.

Evil Twin: malicious software changes the DNS of the victim which will respond to the requests being able to be rerouted.

MAC spoofing:  Sniffing device is set up with a known MAC address and can capture traffic as a known device.

There is some anti-sniffer software.  

HTTP, TELNET, FTP, POP and SNMP are vulnerable to sniffing attacks as they are unencrypted.