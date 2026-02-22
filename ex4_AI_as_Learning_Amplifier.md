Exercise 4: AI as Learning Amplifier
Phase 1: Build Foundation (you first)
Step 1: Active Reading
some wireless routing protocols are;
Distance-vector: this a type of alogrithm when the router shared its distance to all with destinations with its immediate neighbors only
Link-state: its a routing alogrthm learns the complete network map by sharing information with all routers
AODV : (Ad Hoc On-Demand Distance Vector) AODV is a reactive routing protocol designed specifically for wireless ad hoc networks (like mobile devices communicating directly).
OLSR : (Optimized Link State Routing) OLSR is a proactive routing protocol for mobile ad hoc networks.
DSR : (Dynamic Source Routing) DSR is a reactive routing protocol for wireless ad hoc networks where the source node determines the entire route and includes it in the packet header.
Step 2: Self-Explanation: wirless routing protocols are the rules that determine the flow of data from one device to the other through a wireless method. (close doc)

Step 3: Design a Simple Scenario (5–10 Devices)
for example 8 wireless devices in a disaster recovery zone and No internet
Now justify:
Which routing protocol would you choose?
Why?
What trade-offs are you accepting?
reasoning:
I would use AODV because it is reactive and reduces overhead in a dynamic network.
Phase 2: Strategic AI Use
Test Your Understanding: I believe AODV is better than OLSR for highly mobile networks because it reduces control overhead. Is my reasoning correct? What am I missing?
Explore Edge Cases: What happens to AODV performance if the network grows from 8 nodes to 200 nodes?
Validate Assumptions: Are there scenarios where OLSR would outperform AODV in a small mobile network?
Phase 3: Real Application
Step 1: Understand the Environment
i have 1,000 IoT Sensors(Low power & Need energy efficiency etc )
50 Traffic Lights(Semi-static & Moderate traffic etc)
10 Emergency Vehicles: (Highly mobile & Real-time communication)
Step 2: Decide Protocols
For IoT Sensors: Low mobility, Stable topology & Less delay in routing decisions
For For Emergency Vehicles: Because vehicles move fast & Routes must be created on demand
Step 3: Identify Failure Points
interference in dense city areas
Network congestion during emergencies
Security vulnerabilities (spoofed nodes)
Step 4: Refine with AI Feedback
Is a hybrid protocol more efficient?
What happens if emergency vehicles create routing storms?
Would clustering reduce overhead?
Reflection:
QUESTION: % human judgment vs. AI contribution
ANSWER: 70% the architecture and protocol decisions were based on my reasoning. AI contributed %30 percent by identifying scalability issues and suggesting clustering optimizations.
QUESTION: Could you defend decisions without AI?
ANSWER: absolutely, i can
QUESTION: What will you still remember in 6 months?
ANSWER: in 6 months and more i will remember that proper way or ethical side of AI to be deployed correctly and unbiased prompting phasing.
QUESTION: Did AI make you sharper, or think for you?
ANSWER: yes it did made me sharper, it helps me to indicate point i didn't consider myself at first and it has enhance my knowledge greatly without thinking for me but working according to my own thinking passed down for it to follow.
