# PKG_485
We work to build a real 5G platform with O-RAN architecture, Kubernetes, SONiC, and Intel Tofino P4 Chip. Realize network resource allocation method by O-RAN RAN Intelligent Controller to rise the network resource utilization. Using Kubernetes to monitor and analyze resource usage on Server Switch to load balancing. Develop P4 application to control the network topology and modify routing table to short packet transmission path and avoid error.

# Project Development
1. Server Switch as Kubernetes Worker Node (SONiC OS)
>* SONiC basic operation
>* Install Kubernetes into SONiC system 
>* SONiC Linux Kernel update
>* Monitor SONiC resource usage status by Kubernetes
2. Deploy 5GC on Sever Switch
>* Free5GC container deployment to Kubernetes Server Switch Node in SONiC
>* Containerization and deployment of UERANSIM simulator (used to simulate mobile user and base stations)
>* 5GC UPF and UERANSIM connect Tofino chip via CPU channel (Simulate base station and 5G core network connection)
3. Develop P4 Applications on Tofino P4 Chip
>* Intel P4 basic test on Tofino chip (foundation of basic topology, modification of routing table)
4. Monitor and Analyze Resource usage on Server Switch
>* Monitor system resource usage status through Kubernetes monitoring tools Prometheus and Grafana
