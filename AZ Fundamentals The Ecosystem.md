AZ Fundamentals: The Ecosystem
----
#### Resource Group

A resource group is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group. You decide how you want to allocate resources to resource groups based on what makes the most sense for your organization. Generally, add resources that share the same lifecycle to the same resource group so you can easily deploy, update, and delete them as a group.

The resource group stores metadata about the resources. Therefore, when you specify a location for the resource group, you are specifying where that metadata is stored. For compliance reasons, you may need to ensure that your data is stored in a particular region.

----
#### Azure CLI

The Azure CLI is a command-line tool providing a great experience for managing Azure resources. The CLI is designed to make scripting easy, query data, support long-running operations, and More.

---
#### Azure Commands
az
az --version
az --help
az vm --help
az login
az vm list #get the details of the vm 

----


#### Create a vm on Azure Web Portal -> Bash
![aaa](create%20a%20vm.jpg)



----

#### Azure Regions and Availability Zones

Region: Geographical location consisting of one or more Availability Zones.   

Availability Zones: One or more data centers with high-speed network links, provides high availability within an Azure region.

#### ARM (Azure Resource Manager)

- manage Azure resources as a group
- GUI, command line
- ARM templates (.JSON file format)



