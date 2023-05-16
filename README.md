# Constructing-AWS-EKS-Cluster
Here is an aws eks kubernetes cluster with 2 worker nodes and one nginx pod in a private subnets within a vpc and an application load balancer in public subnets to forward the traffic to the private worker nodes.

![Screenshot from 2023-05-16 20-16-09](https://github.com/mohamedsamirspot/Constructing-AWS-EKS-Cluster/assets/71722372/3a8434ac-f3e6-4e88-9be8-539ce2a04081)

Components
- vpc
- 2 public subnets
- 2 private subnets
- nat gateway
- internet gateway
- public application load balancer
- eks cluster
- node group with 2 worker nodes with auto scaling group


https://github.com/mohamedsamirspot/Constructing-AWS-EKS-Cluster/assets/71722372/703eb8d4-2f21-4f67-b57b-634b7a4c25cd

