# Adaptive Quality of Service using Predictive Rate Approximatin using Openflow Meters

## Abstract
Internet traffic has been continuously increasing since the introduction of first computer networks. With this comes the need to stay updated with the current network technology to make the most of the modern network demands. Service providers have to distribute the bandwidth across thousands of customers by giving certain portion of the link to them. In turn, the customers have to maximize the link usage to ensure least packet loss and congestion on the outgoing traffic. During peak hours, users might experience delay in the quality of service (QoS) they receive due to packet losses and congested link. For this reason, network administrators classify different types of traffic into different classes and prioritize some over the others based on their importance. Each class gets a portion of the link and are not allowed to exceed their rate. Allocating and distributing the link with traditional networking comes as a challenge as the configurations are not dynamic and cannot be reconfigured based on the current traffic pattern. Software Defined Networking (SDN) leverages this limitation and provides new ways of managing networks. SDN address the problem of bandwidth allocation in real time by monitoring the traffic flow and applying the necessary rates set by the network programmer. However, the allocation also depends on the current flow rate. Flow rate must be correctly calculated to maximize the available link bandwidth. Thus, this research first looks at different methods of approximating traffic and taking the best method to further apply to the bandwidth allocation problem. The proposed algorithms are tested in a simulated network environment in Mininet with OpenFlow switches. The results showed that a predictive method of traffic rate approximation incurs the least packet loss in a bursty network environment with maximum throughput. An Adaptive Fair QoS (AFQoS) algorithm is proposed that not only incurs the least packet loss but also maximizes the outgoing link usage.


The repository contains the following directories:
- data - contains the data that was generated during the experiment
- helper_code - contains code that was used to aid the development process
- production_code - contains code that can be used as a final product and integrated in SDN networks
- research_code - contains code that was written to prove the concept

Each of the directories contain the following files:
data