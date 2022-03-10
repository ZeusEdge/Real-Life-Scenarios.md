The first website is to be used across the whole world

www.darey.io

The second website is a tooling app used internlly by the devops team. It must not be publicly accessible to the entire world, only specific addresses must be allowed.

www.tooling.darey.io

## Implementation

Always sketch out your solution before implementation

Think about the following as you design the solution

- **Security**
- --Do not put your application in public subnets
- --Use Security groups to limit access to EC2 instances
- **Availability**
- --Spread your workloads across multiple availability zones
- --Fault tolerance
- **Scalability**
- Begin the implementation first from the console, then using automation with terraform
