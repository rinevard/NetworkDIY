NetworkDIY
==============================

[中文说明 (Chinese Version)](./README.md)

This is a hybrid learning roadmap combining CS144 and CS168. CS168 has made its latest digital textbook and lecture videos publicly available, featuring a humorous and engaging instructor. Meanwhile, CS144 offers assignments based on modern C++. Therefore, this roadmap satisfies the needs for learning both Computer Networks and modern C++ simultaneously.

The starter code for CS144 Fall 2025 is backed up in this repository. The lab documentation, along with a Chinese-English comparison (machine-translated), can be found in the [handouts](./handouts/) folder. I hope you find this helpful.

How to use: For each stage, start by studying the CS168 materials. You can go through the "CS168 Readings" for that stage, watch the "CS168 Lectures" via the [YouTube Playlist](https://www.youtube.com/playlist?list=PL0_XloRC3MWs5MylcqPFEeTCx0RQocrD7), or do both. Once you have finished the theoretical part, complete the corresponding CS144 Lab using the [handouts](./handouts/), and then proceed to the next stage.

Since CS144 spans only 10 weeks while CS168 runs for 16 weeks, the final two stages will consist solely of lectures without accompanying Labs. Happy learning!

| Resource Name | Link |
| :--- | :--- |
| CS168 SP25 Official Site | https://sp25.cs168.io/
| CS168 Textbook | https://textbook.cs168.io/
| CS168 SP25 Playlist | https://www.youtube.com/playlist?list=PL0_XloRC3MWs5MylcqPFEeTCx0RQocrD7 |
| CS144 Official Site | https://cs144.github.io/ |
| CS144 Labs | https://github.com/CS144/minnow |

| Stage | CS144 Lab | CS168 Lectures | CS168 Readings | Remarks |
| :--- | :--- | :--- | :--- | :--- |
| P1 | Lab 0: ByteStream | 1. Intro 1: Layers of the Internet<br>2. Intro 2: Design Principles | [Intro](https://textbook.cs168.io/intro/intro.html), [Layers](https://textbook.cs168.io/intro/layers.html), [Headers](https://textbook.cs168.io/intro/headers.html)<br>[Architecture](https://textbook.cs168.io/intro/architecture.html), [Design](https://textbook.cs168.io/intro/sharing-resources.html) | Lab 0 is for familiarizing yourself with the C++ environment; watching the introductory lectures is sufficient. |
| P2 | Lab 1: Reassembler | 3. Intro 3: Links | [Links](https://textbook.cs168.io/intro/links.html), [Multiplexing](https://textbook.cs168.io/intro/sharing-resources.html) | Lab 1 is a pure logic/algorithm problem with low theoretical requirements. Watch one more lecture. |
| P3 | Lab 2: TCP Receiver | 11-12. Transport 1: TCP | [Principles (Reliability)](https://textbook.cs168.io/transport/reliability.html)<br>[Design](https://textbook.cs168.io/transport/tcp-design.html), [Implementation](https://textbook.cs168.io/transport/tcp-implementation.html) | Lab 2 relates to the TCP protocol, so we skip ahead in the lectures. CS168 spends considerable time on routing early on, placing TCP in the middle of the course. |
| P4 | Lab 3: TCP Sender | 13-15. Transport 3: Congestion Control | [Principles](https://textbook.cs168.io/transport/cc-principles.html), [Design](https://textbook.cs168.io/transport/cc-design.html), [Implementation](https://textbook.cs168.io/transport/cc-implementation.html)<br>[Throughput](https://textbook.cs168.io/transport/throughput-model.html), [Issues](https://textbook.cs168.io/transport/cc-issues.html), [Router-Assisted](https://textbook.cs168.io/transport/router-based-cc.html) | Lab 3 is also related to TCP, so we can finish the remaining TCP lectures in CS168. |
| P5 | Lab 4: Real World | 4-6. Routing 1-2: Principles, Distance-Vector | [Intro](https://textbook.cs168.io/routing/intro.html), [Model](https://textbook.cs168.io/routing/model.html), [States](https://textbook.cs168.io/routing/solutions.html)<br>[Distance-Vector](https://textbook.cs168.io/routing/distance-vector.html) | Lab 4 requires no coding; you will ping real websites, collect data, and plot graphs. This is a good time to catch up on the earlier routing lectures. |
| P6 | Lab 5: Network Interface | 18-20. End-to-End: Ethernet, STP, ARP, DHCP | [Ethernet](https://textbook.cs168.io/end-to-end/ethernet.html), [STP (L2 Routing)](https://textbook.cs168.io/end-to-end/l2-routing.html)<br>[ARP](https://textbook.cs168.io/end-to-end/arp.html), [DHCP](https://textbook.cs168.io/end-to-end/dhcp.html), [NAT](https://textbook.cs168.io/end-to-end/nat.html), [TLS](https://textbook.cs168.io/end-to-end/tls.html), [End-to-End](https://textbook.cs168.io/end-to-end/end-to-end.html) | Lab 5 connects IP and Ethernet. We will learn how hosts within the same subnet communicate. |
| P7 | Lab 6: IP Router | 7-8. Routing 3-4: Link-State, Addressing, Routers | [Link-State](https://textbook.cs168.io/routing/link-state.html), [Addressing](https://textbook.cs168.io/routing/addressing.html)<br>[Routers](https://textbook.cs168.io/routing/router.html) | Lab 6 involves implementing a software router. Let's return to the first half of CS168 to watch the routing lectures. |
| P8 | Lab 7: Putting it together | 21-22. Datacenters: Topology, Routing | [Topology](https://textbook.cs168.io/datacenter/topology.html), [Congestion](https://textbook.cs168.io/datacenter/datacenter-cc.html)<br>[Routing](https://textbook.cs168.io/datacenter/datacenter-routing.html), [Addressing](https://textbook.cs168.io/datacenter/datacenter-addressing.html), [Virtualization](https://textbook.cs168.io/datacenter/virtualization.html) | Lab 7 requires no coding. Catch up on the main course lectures. |
| P9 | No Lab | 9-10. Routing (BGP)<br>16-17. Applications (DNS, HTTP)<br>23. SDN<br>24-25. Multicast | [Model](https://textbook.cs168.io/routing/autonomous-systems.html), [Design](https://textbook.cs168.io/routing/bgp.html), [Implementation](https://textbook.cs168.io/routing/bgp-implementation.html), [IP Header](https://textbook.cs168.io/routing/ip-header.html)<br>[DNS](https://textbook.cs168.io/applications/dns.html), [HTTP](https://textbook.cs168.io/applications/http.html)<br>[SDN](https://textbook.cs168.io/datacenter/sdn.html), [Host Networking](https://textbook.cs168.io/special-topics/host-networking.html)<br>[Multicast](https://textbook.cs168.io/beyond-client-server/), [Operations](https://textbook.cs168.io/beyond-client-server/collective-operations.html), [Implementation](https://textbook.cs168.io/beyond-client-server/collective-implementations.html) | Labs are done. Finish the remaining core lectures. |
| P10 | No Lab | 26. Wireless<br>27. Cellular | [Wireless](https://textbook.cs168.io/special-topics/wireless.html)<br>[Cellular](https://textbook.cs168.io/special-topics/cellular.html) | Extended topics: Wi-Fi and cellular networks. Optional. |

Special thanks to Stanford CS144 and Berkeley CS168 for open-sourcing these top-tier course resources.