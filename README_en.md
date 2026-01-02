NetworkDIY
==============================

[中文说明 (Chinese Version)](./README.md)

While learning Computer Networking, I came across two courses: CS168 and CS144. My original plan was to take CS144 to learn both networking and modern C++ simultaneously. However, I found the available CS144 lecture videos a bit dated, and the official notes felt somewhat scattered.

Turning to CS168, I found its learning materials extremely well-organized. The accompanying online textbook is comprehensive, concise, and vivid. The lecture videos are up-to-date, and the instructor is humorous and engaging. The only downside was that CS168 primarily uses Python, which didn't fit my goal of mastering modern C++.

So I thought: Can I study using the CS168 materials but do the CS144 Labs? 

Practice proved this to be a feasible path. I have listed the resources used and my study schedule below for reference.

The CS144 Fall 2025 starter code is also backed up in this repository and the lab handouts are placed in the [handouts](./handouts/) folder. I hope this helps you.

| Resource | Link |
| :--- | :--- |
| CS168 SP25 Website | https://sp25.cs168.io/ |
| CS168 Textbook | https://textbook.cs168.io/ |
| CS168 SP25 Playlist | https://www.youtube.com/playlist?list=PL0_XloRC3MWs5MylcqPFEeTCx0RQocrD7 |
| CS144 Website | https://cs144.github.io/ |
| CS144 Labs | https://github.com/CS144/minnow |

| Stage | CS144 Lab | CS168 Lectures | Remarks |
| :--- | :--- | :--- | :--- |
| P1 | Lab 0: ByteStream | 1. Intro 1: Layers of the Internet<br>2. Intro 2: Design Principles | Lab 0 is for getting familiar with the C++ environment. Watching the intro lectures is sufficient. |
| P2 | Lab 1: Reassembler | 3. Intro 3: Links | Lab 1 is a pure logic/algorithm problem with low theoretical prerequisites. Watch one more lecture. |
| P3 | Lab 2: TCP Receiver | 11-12. Transport 1: TCP | Lab 2 relates to the TCP protocol, so we jump ahead in lectures. CS168 focuses on Routing early on and puts TCP in the middle. |
| P4 | Lab 3: TCP Sender | 13-15. Transport 3: Congestion Control | Lab 3 also relates to TCP. We can finish the remaining CS168 TCP lectures here. |
| P5 | Lab 4: Real World | 4-6. Routing 1-2: Principles, Distance-Vector | Lab 4 requires no coding (pinging real sites and collecting data). It's a perfect time to catch up on the early Routing lectures. |
| P6 | Lab 5: Network Interface | 18-20. End-to-End: Ethernet, STP, ARP, DHCP | Lab 5 connects IP and Ethernet. We need to learn how hosts communicate within the same subnet. |
| P7 | Lab 6: IP Router | 7-8. Routing 3-4: Link-State, Addressing, Routers | Lab 6 requires implementing a software router. Go back to the first half of CS168 to review Routing. |
| P8 | Lab 7: Putting it together | 21-22. Datacenters: Topology, Routing | Lab 7 requires no coding. Catch up on the main lecture timeline. |
| P9 | No Lab | 9-10. Routing (DV, LS, BGP)<br>16-17. Applications (DNS, HTTP)<br>23. SDN<br>24-25. Beyond Client-Server: Multicast | Labs are done. Complete the remaining core lectures. |
| P10 | No Lab | 26. Wireless<br>27. Cellular | Extended content: Wi-Fi and Cellular networks. Optional. |

Special thanks to Stanford CS144 and Berkeley CS168 for their top-tier open-source course resources.