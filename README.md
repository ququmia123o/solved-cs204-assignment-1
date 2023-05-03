Download Link: https://assignmentchef.com/product/solved-cs204-assignment-1
<br>
5/5 - (1 vote)

1. Define Virtual circuit and datagram switching. Compare Virtual circuit network with datagram network. Is Virtual circuit same as Physical connection. Comment

2. In the context of Network Layer, what is Logical address and Physical address in computer networks? Why a mapping from logical address to physical address and vice versa is required? Explain the protocols which perform it.

3. Discuss the various scenarios, where UDP is preferred to TCP.

4. Two IITs located in different cities wish to have a jam session over a communications network. Find the maximum possible distance between the IITs if they are to interact in real-time, in the sense of experiencing the same delay in hearing each other as if they were 10 meters apart. The speed of sound is approximately 330 meters/second. Assume that the network transmits the sound at the speed of light in cable, 2.3 x 108 meters/second.

5. In the 1950s, standard containers were developed for the transportation of goods. These standard containers could fit on a train car, on a truck, or in specially designed container ships. The standard size of the containers makes it possible to load and unload them much more quickly than using non-standard

containers of different sizes. Draw an analogy to packet switching communications networks. In your answer identify what might constitute a container and speculate on the advantages that may come from standard-size information containers.

6. Suppose that an interactive video game is accessed over a communication network. What requirements are imposed on the network if the network is connection-oriented? What if the network is connectionless?

7. Explain why it is useful for application layer programs to have a “well-known” TCP port number?

8. What advantage does a circuit-switched network have over a packet-switched network? What advantages does TDM have over FDM in a circuit-switched network?

9. Suppose end system A wants to send a large file to end system B. At a very high level,describe how end system A creates packets from the file. When one of these packets arrives toa router, what information in the packet does the router use to determine the link onto which the packet is forwarded? Why is packet switching in the Internet analogous to driving from one city to another and asking directions along the way?

10. Consider an application that transmits data at a steady rate (for example, the sender generates an N-bit unit of data every k time units, where k is small and fixed). Also, when such an application starts, it will continue running for a relatively long period of time. Answer the following questions, briefly justifying your answer:

a. Would a packet-switched network or a circuit-switched network be more appropriate for this application? Why?

b. Suppose that a packet-switched network is used and the only traffic in this network comes from such applications as described above. Furthermore, assume that the sum of the application data rates is less than the capacities of each and every link. Is some form of congestion control needed? Why?

11. Consider a router buffer preceding an outbound link. In this problem, you will use Little’s formula, a famous formula from queuing theory. Let N denote the average number of packets in the buffer plus the packet being transmitted. Let a denote the rate of packets arriving at the link.

Let d denote the average total delay (i.e., the queuing delay plus the transmission delay) experienced by a packet. Little’s formula is N = a.d). Suppose that on average, the buffer contains 10 packets, and the average packet queuing delay is 10 msec. The link’s transmission rate is100 packets/sec. Using Little’s formula, what is the average packet arrival rate, assuming thereis no packet loss?

12. When a file is transferred between two computers, two acknowledgement strategies are possible. In the first one, the file is chopped up into packets, which are individually acknowledged by the receiver, but the file transfer as a whole is not acknowledged. In the second one, the packets are not acknowledged individually, but the entire file is acknowledged when it arrives. Discuss these two approaches.

13. A process on host 1 has been assigned port p, and a process on host 2 has been assigned port q. Is it possible for there to be two or more TCP connections between these two ports at the same time?

14. Consider the following figure. Assume that we know the bottleneck link along the path from the server to the client is the first link with rate Rs bits/sec. Suppose we send a pair of packets back to back from the server to the client, and there is no other traffic on this path. Assume each packet of size L bits, and both links have the same propagation delay dprop.

a. What is the packet inter-arrival time at the destination? That is, how much time elapses from when the last bit of the first packet arrives until the last bit of the second packet arrives?