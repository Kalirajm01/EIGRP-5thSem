# EIGRP-5thSem

=> IGRP is used in TCP/IP and Open System Interconnection (OSI) Internets. The original IP version was designed and deployed successfully in 1986. It is regarded as an IGP but has also been used extensively as an Exterior Gateway Protocol (EGP) for inter-domain routing. IGRP uses distance vector routing technology. The concept is that each router need not know all the router/link relationships for the entire network. Each router advertises destinations with a corresponding distance. Each router hearing the information adjusts the distance and propagates it to neighboring routers.

=> The distance information in IGRP is represented as a composite of available bandwidth, delay, load utilization, and link reliability. This allows fine tuning of link characteristics to achieve optimal paths.

=> EIGRP is an enhanced version of IGRP. The same distance vector technology found in IGRP is also used in EIGRP, and the underlying distance information remains unchanged. The convergence properties and the operating efficiency of this protocol have improved significantly. This allows for an improved architecture while retaining existing investment in IGRP. The convergence technology is based on research conducted at SRI International. The Diffusing Update Algorithm (DUAL) is the algorithm used to obtain loop-freedom at every instant throughout a route computation. This allows all routers involved in a topology change to synchronize at the same time. Routers that are not affected by topology changes are not involved in the recomputation. The convergence time with DUAL rivals that of any other existing routing protocol. EIGRP has been extended to be network-layer-protocol independent, thereby allowing DUAL to support other protocol suites.

**NETWORK TOPOLOGY:**

<img width="668" alt="image" src="https://github.com/Kalirajm01/EIGRP-5thSem/assets/92640470/b30d36c7-a815-4c6a-9d5b-77918834ca01">

<img width="476" alt="image" src="https://github.com/Kalirajm01/EIGRP-5thSem/assets/92640470/838305e7-7203-4627-9d6b-4e48abdff47e">
<img width="412" alt="image" src="https://github.com/Kalirajm01/EIGRP-5thSem/assets/92640470/d113511c-be81-4388-b50a-b681cb360970">



**To show the EIGRP topology, enter show ip eigrp topology**
<img width="305" alt="image" src="https://github.com/Kalirajm01/EIGRP-5thSem/assets/92640470/3ecb4ffd-15d5-4f3b-9861-e3c9a98dda0c">
