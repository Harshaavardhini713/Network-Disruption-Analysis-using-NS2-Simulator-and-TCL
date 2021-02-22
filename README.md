Network Disruption Analysis using NS2 Simulator and TCL

In this project the following had been implemented:

Creating the nodes of the network and creating the duplex links.

They have a bandwidth varying from 2Mb to 4Mb and propagation delay of 10ms and 5ms and will be using SFQ scheduling algorithm.

Create UDP agents (udp0 & udp1) and (tcp0: New Reno, tcp1: Vegas, tcp2: Reno).

Setting up ftp over tcp.

Attaching cbr to udp and setting packet size and rate.

Attaching sinks.

Assigning different colors for different packets.

Disrupting the link between adjacent nodes for 0.5 seconds.

After the implementation:

Store the respective network information in their trace files.

Plotting the xgraph plots of udp0 vs udp1 bandwidth analysis plots , tcp0 vs tcp1, tcp1 vs tcp2 and tcp2 vs tcp0 congestion window plots using their trace files.
