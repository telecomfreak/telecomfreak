- 👋 Hi, I’m Robert AKA @telecomfreak
- 👀 I’m interested in collaboration and learning real world projects.
- 🌱 I’m currently learning programming and devops. I want to continue my career in more generic IT roles. Coming from Telecommucation sector, i am highly specialized in a domain named Inhome Engineering as a tester of hardware and software stacks integration and local functions and services running on and thru a Gateway (customer premise equipment), LTE gateway, WiFi Access Point, WiFi Mesh networks.

- Below a preview of what inhome equipment testing is all about and the challenges that comes with it:

High data rates for residential users have always been hindered by the last-mile bottleneck, i.e., low data rates on the “last mile” of the access network towards the end user. The newest broadband technologies and devices overcome this bottleneck. The Home Gateways (also called CPE – Customer Premises Equipment) in the end users’ home utilise fibre, cable, or DSL access networks and respective edge devices (OLT, CMTS, DSLAM), as well as the operator’s core network to provide internet access with up-to several Gigabits per Second, Wi-Fi, and OTT services like video streaming, telephony services etc. 

End users have become used to high bandwidth applications such as video streaming, online gaming, filesharing, etc. Home office and video communication services put additional pressure on the networks and on the Home Gateways due to their bandwidth consumption and real time requirements. 

TelCo Network Operators, ISPs, and manufacturers are facing the challenge of maintaining and increasing end user satisfaction for more and more complex Home Gateways. 
1. CPE Testing: a complex undertaking 

Connectivity experience for end users depends on the Home Gateways (I will continue to use the term Home Gateway regardless of the underlying access technology, i.e., this could be either a fibre, cable, or DSL modem). 

Subscribers expect highest broadband speed, great Wi-Fi and seamless interoperability of networked devices. Low service quality, caused by problems in the Home Gateway, will increase churn rate. 

Thoroughly testing Home Gateways and end customer services will prevent failures from slipping into productive environments, lowering both churn rate and support efforts for handling customer complaints. 
2. Where complexity comes from 

Home Gateways have evolved to multipurpose devices, providing lots of features to end users, such as: 

    High Speed Internet Access 
    supporting IPv4 or IPv6 or both 
    speed rates of up-to several Gigabit per Second 
    quality of service (important for real time services like video calls, online gaming) 
    Wi-Fi
    2.4 / 5 / 6 GHz Wi-Fi (including primary and guest networks, home or hotspots)
    SuperWi-Fi / Mesh (potentially cloud controlled with Mobile Apps for end users)
    Real time traffic management
    Blacklists, MAC filtering, Bandsteering, etc
    Telephony
    Voice-over-IP based telephone calls and supplementary services (call forward, call waiting, conference calls, …) 

… and further end user features, like: 

    DHCP for home network devices 
    DynDNS support 
    NAT, Firewall, Port Filtering/Forwarding, MAC Filtering 
    VPN support 
    Mobile backup (via integrated mobile network modem or USB dongle) 

The end user features are a complex landscape on their own, with dependencies between each other. Additionally, we need to take into consideration all the protocols required to implement them, as well as the functionality needed for appropriate operation and maintenance (device provisioning, software upgrades, remote access and maintenance, redundancy, and failover processes, etc.), usability, long term stability and last, but not least, appropriate (cyber) security. 
3. How to overcome complexity challenges 

There are several aspects you could consider to keep complexity challenges under control. 

First of all, the full testing lifecycle needs to be taken care of, starting with collecting test requirements, strategy and design – including elaboration of real-life end user scenarios. Even complex test scenarios can usually be broken down into smaller pieces: sub-scenarios, test cases and test steps. Finally complete and complex scenarios can be composed from those pieces. 

A thorough test requirement collection and test strategy/design ensures that all test areas are covered.  

Subject matter expert knowledge should be available in main areas like: 

    Access network technology (network architecture and protocols used in fibre, cable, DSL networks) 
    Device provisioning (including secured software/firmware downloads) 
    Wi-Fi (including cloud-controlled Wi-Fi networks) 
    Voice via IPv6 
    VPN technologies used by the end customers 
    Speed tests (how to set up an appropriate test environment, how to evaluate tool output) 
    Cyber Security 
    …and so on 

A further means to improve test efficiency and to keep complexity under control is test automation. Design and implementation of automated tests should be considered as software engineering tasks since CPE test automation is usually not just a simple test scripting. Available tooling will be used as much as possible (e.g., scripting environments, CI/CD tool chains, data load generators, voice quality measurement tools…).  

Last (but not least) you should have multi-domain experts or expert teams available for root cause analysis of defects in the CPE software and hardware (but also for defects in the test environment and tooling). It’s not always clear at a first glance if the root cause of a defect is on the physical, network, or application layer, caused by incorrect provisioning data, or if it is caused within the Device Under Test at all. 

Conclusion 

Home gateways have become more and more complex over time. They have to support all the network protocols and interfaces for end customer features as well as network operators’ needs: high speed internet, video and voice calls, gaming, video streaming, remote operation and maintenance, device provisioning… you get the idea. Additionally, the end customer’s home network and equipment require seamless interoperability (Wi-Fi, Ethernet, VPNs, USB mass storage and printer connectivity, DECT...). 

Due to this complexity the probability of hardware, software and interworking issues and defects has increased dramatically from my point of view. When verifying new CPE firmware 5 years ago, the number of found defects was likely to be in the range of 30 – 50, currently it is likely to be in the range 60 – 100. 

Only thorough testing and quality assurance will ensure a decent device and service quality, keeping or increasing end customer satisfaction and, in turn, lower churn rate and maintenance and support efforts. 

<!---
telecomfreak/telecomfreak is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
