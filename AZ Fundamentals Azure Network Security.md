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
