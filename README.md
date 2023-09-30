# Azure-Network-Design
                                                                               ** Fictional Company **

INTERFACE.COM : A Brief Overview


Company Description:

InterfaceTech is a fictitious e-commerce enterprise with a specialisation in electronic merchandise, serving primarily the Europe market. To ensure resilience and top-tier performance, the infrastructure is anchored by dual primary data centers.

System Architecture Highlights:

User Interface: End-users are presented with an intuitive web portal, allowing them to efficiently navigate and query the comprehensive product database.

API Integration: The platform incorporates an advanced API Management Gateway, which serves as the nexus between end-users, internal stakeholders, and developers. This gateway efficiently directs traffic to relevant API endpoints based on pre-established protocols.

Backend and Payment Processing: A streamlined backend structure offers seamless integration with third-party payment solutions. Outgoing traffic is channeled through a meticulously defined and secure conduit to the broader internet.

Data Security: All sensitive information, including user credentials and transaction details, resides in a fortified data plane, ensuring utmost security and confidentiality.




Legend
External Load Balancing End Point for Ingress  Web-Traffic and API inbound connections.) A Performance Based Routing profile used here.
Internal Load Balancing(ILB) for Internal Users.
Data Spoke responsible for Payments to third parties with UDR and NSG deployed with controlled Egress Traffic.
VNET to VNET Peering for Data and API connections via NVA.
Branches and Clients connectivity using VPN and ER connections

