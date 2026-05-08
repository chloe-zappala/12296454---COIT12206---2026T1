Portfolio for Chloe Zappala 12296454

All done in GNS3 with WireShark and FileZilla. 

Week 1 - Added and changed IP address of a Linux host using etc/network/interface. The IP was then checked in a seperate web console

Week 2 - Added four Linux hosts and a netwrok switch and changed IP addresses on two out of four Linux hosts. The other two hosts IP addresses were then set. The IP addresses were then checked in a seperate web console. Different ping 'options' were then used, and an IP address that does not exsit on the network was pinged. 

Week 3 - The before mentioned project was used. A 'netcat' server was started, and messages were sent between the client and the server hosts. A packet capture was started, with hosts pinged and netcat used to send messages. The file was then opened in WireShark using FileZilla

Week 4 - Added three Linux hosts, Linux router and connected them to the router. The IP and Gateways were then changed, forwarding on the router was enabled and the routing table was shown on each device. A ping test was then conducted.   A project with two hosts, four FFR's and two NETem's was opened. The IP address of neighbur routers, the destination subnet addresses adn the next node path was found. Traceroute was used to find the path between the two hosts, then that path was disconnected and Traceroute was used a secodn time. 

Week 5 - Added four Linux hosts and an OpenvSwitch, then connected them. The IP addresses were changed for the hosts, as well as two VLANs. Connectivity was tested. A router was then added, and two IP Subents were created. Two different VLANs were created then connectivity was tested. 

Week 6 - Using a previous GNS3 project with fours Linux hosts and a Switch, the ARP tables of hosts were looked at, then a ping between two devices was done, then the ARP table was re-examined.   A previous GNS3 project was used and added to, resulting in 4 Linux Hosts, 2 Switches and 2 Routers. Forwarding was enabled/disenabled for the routers and the hosts, then the IP addresses and routing tables were viewed for all routers and hosts. Connectivity between the two subnets was then tested.       - The ping test from a Host on one subent to another did not work, as well as the IP route tables for Host 3 and 4 not working. I beleive this is due to either Router 2 or Hosts 3 and 4 being incorrectly set-up. While I was able to ping Host 3 and 4 to eachother, I was not able to ping a Host on the other subnet. The routing table for Hosts 3 and 4 did not show the correct 'via', and showed 'ip: RTNETLINK answers: Network is unreachable'. 

Week 7 - Added 3 Linux Hosts, 1 switch and 1 OpenWRT. Connected all devices together using ehternet. Set DHCP IP addresses on all hosts. Changed DHCP server config, then used domains instead of IP addresses

Week 8 - Added one Linux host, two Routers, two Switches and a Server. Set IP addresses and Gateways, tested connectivity through use of ping and subnet captures (Wireshark). Then deleted the FireFox host and added a Linux host. Ran commands in both Host 1 and a shell. Captured packets and used Wireshark. 
