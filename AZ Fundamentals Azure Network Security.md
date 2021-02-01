
AZ Fundamentals: Azure Network Security
----
#### Azure Firewall
- Has a static public IP address
- Rules control traffic flow
- Threat intelligence can alert on and deny traffic

----
#### Update the Firewall Rules
locate the firewall -> Rules -> Add application Rule collection ->create

		e.g. 
		Name: 			AllowCNN
		Source 			Addresses: *
		Protocol/ Port: http, https
		Target FQDNS:  	*.cnn.com
----
Azure DDoS - Distributed Denial of Service   
Azure NDGs - Network Security Groups (Allow and Deny actions)

 
----
#### Create a VM Jumpbox
1. create a jumbox VM
2. from the jumbox VM, we can connect to other VM(with private IP but without public IP) through Remote Desktop connection.
----
#### Azure ATP - Azure Advanced Threat Protection
- Require an ATP license
- Managed throuth the ATP portal
	- https://portal.atp.azure.com
- Connects to and monitors Active Directory
	- Azure ATP sersor

---- 
#### Exercise
- Describe how security is enhanced when using
	- Azure Firewall
	- Azure DDoS mitigation 
	- Network security groups (NSGs)

Firewall:
- Controls in and outbound traffic to and from Azure
- Associated with Azure VNet subnets
- Firewall, Network and Application rules
- For Application Rules, create a route table resource

Azure DDoS mitigation:
- Distributed Denial of Service
- "Basic" protection is enabled automatically at no cost
- "Standard"
	- configured in VNet properties
	- Adaptive tuning based on deployed VNet resources
	- Alerts
	
Network security groups (NSGs)
- Associated with NICs, subnets
- Inbound network security rules
- Outbound network security fules
- Each rule has a priority value
- Traffic can be allowed or denied
