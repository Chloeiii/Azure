AZ Fundamentals: Network Components
----
####  Virtual Network  
CLI:  
az network vnet --help  

Powershell:  

		$vnet = new-azvirtualnetwork ...
		$subnet= add-azvirtualnetworksubnetconfig ...
		$vnet|set-azvirtualnetwork
---

 #### Azure IP Addressing  
Static IP address  
Dynamic IP address  
Private IP Addressing  
Public IP Addressing (Public IPv6 - public facing Load Balancers only)  

---
#### Configure an Azure Point to Site VPN :open_mouth::open_mouth::open_mouth::open_mouth::open_mouth::open_mouth::open_mouth::open_mouth:
1. Virtual networks -> Subnets
2. Create Gateway subnet
3. Create Virtual Network Gateway
4. the deployment may take up to 45 mins 

In the mean time:  
generate root certificate    
generate client certificte   
export a public key from the root cert to a file and paste to Azure vitual network gateway (Point-to-site configuration)    
Download VPN Client -> Open the zip file -> run the exe installer -> connect   

--- 
#### Configure Azure Application Gateway
Create 2 Virtual machine  
create application gateway    
go to the application gateway -> edit the backend pools -> set the virtual machines  

---
#### Content Delivery Network (CDN)  

goal: speed up end-user content delivery experience    

Features:  

		Geo-filtering
		Content compression
		Caching rules
		Site acceleration
		HTTPS custom domains
		
Configure:   
App Services -> Networking -> Azure CDN 




