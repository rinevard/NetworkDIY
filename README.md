NetworkDIY
==============================

[英文说明 (English Version)](./README_en.md)

我在学习计算机网络时发现了 CS168 和 CS144 这两门课程。我的原计划是学习 CS144 从而同时学习计网和现代 C++，但我能找到的 CS144 视频资料比较古早，官网提供的 Notes 也有些零散。

而回望 CS168，我发现其课程学习资料极其完善，配套的电子版教材内容全面且简洁生动，最新年份视频公开，授课老师幽默风趣，唯一美中不足的就是使用的编程语言以 Python 为主，不太满足我对学习现代 C++ 的需求。

于是我就想，能不能学 CS168 提供的学习资料，但做 CS144 的 Labs？实践证明是可行的。我把我用到的学习资料和学习日程列在下面两个表中以供参考。

CS144 2025 Fall 的 starter code 也被备份在本仓库中，实验文档及其中英对照（机翻）在 [handouts](./handouts/) 中，希望对你有帮助。

| 资源名 | 链接 |
| :--- | :--- |
| CS168 SP25 官网 | https://sp25.cs168.io/
| CS168 教材 | https://textbook.cs168.io/
| CS168 SP25 视频列表 | https://www.youtube.com/playlist?list=PL0_XloRC3MWs5MylcqPFEeTCx0RQocrD7 |
| CS144 官网 | https://cs144.github.io/ |
| CS144 Labs | https://github.com/CS144/minnow |

| 阶段 | CS144 Lab | CS168 Lectures | 备注 |
| :--- | :--- | :--- | :--- |
| P1 | Lab 0: ByteStream | 1. Intro 1: Layers of the Internet<br>2. Intro 2: Design Principles | Lab 0 是熟悉 C++ 环境，看导论课即可。 |
| P2 | Lab 1: Reassembler | 3. Intro 3: Links | Lab 1 是一个纯逻辑算法题，理论需求不高，再看一节课。 |
| P3 | Lab 2: TCP Receiver | 11-12. Transport 1: TCP | Lab 2 与 TCP 协议有关，跳跃看课。CS168 前期花了较多篇幅讲路由，而把 TCP 放在课程中期。 |
| P4 | Lab 3: TCP Sender | 13-15. Transport 3: Congestion Control | Lab 3 也与 TCP 有关，我们可以把 CS168 的 TCP 课程看完。 |
| P5 | Lab 4: Real World | 4-6 Routing 1-2: Principles, Distance-Vector | Lab 4 不需要写代码，ping 真实网站并收集数据画图。我们正好补补前期的路由课。 |
| P6 | Lab 5: Network Interface | 18-20. End-to-End: Ethernet, STP, ARP, DHCP | Lab 5 把 IP 和 Ethernet 连接起来，我们要学学同一子网下的主机如何通信。 |
| P7 | Lab 6: IP Router | 7-8. Routing 3-4: Link-State, Addressing, Routers | Lab 6 要实现软件路由器，回到 CS168 前半部分看看路由课。 |
| P8 | Lab 7: Putting it together | 21-22. Datacenters: Topology, Routing | Lab 7 不需要写代码。补下主线课。 |
| P9 | 无 Lab | 9-10. Routing (DV, LS, BGP)<br>16-17. Applications (DNS, HTTP)<br>23. SDN<br>24-25. Beyond Client-Server: Multicast, Collectives | Lab 做完了，补完剩余的主线课程。 |
| P10 | 无 Lab | 26. Wireless<br>27. Cellular | 拓展内容，Wi-Fi 和手机蜂窝移动网络，可选学习。 |

感谢 Stanford CS144 和 Berkeley CS168 开源的顶级课程资源。