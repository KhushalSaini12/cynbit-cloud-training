\# VPC Basics



\## What is a VPC?

A Virtual Private Cloud (VPC) is a logically isolated network in AWS where you can launch resources securely.



\## Subnet

A subnet is a section of a VPC.

Types:

\- Public Subnet

\- Private Subnet



\## Internet Gateway (IGW)

An Internet Gateway allows communication between a VPC and the Internet.



\## Route Table

A Route Table contains rules that determine where network traffic is directed.



\## Simple VPC Structure



Internet

&#x20;  |

&#x20;  v

Internet Gateway

&#x20;  |

&#x20;  v

VPC

&#x20;  |

&#x20;  +-- Public Subnet

&#x20;         |

&#x20;         +-- EC2 Instance



\## Summary

\- VPC provides network isolation.

\- Subnets divide the network.

\- IGW provides internet access.

\- Route Tables control traffic flow.

