# Spoofed-Packet-Detection-and-Prevention-Mechanism
IP-Spoofing is an attack that forges the source
IP Address to mislead the receiver about the sender and makes it
difficult to trace back. Existing IP-Spoofing prevention methods
like Ingress/Egress filtering, Reverse Path Forwarding (RPF) have
the following limitations: they filter only the IP Packets of the
local network, limited logging capabilities, and they work only
for specific types of TCP/IP protocol attacks. In this paper, we
proposed an Anti IP Spoofing method called “Border Gateway
Protocol Anti Spoofing Extension” (BGP-ASE) to stop spoofed
packets successfully. The proposed mechanism is tested using
emulation network environments consisting of Mininet, OpenFlow
Switch, and POX Controller. Usage of random filter placement
improve the performance for dropping attack packets ratio. BGPASE
is more potent than Ingress/Egress and RPF filtering in
dropping attack packets. In BGP-ASE mechanism, only 30%
transit Autonomous Systems can filter greater than 90% of the
malicious packets. BGP-ASE also has the following desirable
properties - Initial Benefits for early users, Incremental Benefits
for subsequent users, and effectiveness in partial deployment.

