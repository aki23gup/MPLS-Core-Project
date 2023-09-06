# MPLS-Core-Project

## Objective
To design and simulate an MPLS network for TD Bank and its resources via ISP providers like Lumen and Cogent. Simulated on GNS3.

## Requirements
### Client
- TD Bank has on-premise datacentres with the subnets 142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24.  
- TD Bank has also resources in the cloud, both in Azure and AWS. 
- TD Bank has direct connect style MPLS tunnels to Azure and AWS.

### MPLS Service Provider
- Lumen provides the MPLS transport service to TD's Azure resources. 
- Cogent provides the MPLS transport service to TD's AWS resources. 
- Any computing resource connected to TD’s networks (142.205.1.0/24, 142.205.2.0/24, 142.205.3.0/24, and 142.205.4.0/24) must have connectivity with the compute resources in Azure and AWS.  
- The TD compute resources located in the two cloud providers must have mutual access for replication purposes.

## Topology
Here is the topology for the network design:
