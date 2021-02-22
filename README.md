Network Disruption Analysis using NS2 Simulator and TCL

In this project the following had been implemented:

1.Creating the nodes of the network and creating the duplex links.  

2.They have a bandwidth varying from 2Mb to 4Mb and propagation delay of 10ms and 5ms and will be using SFQ scheduling algorithm.

3..Create UDP agents (udp0 & udp1) and (tcp0: New Reno, tcp1: Vegas, tcp2: Reno).

4.Setting up ftp over tcp.

5..Attaching cbr to udp and setting packet size and rate.

6.Attaching sinks.

7.Assigning different colors for different packets.

8.Disrupting the link between adjacent nodes for 0.5 seconds.

After the implementation:

9.Store the respective network information in their trace files.
10.
11.Plotting the xgraph plots of udp0 vs udp1 bandwidth analysis plots , tcp0 vs tcp1, tcp1 vs tcp2 and tcp2 vs tcp0 congestion window plots using their trace files.
