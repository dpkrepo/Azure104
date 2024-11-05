Manage Azure identities and governance (20–25%)	
Manage Microsoft Entra users and groups	
Create users and groups	
•	Sign in to the Microsoft Entra admin center as at least a User Administrator.	
•	Navigate to Identity > Users > All users.	
•	Select New users > Create new user.	
•	Fill in the required details (e.g., User principal name, Display name, Password).	
•	Click Create.	
•	To create a group, navigate to Identity > Groups > All groups.	
•	Select New group > Create new group.	
•	Fill in the group details (e.g., Group name, Membership type).	
•	Click Create	
Manage user and group properties	
•	Navigate to Identity > Users > All users or Identity > Groups > All groups.	
•	Select the user or group you want to manage.	
•	Click Properties to view and edit details.	
Manage licenses in Microsoft Entra ID	
•	Sign in to the Microsoft Entra admin center as a License Administrator.	
•	Navigate to Identity > Billing > Licenses.	
•	Select All products to view license details.	
•	Assign or remove licenses as needed	
Manage external users	
•	Navigate to Identity > External Identities > Users.	
•	Add external users by selecting New external user and filling in the required details	
Configure self-service password reset (SSPR)	
•	Sign in to the Microsoft Entra admin center as a Global Administrator.	
•	Navigate to Identity > Password reset.	
•	Enable SSPR and configure the settings according to your organization's needs.	
Manage access to Azure resources	
Manage built-in Azure roles	
•	Sign in to the Azure portal: Go to the Azure portal and sign in with your credentials.	
•	Navigate to Access control (IAM): In the search box at the top, type "Access control (IAM)" and select it.	
•	View roles: Click on the "Roles" tab to see a list of all built-in and custom roles.	
•	Select a role: Click on the role you want to manage to view its details and permissions.	
Assign roles at different scopes	
•	Identify the needed scope: Determine the scope at which you want to assign the role (management group, subscription, resource group, or resource).	
•	Open the Add role assignment page: Go to the specific scope and click on "Access control (IAM)".	
•	Add role assignment: Click on "Add" > "Add role assignment".	
•	Select the role: Choose the appropriate role from the list.	
•	Select who needs access: Choose the user, group, or service principal to whom you want to assign the role.	
•	Assign the role: Click "Save" to assign the role.	
Interpret access assignments	
•	View role assignments: Go to the "Access control (IAM)" page for the specific scope.	
•	Check role assignments: Click on the "Role assignments" tab to see a list of all role assignments at that scope.	
•	View details: Click on a specific role assignment to view details about the assigned role and the assigned user or group.	
Manage Azure subscriptions and governance	
Implement and manage Azure Policy (Enforce organizational standards and assess compliance at scale)	
•	Navigate to Azure Policy: Go to the Azure portal and search for "Policy".	
•	Assign a Policy: Select "Assignments" on the left side of the Azure Policy page.	
•	Select Scope: Choose the scope (management group, subscription, resource group, or individual resource).	
•	Choose a Policy Definition: Select a built-in policy or create a custom one.	
•	Apply the Policy: Assign the policy to enforce conditions for resources.	
Configure resource locks (Resource locks prevent accidental deletions or modifications)	
•	Navigate to the Resource: Go to the resource you want to lock in the Azure portal.	
•	Select Locks: Under the "Settings" section, select "Locks".	
•	Add a Lock: Provide a name for the lock and select the type (CanNotDelete or ReadOnly).	
•	Apply the Lock: Save the lock.	
Apply and manage tags on resources (Tags help organize and manage resources)	
•	Navigate to the Resource: Go to the resource or resource group in the Azure portal.	
•	Select Tags: Under the "Settings" section, select "Tags".	
•	Add Tags: Enter the name and value for the tag, then save.	
•	Manage Tags: You can view, edit, or delete tags as needed.	
Manage resource groups	
•	Navigate to Resource Groups: Go to the Azure portal and search for "Resource Groups".	
•	Create or Manage: Create new resource groups or manage existing ones by selecting them from the list.	
•	Add Resources: Add resources to the group as needed.	
Manage subscriptions	
•	Navigate to Subscriptions: Go to the Azure portal and search for "Subscriptions".	
•	Manage Access: Use Azure RBAC to control access to resources within the subscription.	
•	Monitor Usage: Keep track of usage and costs associated with the subscription.	
Manage costs by using alerts, budgets, and Azure Advisor recommendations	
•	Set Up Alerts: Go to the Azure portal and search for "Alerts" to set up cost alerts.	
•	Create Budgets: Use the "Budgets" feature to set spending limits and receive notifications.	
•	Use Azure Advisor: Azure Advisor provides recommendations to optimize costs and improve performance.	
Configure management groups	
•	Navigate to Management Groups: Go to the Azure portal and search for "Management Groups".	
•	Create a Management Group: Select "Create" and follow the prompts to set up a new management group.	
•	Assign Subscriptions: Add subscriptions to the management group for centralized management.	
Implement and manage storage (15–20%)	
Configure access to storage	
Configure Azure Storage firewalls and virtual networks	
•	Navigate to your storage account in the Azure Portal.	
•	Select "Networking" from the left-hand menu.	
•	Go to the "Firewalls and virtual networks" tab.	
•	Configure the settings:	
•	Allow access from: Choose "Selected networks" to limit access to specific IP addresses or virtual networks.	
•	Network routing preference: Choose "Microsoft network routing" for optimal performance.	
•	Save your changes.	
Create and use shared access signature (SAS) tokens	
•	Navigate to your storage account in the Azure Portal.	
•	Select the container or blob you want to grant access to.	
•	Click on "Shared access signature" in the toolbar.	
•	Configure the SAS token:	
•	Start time: Specify when the SAS token should start.	
•	Expire time: Specify when the SAS token should expire.	
•	Permissions: Choose the permissions you want to grant.	
•	Generate the SAS token and copy it.	
Configure stored access policies	
•	Navigate to your storage account in the Azure Portal.	
•	Select the container where you want to apply the policy.	
•	Click on "Access policy" in the menu.	
•	Create a new stored access policy:	
•	Name: Provide a name for the policy.	
•	Start time: Specify the start time.	
•	Expiry time: Specify the expiry time.	
•	Permissions: Choose the permissions.	
•	Save the policy.	
Manage access keys	
•	Navigate to your storage account in the Azure Portal.	
•	Select "Access keys" from the menu.	
•	Regenerate keys periodically to maintain security.	
•	Use the keys to authorize access to your storage account.	
•	Configure identity-based access for Azure Files	
•	Navigate to your storage account in the Azure Portal.	
•	Select "Identity-based access" from the menu.	
•	Enable Azure AD authentication for your storage account.	
•	Assign permissions to users or groups using Azure RBAC.	
•	Use managed identities to grant access to your storage data without including SAS tokens.	
Configure and manage storage accounts	
Create and configure storage accounts	
•	Open the Azure Portal: Sign in to your Azure account.	
•	Create a Storage Account: Go to the "Storage accounts" page and click on "+ Create" to start the process.	
•	Fill in the Basics: Provide a unique name for your storage account, select your subscription, resource group, and region.	
•	Set Performance and Redundancy: Choose the performance tier (Standard or Premium) and redundancy options (LRS, ZRS, GRS, etc.)3. 	
•	Review and Create: Review your settings and click "Create" to deploy the storage account.	
Configure Azure Storage redundancy	
•	Navigate to Your Storage Account: Go to the storage account you created.	
•	Select Redundancy Settings: Under "Data management," select "Redundancy".	
•	Choose Redundancy Type: Select the desired redundancy option (LRS, ZRS, GRS, etc.) and save your changes.	
•	Configure object replication	
•	Navigate to the Source Storage Account: Go to the source storage account in the Azure portal.	
•	Select Object Replication: Under "Data management," select "Object replication".	
•	Create Replication Rules: Select the destination subscription and storage account, and specify the source and destination containers.	
•	Save the Policy: Save your replication policy.	
Configure storage account encryption	
•	Navigate to Your Storage Account: Go to the storage account in the Azure portal.	
•	Select Encryption Settings: Under "Settings," select "Encryption" and configure encryption options (Microsoft-managed keys or customer-managed keys).	
Manage data by using Azure Storage Explorer and AzCopy	
•	Azure Storage Explorer: Download and install Azure Storage Explorer7. Connect it to your Azure account and use it to manage your storage resources visually. 	
•	AzCopy: Install AzCopy and use it to transfer data to and from your storage account via command line. Example command: azcopy copy 'C:\local\path\to\file.txt' 'https://<storage-account-name>.blob.core.windows.net/<container-name>/<file-path>'	
Configure Azure Files and Azure Blob Storage	
Create and configure a file share in Azure Storage	
•	Create a Storage Account: Go to the Azure portal, search for "Storage accounts", and click on "Create".	
•	Configure Storage Account: Fill in the required details like name, region, and performance tier.	
•	Create a File Share: Once the storage account is created, go to "File shares" under the Data storage section and click on "+ File share".	
•	Configure File Share: Provide a name, set the quota, and choose the performance tier.	
Create and configure a container in Blob Storage	
•	Create a Storage Account: Follow the same steps as above.	
•	Create a Container: Go to "Containers" under the Data storage section and click on "+ Container".	
•	Configure Container: Provide a name and set the access level.	
Configure storage tiers	
•	Navigate to Storage Account: Go to your storage account in the Azure portal.	
•	Select Access Tier: Under the "Settings" section, select "Access tier" and choose between "Hot" (frequent access) or "Cool" (infrequent access).	
Configure snapshots and soft delete for Azure Files	
•	Enable Snapshots: Go to your file share, select "Settings", and enable "Snapshots".	
•	Enable Soft Delete: Under the "Settings" section, enable "Soft delete" to protect against accidental deletion.	
•	Configure blob lifecycle management	
•	Navigate to Blob Service: Go to your storage account and select "Blob service".	
•	Lifecycle Management: Click on "Lifecycle management" and configure rules to transition or delete blobs based on age or other criteria.	
Configure blob versioning	
•	Navigate to Blob Service: Go to your storage account and select "Blob service".	
•	Enable Versioning: Click on "Versioning" and enable it to keep track of changes and restore previous versions of blobs.	
Deploy and manage Azure compute resources (20–25%)	
Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files	
Interpret an Azure Resource Manager template or a Bicep file	
•	ARM templates are JSON files that define the infrastructure and configuration for your project. Bicep is a domain-specific language (DSL) that offers the same capabilities as ARM templates but with a more concise syntax. Each Bicep file is automatically converted to an ARM template during deployment.	
Modify an existing Azure Resource Manager template	
•	Edit the JSON file directly: Open the template in a JSON editor like Visual Studio Code with the Azure Resource Manager Tools extension.	
•	Update specific resources: Modify the properties of resources within the template. For example, to update a virtual network, you can change the addressSpace or subnets properties.	
Modify an existing Bicep file	
•	Edit the Bicep file directly: Open the file in Visual Studio Code with the Bicep extension.	
•	Update parameters, variables, or resources: Make changes to the Bicep syntax to reflect the desired infrastructure.	
Deploy resources by using an Azure Resource Manager template or a Bicep file	
•	Using Azure CLI: Run the az deployment group create command with the template file as an argument.	
•	Using Azure PowerShell: Use the New-AzResourceGroupDeployment cmdlet with the template file.	
•	Using the Azure Portal: Navigate to the "Deploy a custom template" option, upload your template file, and provide the necessary parameters.	
Export a deployment as an Azure Resource Manager template or convert an Azure Resource Manager template to a Bicep file	
•	From the Azure Portal: Navigate to the resource group, select "Export template," and download the template.	
•	Using Azure CLI: Use the az resource export command to export the template.	
Create and configure virtual machines	
Create a virtual machine	
•	Sign in to the Azure portal.	
•	Navigate to "Virtual Machines" and click on "Create" and then "Virtual Machine".	
•	Fill in the required details such as the resource group, VM name, region, image, and size.	
•	Set up an administrator account and configure inbound port rules.	
•	Review and create the VM.	
Configure Azure Disk Encryption	
•	Create an Azure Key Vault to store encryption keys.	
•	Create a Key Encryption Key (KEK) if needed.	
•	Navigate to your VM, select "Disks", and then "Additional settings".	
•	Select the disks to encrypt and choose the key vault and key for encryption.	
Move a virtual machine to another resource group, subscription, or region	
•	Go to the VM you want to move.	
•	Select "Move" and choose the target resource group, subscription, or region.	
•	Follow the prompts to complete the move.	
Manage virtual machine sizes	
•	Go to the VM you want to resize.	
•	Select "Size" and choose a new size from the available options.	
•	Save the changes.	
Manage virtual machine disks	
•	Go to the VM and select "Disks".	
•	Add or remove disks as needed.	
•	Resize disks if necessary.	
Deploy virtual machines to availability zones and availability sets	
•	Go to "Virtual Machines" and click "Create".	
•	Select "Availability options" and choose an availability zone or set.	
•	Complete the VM creation process as usual.	
Deploy and configure an Azure Virtual Machine Scale Sets	
•	Navigate to "Virtual Machine Scale Sets" and click "Create".	
•	Fill in the required details such as the scale set name, resource group, and region.	
•	Configure the scale set with the desired VM size, image, and scaling settings.	
•	Review and create the scale set.	
Provision and manage containers in the Azure portal	
Create and manage an Azure container registry	
•	Sign in to Azure: Go to the Azure portal and sign in with your account.	
•	Create a Container Registry: Select "Create a resource" > "Containers" > "Container Registry".	
•	Configure Basics: Enter a unique name for your registry, select a resource group, and choose the location.	
•	Review and Create: Review the settings and click "Create".	
•	Log in to the Registry: Use the Azure CLI to log in with az acr login --name <registry-name>.	
Provision a container by using Azure Container Instances	
•	Sign in to Azure: Go to the Azure portal.	
•	Create a Container Instance: Select "Create a resource" > "Containers" > "Container Instances".	
•	Configure Basics: Choose your subscription, resource group, container name, and image source.	
•	Networking: Specify a DNS name label for your container.	
•	Review and Create: Review the settings and click "Create".	
•	View Logs: Navigate to your resource group and view the container logs.	
Provision a container by using Azure Container Apps	
•	Sign in to Azure: Go to the Azure portal.	
•	Create a Container App: Search for "Container Apps" and select it.	
•	Configure Basics: Enter the project details, resource group, and container app name.	
•	Container Settings: Select the container image and configure the environment.	
•	Review and Create: Review the settings and click "Create".	
•	Verify Deployment: Go to the resource group and view the application URL.	
Manage sizing and scaling for containers, including Azure Container Instances and Azure Container Apps	
•	Azure Container Instances: Use the Azure portal or CLI to scale container instances by adjusting the number of instances.	
•	Azure Container Apps: Use the Azure portal or CLI to manage scaling by configuring the environment and setting autoscale rules.	
Create and configure Azure App Service	
Provision an App Service plan	
•	Go to the Azure portal and sign in.	
•	Select "Create a resource" and search for "App Service Plan".	
•	Fill in the required details such as the name, region, operating system (Windows or Linux), and pricing tier.	
•	Click "Review + create" and then "Create" to provision the App Service Plan.	
Configure scaling for an App Service plan	
•	Navigate to your App Service Plan in the Azure portal.	
•	Select "Scale out (App Service plan)" from the left menu.	
•	Choose "Custom auto scale" and set rules based on metrics like CPU usage or request count.	
•	Save the settings to apply the scaling configuration.	
Create an App Service	
•	Go to the Azure portal and select "Create a resource".	
•	Search for "Web App" and click "Create".	
•	Fill in the required details such as the name, subscription, resource group, and region.	
•	Select the App Service Plan you created earlier and click "Review + create".	
•	Click "Create" to create the App Service.	
Configure certificates and Transport Layer Security (TLS) for an App Service	
•	Go to your App Service in the Azure portal.	
•	Select "TLS/SSL settings" from the left menu.	
•	Upload your SSL certificate and configure the bindings.	
•	Save the changes to apply the TLS settings.	
Map an existing custom DNS name to an App Service	
•	Go to your App Service in the Azure portal.	
•	Select "Custom domains" from the left menu.	
•	Add a new domain and enter the DNS name you want to map.	
•	Update your DNS records with the provided name servers to complete the mapping	
Configure backup for an App Service	
•	Go to your App Service in the Azure portal.	
•	Select "Backups" from the left menu.	
•	Enable backups and configure the backup frequency and retention period.	
•	Save the settings to apply the backup configuration.	
Configure networking settings for an App Service	
•	Go to your App Service in the Azure portal.	
•	Select "Networking" from the left menu.	
•	Configure the settings such as virtual network integration, access restrictions, and custom domains.	
•	Save the changes to apply the networking settings.	
Configure deployment slots for an App Service	
•	Go to your App Service in the Azure portal.	
•	Select "Deployment slots" from the left menu.	
•	Create a new slot and configure the settings such as the name and configuration.	
•	Deploy your app to the slot and test it before swapping it to production.	
Implement and manage virtual networking (15–20%)	
Configure and manage virtual networks in Azure	
Create and configure virtual networks and subnets	
•	Sign in to the Azure portal.	
•	Create a resource group by selecting "Create a resource" > "Resource group".	
•	Create a virtual network by selecting "Networking" > "Virtual Network".	
•	Add subnets by clicking on the "Subnets" tab and then "Add subnet".	
•	Configure the IP address range for each subnet.	
Create and configure virtual network peering	
•	Navigate to the virtual network you want to peer.	
•	Select "Peerings" in the settings menu.	
•	Click "Add" to create a new peering.	
•	Enter the remote virtual network details and configure the peering settings.	
Configure public IP addresses	
•	Create a public IP address by selecting "Networking" > "Public IP address".	
•	Assign the public IP address to a resource, such as a virtual machine or a load balancer.	
Configure user-defined network routes	
•	Navigate to the virtual network and select "Routes" under the settings menu.	
•	Add a new route by specifying the destination prefix, next hop type, and next hop IP address.	
Troubleshoot network connectivity	
•	Use Azure Network Watcher to diagnose and troubleshoot network issues.	
•	Run connectivity tests using tools like "Check connectivity" or "Ping" in Network Watcher.	
Configure secure access to virtual networks	
Create and configure network security groups (NSGs) and application security groups	
•	Create an NSG:	
	Go to the Azure portal.	
	In the search box, type "Network security group" and select it.	
	Click on "+ Create" and fill in the required details like name, subscription, and resource group.	
	Click "Review + create" and then "Create" to create the NSG.	
	Add Security Rules:	
	Go to the "Security rules" section of the NSG.	
	Click on "+ Add" to create a new rule.	
	Define the rule parameters such as name, priority, direction (inbound/outbound), port range, protocol, and source/destination.	
	Save the rule.	
•	Associate NSG with a Subnet or Network Interface:	
	Go to the subnet or network interface you want to associate with the NSG.	
	Under "Settings," find the "Network security group" section and select the NSG you created.	
	Save the changes.	
Evaluate effective security rules in NSGs	
•	View Effective Security Rules:	
	Go to the Azure portal and select the virtual machine or network interface.	
	Under "Settings," select "Networking" and then "Effective security rules".	
	This will show you the aggregated inbound and outbound rules applied to the network interface.	
•	Troubleshoot Connectivity Issues:	
	Use the "NSG diagnostics" feature in Azure Network Watcher to check if traffic is allowed or denied by the applied security rules.	
	This helps in identifying misconfigured rules that might be causing connectivity issues.	
Implement Azure Bastion	
•	Create a Virtual Network:	
	Go to the Azure portal and create a new virtual network.	
	Add subnets for the virtual machines and the Bastion host.	
•	Enable Azure Bastion:	
	In the virtual network settings, under "Security," select "Azure Bastion" and enable it.	
	Configure the Bastion host name and public IP address.	
•	Connect to a Virtual Machine:	
	Once Bastion is set up, use it to connect to your virtual machines without exposing them to the internet.	
Configure service endpoints for Azure platform as a service (PaaS)	
•	Go to the Azure portal:	
	Navigate to the specific PaaS service you want to configure endpoints for.	
	Select "Networking" and then "Service endpoints".	
•	Add Service Endpoint:	
	Click on "+ Add" and select the appropriate service endpoint type (e.g., SQL Database, Storage, etc.).	
	Select the virtual network and subnet you want to enable the endpoint for.	
	Save the changes.	
Configure private endpoints for Azure PaaS	
•	Go to the Azure portal:	
	Navigate to the specific PaaS service and select "Networking".	
	Click on "+ Add" and select "Private endpoint".	
•	Create Private Endpoint:	
	Select the virtual network and subnet where you want to create the private endpoint.	
	Configure the private endpoint settings and click "Create".	
Configure name resolution and load balancing	
Configure Azure DNS	
•	Sign in to the Azure portal.	
•	Create a DNS zone:	
•	Select Create a resource.	
•	Search for DNS zone and select it.	
•	Enter the required details like Resource group, Name, and Resource group location.	
•	Click Review + create and then Create.	
•	Create DNS records:	
•	Navigate to your DNS zone.	
•	Select Record sets and then Add.	
•	Enter the required details like Name, Type, and TTL.	
•	Click Save.	
Configure an internal or public load balancer	
•	Internal Load Balancer	
	1. Create a NAT gateway for outbound internet access.	
	2. Create a virtual network and bastion host.	
	3. Create the internal load balancer:	
	Select Create a resource.	
	Search for Load balancer and select it.	
	Enter the required details like Resource group, Name, and Region.	
	Configure the frontend IP, backend pool, and health probe.	
	Click Review + create and then Create.	
•	Public Load Balancer	
	1. Create a NAT gateway for outbound internet access.	
	2. Create a virtual network and bastion host.	
	3. Create the public load balancer:	
	Select Create a resource.	
	Search for Load balancer and select it.	
	Enter the required details like Resource group, Name, and Region.	
	Configure the frontend IP, backend pool, and health probe.	
	Click Review + create and then Create.	
Troubleshoot load balancing	
•	Check health probes: Ensure that the backend VMs are responding to health probes.	
•	Verify network security groups (NSGs): Ensure that the NSGs are allowing the required traffic.	
•	Monitor load balancer metrics: Use Azure Monitor to check metrics like Data Path Availability and Health Probe Status.	
•	Check backend VMs: Ensure that the backend VMs are listening on the correct ports and not blocked by NSGs.	
Monitor and maintain Azure resources (10–15%)	
Monitor resources in Azure	
Interpret metrics in Azure Monitor (In Azure Monitor, you can use the Metrics Explorer)	
•	Open Metrics Explorer: Go to the Azure portal, select Monitor, and then Metrics.	
•	Select a Resource: Choose the resource you want to monitor.	
•	Choose Metrics: Select the metrics you want to view.	
•	Configure Time Range: Set the time range for the metrics.	
•	Analyze Data: Use the charts to visualize trends and identify any anomalies.	
Configure log settings in Azure Monitor	
•	Open Diagnostic Settings: Go to the resource you want to configure, select Monitoring, and then Diagnostic Settings.	
•	Add Diagnostic Setting: Click Add Diagnostic Setting.	
•	Select Logs: Choose the log categories you want to collect.	
•	Choose Destinations: Select where you want to send the logs (e.g., Log Analytics workspace, storage account, event hub).	
•	Save Settings: Save the diagnostic settings.	
Query and analyze logs in Azure Monitor	
•	Open Log Analytics: Go to the Azure portal, select Monitor, and then Logs.	
•	Write Queries: Use Kusto Query Language (KQL) to write queries.	
•	Run Queries: Execute the queries to retrieve and analyze data.	
•	Visualize Results: Use charts and tables to visualize the results.	
Set up alert rules, action groups, and alert processing rules in Azure Monitor	
•	Open Alerts: Go to the Azure portal, select Monitor, and then Alerts.	
•	Add Alert Rule: Click Add and configure the rule (e.g., condition, threshold).	
•	Create Action Group: Define the actions to take when an alert is triggered (e.g., email, SMS, webhook).	
•	Save Settings: Save the alert rule and action group.	
Configure and interpret monitoring of virtual machines, storage accounts, and networks by using Azure Monitor Insights	
•	Open Insights: Go to the Azure portal, select Monitor, and then Insights.	
•	Select Resource: Choose the resource you want to monitor.	
•	Configure Insights: Set up the monitoring parameters and view the insights dashboard.	
Use Azure Network Watcher and Connection Monitor	
•	Open Network Watcher: Go to the Azure portal, select Network Watcher, and then Connection Monitor.	
•	Create Monitor: Set up a connection monitor to track network performance and connectivity.	
•	Analyze Data: Use the data collected to identify and troubleshoot network issues.	
Implement backup and recovery	
Create a Recovery Services vault	
•	Sign in to the Azure portal.	
•	Search for Backup center and go to the Backup center dashboard.	
•	On the Overview pane, select Vault.	
•	Select Recovery Services vault and click Continue.	
•	Enter the required details (Subscription, Resource group, Vault name, Region) and click Review + create.	
•	Click Create to finish the process.	
Create an Azure Backup vault	
•	Sign in to the Azure portal.	
•	Type Backup vaults in the search box.	
•	Under Services, select Backup vaults.	
•	Click Add.	
•	Fill in the required details (Subscription, Resource group, Vault name, Region, Storage redundancy) and click Review + create.	
•	Click Create to finish the process.	
Create and configure a backup policy	
•	Go to the Backup center dashboard.	
•	Select your Recovery Services vault.	
•	Click on Backup policy and create a new policy.	
•	Define the backup schedule, retention policy, and other settings.	
•	Save the policy.	
Perform backup and restore operations by using Azure Backup	
•	Go to the Backup center dashboard.	
•	Select your Recovery Services vault.	
•	Click on Backup items and select the item you want to back up.	
•	Click Backup now to start the backup process.	
•	To restore, go to Backup items, select the item, and click Restore.	
Configure Azure Site Recovery for Azure resources	
•	Go to the Azure portal and search for Site Recovery.	
•	Create a new Recovery Services vault if you don't have one.	
•	Set up Replication for the resources you want to protect.	
•	Define the Recovery plan and Failover policies.	
•	Perform a failover to a secondary region by using Site Recovery	
•	Go to the Azure portal and select Site Recovery.	
•	Select your Recovery Services vault.	
•	Click on Failover plans and select the plan you want to execute.	
•	Click Failover to start the process.	
Configure and interpret reports and alerts for backups	
•	Go to the Backup center dashboard.	
•	Select your Recovery Services vault.	
•	Click on Reports to view backup reports.	
•	Set up Alerts to get notifications for backup status and issues.	
