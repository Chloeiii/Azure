
AZ Fundamentals: Virtual Machines
----
####  Azure Load Balancing
- public load balancer
- internal load balancer  

Configure Load Balancer
- Azure Portal
- Azure CLI: az network lb create
- Azure PowerShell: New-AzLoadBalancer
- ARM template: Microsoft.Network/LoadBalancers

---
####  Azure Functions
- Serverless computing
- Create and run code
	- Fees are based on when code is running
- Underlying instrastucture is taken care of 
- Foucus on Code and apps instead of the supporting infrastructure 
---
####  Exercise
- List Azure virtual machine configuration considerations

		VM size
		Azure region in which VM will be deployed
		VM OS and data disks
		VM extensions (agents) - security, backup and script support
		Azure subnet 
		


- Deploy a Linux virtual machine using the portal
- Explain the benefit of virtual machine scale sets

		Load blanacing
		Auto-scaling
		Identical VMs
		
- Describe the purpose of Azure serverless computing

		No focus on underlying infrastructure
		More focus on code/app solutions
		Cloud-hosted code
		Pay only when code is running
