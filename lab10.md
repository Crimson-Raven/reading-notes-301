# Author: Rebecca Childs
## Reading Notes:
### Lab 10

### How can one host within a VPC any services that need to be public?
VPCs can host public services through a public subnet with an internet gateway attached.  Security groups on the subnet allow inbound traffic from the internet on specific ports (e.g., port 80 for web traffic). Public IP addresses are assigned to the resources for public access. This approach balances security with public accessibility.

### What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part?
In a VPC, public-facing services like websites, public APIs, and CDN origin servers live in the public subnet. This subnet allows controlled internet access through security groups and public IP addresses.
For enhanced security, private-only resources like databases, internal applications, and backend servers reside in the private subnet. They can't be directly accessed from the internet but can communicate securely with public services within the VPC.

### What are the trade-offs of using a VPC vs traditional infrastructure?
VPCs offer strong security, scalability, and cost-efficiency compared to traditional infrastructure. However, they come with some trade-offs. You might experience vendor lock-in and increased management complexity, and latency could be slightly higher.
Traditional infrastructure offers direct hardware control and potentially lower latency, but it's less scalable and more expensive to maintain in the long run.
The best choice depends on your priorities. Consider security, budget, technical expertise, control needs, and scalability requirements.

## Things I want to learn more about:
N/A
