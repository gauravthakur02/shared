---
title: azure-roles
markmap:
  colorFreezeLevel: 100
---
# _**Azure Roles**_
## **Azure Built-In Roles**

### General
#### Contributor
- `Grants full access to manage all resources, but does not allow you to assign roles in Azure RBAC, manage assignments in Azure Blueprints, or share image galleries.`
#### Owner
- `Grants full access to manage all resources, including the ability to assign roles in Azure RBAC.`
#### Reader
- `View all resources, but does not allow you to make any changes.`
#### Role Based Access Control Administrator
- `Manage access to Azure resources by assigning roles using Azure RBAC. This role does not allow you to manage access using other ways, such as Azure Policy.`
#### User Access Administrator
- `Lets you manage user access to Azure resources.`
### Compute
#### Classic Virtual Machine Contributor
- `Lets you manage classic virtual machines, but not access to them, and not the virtual network or storage account they're connected to.`
#### Compute Gallery Artifacts Publisher
- `This is the role for publishing gallery artifacts.`
#### Compute Gallery Sharing Admin
- `This role allows user to share gallery to another subscription/tenant or share it to the public.`
#### Data Operator for Managed Disks
- `Provides permissions to upload data to empty managed disks, read, or export data of managed disks (not attached to running VMs) and snapshots using SAS URIs and Azure AD authentication.`
#### Desktop Virtualization Application Group Contributor
- `Contributor of the Desktop Virtualization Application Group.`
#### Desktop Virtualization Application Group Reader
- `Reader of the Desktop Virtualization Application Group.`
#### Desktop Virtualization Contributor
- `Contributor of Desktop Virtualization.`
#### Desktop Virtualization Host Pool Contributor
- `Contributor of the Desktop Virtualization Host Pool.`
#### Desktop Virtualization Host Pool Reader
- `Reader of the Desktop Virtualization Host Pool.`
#### Desktop Virtualization Reader
- `Reader of Desktop Virtualization.`
#### Desktop Virtualization Session Host Operator
- `Operator of the Desktop Virtualization Session Host.`
#### Desktop Virtualization User
- `Allows user to use the applications in an application group.`
#### Desktop Virtualization User Session Operator
- `Operator of the Desktop Virtualization User Session.`
#### Desktop Virtualization Workspace Contributor
- `Contributor of the Desktop Virtualization Workspace.`
#### Desktop Virtualization Workspace Reader
- `Reader of the Desktop Virtualization Workspace.`
#### Disk Backup Reader
- `Provides permission to backup vault to perform disk backup.`
#### Disk Pool Operator
- `Provide permission to StoragePool Resource Provider to manage disks added to a disk pool.`
#### Disk Restore Operator
- `Provides permission to backup vault to perform disk restore.`
#### Disk Snapshot Contributor
- `Provides permission to backup vault to manage disk snapshots.`
#### Virtual Machine Administrator Login
- `View Virtual Machines in the portal and login as administrator`
#### Virtual Machine Contributor
- `Create and manage virtual machines, manage disks, install and run software, reset password of the root user of the virtual machine using VM extensions, and manage local user accounts using VM extensions. This role does not grant you management access to the virtual network or storage account the virtual machines are connected to. This role does not allow you to assign roles in Azure RBAC.`
#### Virtual Machine Data Access Administrator (preview)
- `Manage access to Virtual Machines by adding or removing role assignments for the Virtual Machine Administrator Login and Virtual Machine User Login roles. Includes an ABAC condition to constrain role assignments.`
#### Virtual Machine Local User Login
- `View Virtual Machines in the portal and login as a local user configured on the arc server`
#### Virtual Machine User Login
- `View Virtual Machines in the portal and login as a regular user.`
#### Windows Admin Center Administrator Login
- `Let's you manage the OS of your resource via Windows Admin Center as an administrator.`


### Networking
#### Azure Front Door Domain Contributor
- `For internal use within Azure. Can manage Azure Front Door domains, but can't grant access to other users.`
#### Azure Front Door Domain Reader
- `For internal use within Azure. Can view Azure Front Door domains, but can't make changes.`
#### Azure Front Door Profile Reader
- `Can view AFD standard and premium profiles and their endpoints, but can't make changes.`
#### Azure Front Door Secret Contributor
- `For internal use within Azure. Can manage Azure Front Door secrets, but can't grant access to other users.`
#### Azure Front Door Secret Reader
- `For internal use within Azure. Can view Azure Front Door secrets, but can't make changes.`
#### CDN Endpoint Contributor
- `Can manage CDN endpoints, but can't grant access to other users.`
#### CDN Endpoint Reader
- `Can view CDN endpoints, but can't make changes.`
#### CDN Profile Contributor
- `Can manage CDN and Azure Front Door standard and premium profiles and their endpoints, but can't grant access to other users.`
#### CDN Profile Reader
- `Can view CDN profiles and their endpoints, but can't make changes.`
#### Classic Network Contributor
- `Lets you manage classic networks, but not access to them.`
#### DNS Zone Contributor
- `Lets you manage DNS zones and record sets in Azure DNS, but does not let you control who has access to them.`
#### Network Contributor
- `Lets you manage networks, but not access to them.`
#### Private DNS Zone Contributor
- `Lets you manage private DNS zone resources, but not the virtual networks they are linked to.`
#### Traffic Manager Contributor
- `Lets you manage Traffic Manager profiles, but does not let you control who has access to them.`

### Storage 
#### Avere Contributor
- `Can create and manage an Avere vFXT cluster.`
#### Avere Operator
- `Used by the Avere vFXT cluster to manage the cluster`
#### Backup Contributor
- `Lets you manage backup service, but can't create vaults and give access to others`
#### Backup Operator
- `Lets you manage backup services, except removal of backup, vault creation and giving access to others`
#### Backup Reader
- `Can view backup services, but can't make changes`
#### Classic Storage Account Contributor
- `Lets you manage classic storage accounts, but not access to them.`
#### Classic Storage Account Key Operator Service Role
- `Classic Storage Account Key Operators are allowed to list and regenerate keys on Classic Storage Accounts`
#### Data Box Contributor
- `Lets you manage everything under Data Box Service except giving access to others.`
#### Data Box Reader
- `Lets you manage Data Box Service except creating order or editing order details and giving access to others.`
#### Data Lake Analytics Developer
- `Lets you submit, monitor, and manage your own jobs but not create or delete Data Lake Analytics accounts.`
#### Defender for Storage Data Scanner
- `Grants access to read blobs and update index tags. This role is used by the data scanner of Defender for Storage.`
#### Elastic SAN Owner
- `Allows for full access to all resources under Azure Elastic SAN including changing network security policies to unblock data path access`
#### Elastic SAN Reader
- `Allows for control path read access to Azure Elastic SAN`
#### Elastic SAN Volume Group Owner
- `Allows for full access to a volume group in Azure Elastic SAN including changing network security policies to unblock data path access`
#### Reader and Data Access
- `Lets you view everything but will not let you delete or create a storage account or contained resource. It will also allow read/write access to all data contained in a storage account via access to storage account keys.`
#### Storage Account Backup Contributor
- `Lets you perform backup and restore operations using Azure Backup on the storage account.`
#### Storage Account Contributor
- `Permits management of storage accounts. Provides access to the account key, which can be used to access data via Shared Key authorization.`
#### Storage Account Key Operator Service Role
- `Permits listing and regenerating storage account access keys.`
#### Storage Blob Data Contributor
- `Read, write, and delete Azure Storage containers and blobs. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Blob Data Owner
- `Provides full access to Azure Storage blob containers and data, including assigning POSIX access control. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Blob Data Reader
- `Read and list Azure Storage containers and blobs. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Blob Delegator
- `Get a user delegation key, which can then be used to create a shared access signature for a container or blob that is signed with Azure AD credentials. For more information, see Create a user delegation SAS.`
#### Storage File Data Privileged Contributor
- `Allows for read, write, delete, and modify ACLs on files/directories in Azure file shares by overriding existing ACLs/NTFS permissions. This role has no built-in equivalent on Windows file servers.`
#### Storage File Data Privileged Reader
- `Allows for read access on files/directories in Azure file shares by overriding existing ACLs/NTFS permissions. This role has no built-in equivalent on Windows file servers.`
#### Storage File Data SMB Share Contributor
- `Allows for read, write, and delete access on files/directories in Azure file shares. This role has no built-in equivalent on Windows file servers.`
#### Storage File Data SMB Share Elevated Contributor
- `Allows for read, write, delete, and modify ACLs on files/directories in Azure file shares. This role is equivalent to a file share ACL of change on Windows file servers.`
#### Storage File Data SMB Share Reader
- `Allows for read access on files/directories in Azure file shares. This role is equivalent to a file share ACL of read on Windows file servers.`
#### Storage Queue Data Contributor
- `Read, write, and delete Azure Storage queues and queue messages. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Queue Data Message Processor
- `Peek, retrieve, and delete a message from an Azure Storage queue. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Queue Data Message Sender
- `Add messages to an Azure Storage queue. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Queue Data Reader
- `Read and list Azure Storage queues and queue messages. To learn which actions are required for a given data operation, see Permissions for calling data operations.`
#### Storage Table Data Contributor
- `Allows for read, write and delete access to Azure Storage tables and entities`
#### Storage Table Data Reader
- `Allows for read access to Azure Storage tables and entities`

### Web and Mobile
#### Azure Maps Data Contributor
- `Grants access to read, write, and delete access to map related data from an Azure maps account.`
#### Azure Maps Data Reader
- `Grants access to read map related data from an Azure maps account.`
#### Azure Spring Cloud Config Server Contributor
- `Allow read, write and delete access to Azure Spring Cloud Config Server`
#### Azure Spring Cloud Config Server Reader
- `Allow read access to Azure Spring Cloud Config Server`
#### Azure Spring Cloud Data Reader
- `Allow read access to Azure Spring Cloud Data`
#### Azure Spring Cloud Service Registry Contributor
- `Allow read, write and delete access to Azure Spring Cloud Service Registry`
#### Azure Spring Cloud Service Registry Reader
- `Allow read access to Azure Spring Cloud Service Registry`
#### Media Services Account Administrator
- `Create, read, modify, and delete Media Services accounts; read-only access to other Media Services resources.`
#### Media Services Live Events Administrator
- `Create, read, modify, and delete Live Events, Assets, Asset Filters, and Streaming Locators; read-only access to other Media Services resources.`
#### Media Services Media Operator
- `Create, read, modify, and delete Assets, Asset Filters, Streaming Locators, and Jobs; read-only access to other Media Services resources.`
#### Media Services Policy Administrator
- `Create, read, modify, and delete Account Filters, Streaming Policies, Content Key Policies, and Transforms; read-only access to other Media Services resources. Cannot create Jobs, Assets or Streaming resources.`
#### Media Services Streaming Endpoints Administrator
- `Create, read, modify, and delete Streaming Endpoints; read-only access to other Media Services resources.`
#### SignalR AccessKey Reader
- `Read SignalR Service Access Keys`
#### SignalR App Server
- `Lets your app server access SignalR Service with AAD auth options.`
#### SignalR REST API Owner
- `Full access to Azure SignalR Service REST APIs`
#### SignalR REST API Reader
- `Read-only access to Azure SignalR Service REST APIs`
#### SignalR Service Owner
- `Full access to Azure SignalR Service REST APIs`
#### SignalR/Web PubSub Contributor
- `Create, Read, Update, and Delete SignalR service resources`
#### Web Plan Contributor
- `Manage the web plans for websites. Does not allow you to assign roles in Azure RBAC.`
#### Website Contributor
- `Manage websites, but not web plans. Does not allow you to assign roles in Azure RBAC.`

### Containers
#### AcrDelete
- `Delete repositories, tags, or manifests from a container registry.`
#### AcrImageSigner
- `Push trusted images to or pull trusted images from a container registry enabled for content trust.`
#### AcrPull
- `Pull artifacts from a container registry.`
#### AcrPush
- `Push artifacts to or pull artifacts from a container registry.`
#### AcrQuarantineReader
- `Pull quarantined images from a container registry.`
#### AcrQuarantineWriter
- `Push quarantined images to or pull quarantined images from a container registry.`
#### Azure Arc Enabled Kubernetes Cluster User Role
- `List cluster user credentials action.`
#### Azure Arc Kubernetes Admin
- `Lets you manage all resources under cluster/namespace, except update or delete resource quotas and namespaces.`
#### Azure Arc Kubernetes Cluster Admin
- `Lets you manage all resources in the cluster.`
#### Azure Arc Kubernetes Viewer
- `Lets you view all resources in cluster/namespace, except secrets.`
#### Azure Arc Kubernetes Writer
- `Lets you update everything in cluster/namespace, except (cluster)roles and (cluster)role bindings.`
#### Azure Container Storage Contributor
- `Install Azure Container Storage and manage its storage resources. Includes an ABAC condition to constrain role assignments.`
#### Azure Container Storage Operator
- `Enable a managed identity to perform Azure Container Storage operations, such as manage virtual machines and manage virtual networks.`
#### Azure Container Storage Owner
- `Install Azure Container Storage, grant access to its storage resources, and configure Azure Elastic storage area network (SAN). Includes an ABAC condition to constrain role assignments.`
#### Azure Kubernetes Fleet Manager Contributor Role
- `Grants read/write access to Azure resources provided by Azure Kubernetes Fleet Manager, including fleets, fleet members, fleet update strategies, fleet update runs, etc.`
#### Azure Kubernetes Fleet Manager RBAC Admin
- `Grants read/write access to Kubernetes resources within a namespace in the fleet-managed hub cluster - provides write permissions on most objects within a namespace, with the exception of ResourceQuota object and the namespace object itself. Applying this role at cluster scope will give access across all namespaces.`
#### Azure Kubernetes Fleet Manager RBAC Cluster Admin
- `Grants read/write access to all Kubernetes resources in the fleet-managed hub cluster.`
#### Azure Kubernetes Fleet Manager RBAC Reader
- `Grants read-only access to most Kubernetes resources within a namespace in the fleet-managed hub cluster. It does not allow viewing roles or role bindings. This role does not allow viewing Secrets, since reading the contents of Secrets enables access to ServiceAccount credentials in the namespace, which would allow API access as any ServiceAccount in the namespace (a form of privilege escalation). Applying this role at cluster scope will give access across all namespaces.`
#### Azure Kubernetes Fleet Manager RBAC Writer
- `Grants read/write access to most Kubernetes resources within a namespace in the fleet-managed hub cluster. This role does not allow viewing or modifying roles or role bindings. However, this role allows accessing Secrets as any ServiceAccount in the namespace, so it can be used to gain the API access levels of any ServiceAccount in the namespace.  Applying this role at cluster scope will give access across all namespaces.`
#### Azure Kubernetes Service Cluster Admin Role
- `List cluster admin credential action.`
#### Azure Kubernetes Service Cluster Monitoring User
- `List cluster monitoring user credential action.`
#### Azure Kubernetes Service Cluster User Role
- `List cluster user credential action.`
#### Azure Kubernetes Service Contributor Role
- `Grants access to read and write Azure Kubernetes Service clusters`
#### Azure Kubernetes Service RBAC Admin
- `Lets you manage all resources under cluster/namespace, except update or delete resource quotas and namespaces.`
#### Azure Kubernetes Service RBAC Cluster Admin
- `Lets you manage all resources in the cluster.`
#### Azure Kubernetes Service RBAC Reader
- `Allows read-only access to see most objects in a namespace. It does not allow viewing roles or role bindings. This role does not allow viewing Secrets, since reading the contents of Secrets enables access to ServiceAccount credentials in the namespace, which would allow API access as any ServiceAccount in the namespace (a form of privilege escalation). Applying this role at cluster scope will give access across all namespaces.`
#### Azure Kubernetes Service RBAC Writer
- `Allows read/write access to most objects in a namespace. This role does not allow viewing or modifying roles or role bindings. However, this role allows accessing Secrets and running Pods as any ServiceAccount in the namespace, so it can be used to gain the API access levels of any ServiceAccount in the namespace. Applying this role at cluster scope will give access across all namespaces.`
#### Kubernetes Agentless Operator
- `Grants Microsoft Defender for Cloud access to Azure Kubernetes Services`
#### Kubernetes Cluster - Azure Arc Onboarding
- `Role definition to authorize any user/service to create connectedClusters resource`
#### Kubernetes Extension Contributor
- `Can create, update, get, list and delete Kubernetes Extensions, and get extension async operations`

### Databases
#### Azure Connected SQL Server Onboarding
- `Allows for read and write access to Azure resources for SQL Server on Arc-enabled servers.`
#### Cosmos DB Account Reader Role
- `Can read Azure Cosmos DB account data. See DocumentDB Account Contributor for managing Azure Cosmos DB accounts.`
#### Cosmos DB Operator
- `Lets you manage Azure Cosmos DB accounts, but not access data in them. Prevents access to account keys and connection strings.`
#### CosmosBackupOperator
- `Can submit restore request for a Cosmos DB database or a container for an account`
#### CosmosRestoreOperator
- `Can perform restore action for Cosmos DB database account with continuous backup mode`
#### DocumentDB Account Contributor
- `Can manage Azure Cosmos DB accounts. Azure Cosmos DB is formerly known as DocumentDB.`
#### Redis Cache Contributor
- `Lets you manage Redis caches, but not access to them.`
#### SQL DB Contributor
- `Lets you manage SQL databases, but not access to them. Also, you can't manage their security-related policies or their parent SQL servers.`
#### SQL Managed Instance Contributor
- `Lets you manage SQL Managed Instances and required network configuration, but can't give access to others.`
#### SQL Security Manager
- `Lets you manage the security-related policies of SQL servers and databases, but not access to them.`
#### SQL Server Contributor
- `Lets you manage SQL servers and databases, but not access to them, and not their security-related policies.`

### Analytics
#### Azure Event Hubs Data Owner
- `Allows for full access to Azure Event Hubs resources.`
#### Azure Event Hubs Data Receiver
- `Allows receive access to Azure Event Hubs resources.`
#### Azure Event Hubs Data Sender
- `Allows send access to Azure Event Hubs resources.`
#### Data Factory Contributor
- `Create and manage data factories, as well as child resources within them.`
#### Data Purger
- `Delete private data from a Log Analytics workspace.`
#### HDInsight Cluster Operator
- `Lets you read and modify HDInsight cluster configurations.`
#### HDInsight Domain Services Contributor
- `Can Read, Create, Modify and Delete Domain Services related operations needed for HDInsight Enterprise Security Package`
#### Log Analytics Contributor
- `Log Analytics Contributor can read all monitoring data and edit monitoring settings. Editing monitoring settings includes adding the VM extension to VMs; reading storage account keys to be able to configure collection of logs from Azure Storage; adding solutions; and configuring Azure diagnostics on all Azure resources.`
#### Log Analytics Reader
- `Log Analytics Reader can view and search all monitoring data as well as and view monitoring settings, including viewing the configuration of Azure diagnostics on all Azure resources.`
#### Schema Registry Contributor (Preview)
- `Read, write, and delete Schema Registry groups and schemas.`
#### Schema Registry Reader (Preview)
- `Read and list Schema Registry groups and schemas.`
#### Stream Analytics Query Tester
- `Lets you perform query testing without creating a stream analytics job first`

### AI + machine learning
#### Azure AI Developer
- `Can perform all actions within an Azure AI resource besides managing the resource itself.`
#### Azure AI Enterprise Network Connection Approver
- `Can approve private endpoint connections to Azure AI common dependency resources`
#### Azure AI Inference Deployment Operator
- `Can perform all actions required to create a resource deployment within a resource group.`
#### AzureML Compute Operator
- `Can access and perform CRUD operations on Machine Learning Services managed compute resources (including Notebook VMs).`
#### AzureML Data Scientist
- `Can perform all actions within an Azure Machine Learning workspace, except for creating or deleting compute resources and modifying the workspace itself.`
#### Cognitive Services Contributor
- `Lets you create, read, update, delete and manage keys of Cognitive Services.`
#### Cognitive Services Custom Vision Contributor
- `Full access to the project, including the ability to view, create, edit, or delete projects.`
#### Cognitive Services Custom Vision Deployment
- `Publish, unpublish or export models. Deployment can view the project but can't update.`
#### Cognitive Services Custom Vision Labeler
- `View, edit training images and create, add, remove, or delete the image tags. Labelers can view the project but can't update anything other than training images and tags.`
#### Cognitive Services Custom Vision Reader
- `Read-only actions in the project. Readers can't create or update the project.`
#### Cognitive Services Custom Vision Trainer
- `View, edit projects and train the models, including the ability to publish, unpublish, export the models. Trainers can't create or delete the project.`
#### Cognitive Services Data Reader (Preview)
- `Lets you read Cognitive Services data.`
#### Cognitive Services Face Recognizer
- `Lets you perform detect, verify, identify, group, and find similar operations on Face API. This role does not allow create or delete operations, which makes it well suited for endpoints that only need inferencing capabilities, following 'least privilege' best practices.`
#### Cognitive Services Metrics Advisor Administrator
- `Full access to the project, including the system level configuration.`
#### Cognitive Services OpenAI Contributor
- `Full access including the ability to fine-tune, deploy and generate text`
#### Cognitive Services OpenAI User
- `Read access to view files, models, deployments. The ability to create completion and embedding calls.`
#### Cognitive Services QnA Maker Editor
- `Let's you create, edit, import and export a KB. You cannot publish or delete a KB.`
#### Cognitive Services QnA Maker Reader
- `Let's you read and test a KB only.`
#### Cognitive Services Usages Reader
- `Minimal permission to view Cognitive Services usages.`
#### Cognitive Services User
- `Lets you read and list keys of Cognitive Services.`
#### Search Index Data Contributor
- `Grants full access to Azure Cognitive Search index data.`
#### Search Index Data Reader
- `Grants read access to Azure Cognitive Search index data.`
#### Search Service Contributor
- `Lets you manage Search services, but not access to them.`

### Internet of Things
#### Azure Digital Twins Data Owner
- `Full access role for Digital Twins data-plane`
#### Azure Digital Twins Data Reader
- `Read-only role for Digital Twins data-plane properties`
#### Device Update Administrator
- `Gives you full access to management and content operations`
#### Device Update Content Administrator
- `Gives you full access to content operations`
#### Device Update Content Reader
- `Gives you read access to content operations, but does not allow making changes`
#### Device Update Deployments Administrator
- `Gives you full access to management operations`
#### Device Update Deployments Reader
- `Gives you read access to management operations, but does not allow making changes`
#### Device Update Reader
- `Gives you read access to management and content operations, but does not allow making changes`
#### IoT Hub Data Contributor
- `Allows for full access to IoT Hub data plane operations.`
#### IoT Hub Data Reader
- `Allows for full read access to IoT Hub data-plane properties`
#### IoT Hub Registry Contributor
- `Allows for full access to IoT Hub device registry.`
#### IoT Hub Twin Contributor
- `Allows for read and write access to all IoT Hub device and module twins.`

### Mixed reality
#### Remote Rendering Administrator
- `Provides user with conversion, manage session, rendering and diagnostics capabilities for Azure Remote Rendering`
#### Remote Rendering Client
- `Provides user with manage session, rendering and diagnostics capabilities for Azure Remote Rendering.`
#### Spatial Anchors Account Contributor
- `Lets you manage spatial anchors in your account, but not delete them`
#### Spatial Anchors Account Owner
- `Lets you manage spatial anchors in your account, including deleting them`
#### Spatial Anchors Account Reader
- `Lets you locate and read properties of spatial anchors in your account`

### Integration
#### App Configuration Data Owner
- `Allows full access to App Configuration data.`
#### App Configuration Data Reader
- `Allows read access to App Configuration data.`
#### Azure API Center Compliance Manager
- `Allows managing API compliance in Azure API Center service.`
#### Azure API Center Data Reader
- `Allows for access to Azure API Center data plane read operations.`
#### Azure API Center Service Contributor
- `Allows managing Azure API Center service.`
#### Azure API Center Service Reader
- `Allows read-only access to Azure API Center service.`
#### Azure Relay Listener
- `Allows for listen access to Azure Relay resources.`
#### Azure Relay Owner
- `Allows for full access to Azure Relay resources.`
#### Azure Relay Sender
- `Allows for send access to Azure Relay resources.`
#### Azure Service Bus Data Owner
- `Allows for full access to Azure Service Bus resources.`
#### Azure Service Bus Data Receiver
- `Allows for receive access to Azure Service Bus resources.`
#### Azure Service Bus Data Sender
- `Allows for send access to Azure Service Bus resources.`
#### BizTalk Contributor
- `Lets you manage BizTalk services, but not access to them.`
#### EventGrid Contributor
- `Lets you manage EventGrid operations.`
#### EventGrid Data Sender
- `Allows send access to event grid events.`
#### EventGrid EventSubscription Contributor
- `Lets you manage EventGrid event subscription operations.`
#### EventGrid EventSubscription Reader
- `Lets you read EventGrid event subscriptions.`
#### FHIR Data Contributor
- `Role allows user or principal full access to FHIR Data`
#### FHIR Data Exporter
- `Role allows user or principal to read and export FHIR Data`
#### FHIR Data Importer
- `Role allows user or principal to read and import FHIR Data`
#### FHIR Data Reader
- `Role allows user or principal to read FHIR Data`
#### FHIR Data Writer
- `Role allows user or principal to read and write FHIR Data`
#### Integration Service Environment Contributor
- `Lets you manage integration service environments, but not access to them.`
#### Integration Service Environment Developer
- `Allows developers to create and update workflows, integration accounts and API connections in integration service environments.`
#### Intelligent Systems Account Contributor
- `Lets you manage Intelligent Systems accounts, but not access to them.`
#### Logic App Contributor
- `Lets you manage logic apps, but not change access to them.`
#### Logic App Operator
- `Lets you read, enable, and disable logic apps, but not edit or update them.`
#### Logic Apps Standard Contributor (Preview)
- `You can manage all aspects of a Standard logic app and workflows. You can't change access or ownership.`
#### Logic Apps Standard Developer (Preview)
- `You can create and edit workflows, connections, and settings for a Standard logic app. You can't make changes outside the workflow scope.`
#### Logic Apps Standard Operator (Preview)
- `You can enable and disable the logic app, resubmit workflow runs, as well as create connections. You can't edit workflows or settings.`
#### Logic Apps Standard Reader (Preview)
- `You have read-only access to all resources in a Standard logic app and workflows, including the workflow runs and their history.`
#### Scheduler Job Collections Contributor
- `Lets you manage Scheduler job collections, but not access to them.`
#### Services Hub Operator
- `Services Hub Operator allows you to perform all read, write, and deletion operations related to Services Hub Connectors.`

### Identity
#### Domain Services Contributor
- `Can manage Azure AD Domain Services and related network configurations`
#### Domain Services Reader
- `Can view Azure AD Domain Services and related network configurations`
#### Managed Identity Contributor
- `Create, Read, Update, and Delete User Assigned Identity`
#### Managed Identity Operator
- `Read and Assign User Assigned Identity`

### Security
#### App Compliance Automation Administrator
- `Create, read, download, modify and delete reports objects and related other resource objects.`
#### App Compliance Automation Reader
- `Read, download the reports objects and related other resource objects.`
#### Attestation Contributor
- `Can read write or delete the attestation provider instance`
#### Attestation Reader
- `Can read the attestation provider properties`
#### Key Vault Administrator
- `Perform all data plane operations on a key vault and all objects in it, including certificates, keys, and secrets. Cannot manage key vault resources or manage role assignments. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Certificate User
- `Read certificate contents. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Certificates Officer
- `Perform any action on the certificates of a key vault, except manage permissions. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Contributor
- `Manage key vaults, but does not allow you to assign roles in Azure RBAC, and does not allow you to access secrets, keys, or certificates.`
#### Key Vault Crypto Officer
- `Perform any action on the keys of a key vault, except manage permissions. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Crypto Service Encryption User
- `Read metadata of keys and perform wrap/unwrap operations. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Crypto Service Release User
- `Release keys. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Crypto User
- `Perform cryptographic operations using keys. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Data Access Administrator
- `Manage access to Azure Key Vault by adding or removing role assignments for the Key Vault Administrator, Key Vault Certificates Officer, Key Vault Crypto Officer, Key Vault Crypto Service Encryption User, Key Vault Crypto User, Key Vault Reader, Key Vault Secrets Officer, or Key Vault Secrets User roles. Includes an ABAC condition to constrain role assignments.`
#### Key Vault Reader
- `Read metadata of key vaults and its certificates, keys, and secrets. Cannot read sensitive values such as secret contents or key material. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Secrets Officer
- `Perform any action on the secrets of a key vault, except manage permissions. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Key Vault Secrets User
- `Read secret contents. Only works for key vaults that use the 'Azure role-based access control' permission model.`
#### Managed HSM contributor
- `Lets you manage managed HSM pools, but not access to them.`
#### Microsoft Sentinel Automation Contributor
- `Microsoft Sentinel Automation Contributor`
#### Microsoft Sentinel Contributor
- `Microsoft Sentinel Contributor`
#### Microsoft Sentinel Playbook Operator
- `Microsoft Sentinel Playbook Operator`
#### Microsoft Sentinel Reader
- `Microsoft Sentinel Reader`
#### Microsoft Sentinel Responder
- `Microsoft Sentinel Responder`
#### Security Admin
- `View and update permissions for Microsoft Defender for Cloud. Same permissions as the Security Reader role and can also update the security policy and dismiss alerts and recommendations.`
#### Security Assessment Contributor
- `Lets you push assessments to Microsoft Defender for Cloud`
#### Security Manager (Legacy)
- `This is a legacy role. Please use Security Admin instead.`
#### Security Reader
- `View permissions for Microsoft Defender for Cloud. Can view recommendations, alerts, a security policy, and security states, but cannot make changes.`

### DevOps
#### DevTest Labs User
- `Lets you connect, start, restart, and shutdown your virtual machines in your Azure DevTest Labs.`
#### Lab Assistant
- `Enables you to view an existing lab, perform actions on the lab VMs and send invitations to the lab.`
#### Lab Contributor
- `Applied at lab level, enables you to manage the lab. Applied at a resource group, enables you to create and manage labs.`
#### Lab Creator
- `Lets you create new labs under your Azure Lab Accounts.`
#### Lab Operator
- `Gives you limited ability to manage existing labs.`
#### Lab Services Contributor
- `Enables you to fully control all Lab Services scenarios in the resource group.`
#### Lab Services Reader
- `Enables you to view, but not change, all lab plans and lab resources.`
#### Load Test Contributor
- `View, create, update, delete and execute load tests. View and list load test resources but can not make any changes.`
#### Load Test Owner
- `Execute all operations on load test resources and load tests`
#### Load Test Reader
- `View and list all load tests and load test resources but can not make any changes`

### Monitor
#### Application Insights Component Contributor
- `Can manage Application Insights components`
#### Application Insights Snapshot Debugger
- `Gives user permission to view and download debug snapshots collected with the Application Insights Snapshot Debugger. Note that these permissions are not included in the Owner or Contributor roles. When giving users the Application Insights Snapshot Debugger role, you must grant the role directly to the user. The role is not recognized when it is added to a custom role.`
#### Grafana Admin
- `View and edit a Grafana instance, including its dashboards and alerts.`
#### Grafana Editor
- `View a Grafana instance, including its dashboards and alerts.`
#### Grafana Viewer
- `Can read all monitoring data and edit monitoring settings. See also Get started with roles, permissions, and security with Azure Monitor.`
#### Monitoring Contributor
- `Can read all monitoring data and edit monitoring settings. See also Get started with roles, permissions, and security with Azure Monitor.`
#### Monitoring Metrics Publisher
- `Enables publishing metrics against Azure resources`
#### Monitoring Reader
- `Can read all monitoring data (metrics, logs, etc.). See also Get started with roles, permissions, and security with Azure Monitor.`
#### Workbook Contributor
- `Can save shared workbooks.`
#### Workbook Reader
- `Can read workbooks.`

### Management and governance
#### Automation Contributor
- `Manage Azure Automation resources and other resources using Azure Automation.`
#### Automation Job Operator
- `Create and Manage Jobs using Automation Runbooks.`
#### Automation Operator
- `Automation Operators are able to start, stop, suspend, and resume jobs`
#### Automation Runbook Operator
- `Read Runbook properties - to be able to create Jobs of the runbook.`
#### Azure Connected Machine Onboarding
- `Can onboard Azure Connected Machines.`
#### Azure Connected Machine Resource Administrator
- `Can read, write, delete and re-onboard Azure Connected Machines.`
#### Azure Connected Machine Resource Manager
- `Custom Role for AzureStackHCI RP to manage hybrid compute machines and hybrid connectivity endpoints in a resource group`
#### Billing Reader
- `Allows read access to billing data`
#### Blueprint Contributor
- `Can manage blueprint definitions, but not assign them.`
#### Blueprint Operator
- `Can assign existing published blueprints, but cannot create new blueprints. Note that this only works if the assignment is done with a user-assigned managed identity.`
#### Carbon Optimization Reader
- `Allow read access to Azure Carbon Optimization data`
#### Cost Management Contributor
- `Can view costs and manage cost configuration (e.g. budgets, exports)`
#### Cost Management Reader
- `Can view cost data and configuration (e.g. budgets, exports)`
#### Hierarchy Settings Administrator
- `Allows users to edit and delete Hierarchy Settings`
#### Managed Application Contributor Role
- `Allows for creating managed application resources.`
#### Managed Application Operator Role
- `Lets you read and perform actions on Managed Application resources`
#### Managed Applications Reader
- `Lets you read resources in a managed app and request JIT access.`
#### Managed Services Registration assignment Delete Role
- `Managed Services Registration Assignment Delete Role allows the managing tenant users to delete the registration assignment assigned to their tenant.`
#### Management Group Contributor
- `Management Group Contributor Role`
#### Management Group Reader
- `Management Group Contributor Role`
#### New Relic APM Account Contributor
- `Lets you manage New Relic Application Performance Management accounts and applications, but not access to them.`
#### Policy Insights Data Writer (Preview)
- `Allows read access to resource policies and write access to resource component policy events.`
#### Quota Request Operator
- `Read and create quota requests, get quota request status, and create support tickets.`
#### Reservation Purchaser
- `Lets you purchase reservations`
#### Reservations Administrator
- `Lets one read and manage all the reservations in a tenant`
#### Reservations Reader
- `Lets one read all the reservations in a tenant`
#### Resource Policy Contributor
- `Users with rights to create/modify resource policy, create support ticket and read resources/hierarchy.`
#### Scheduled Patching Contributor
- `Provides access to manage maintenance configurations with maintenance scope InGuestPatch and corresponding configuration assignments`
#### Site Recovery Contributor
- `Lets you manage Site Recovery service except vault creation and role assignment`
#### Site Recovery Operator
- `Lets you failover and failback but not perform other Site Recovery management operations`
#### Site Recovery Reader
- `Lets you view Site Recovery status but not perform other management operations`
#### Support Request Contributor
- `Lets you create and manage Support requests`
#### Tag Contributor
- `Lets you manage tags on entities, without providing access to the entities themselves.`
#### Template Spec Contributor
- `Allows full access to Template Spec operations at the assigned scope.`
#### Template Spec Reader
- `Allows read access to Template Specs at the assigned scope.`

### Hybrid + multicloud
#### Azure Resource Bridge Deployment Role
- `Azure Resource Bridge Deployment Role`
#### Azure Stack HCI Administrator
- `Grants full access to the cluster and its resources, including the ability to register Azure Stack HCI and assign others as Azure Arc HCI VM Contributor and/or Azure Arc HCI VM Reader`
#### Azure Stack HCI Device Management Role
- `Microsoft.AzureStackHCI Device Management Role`
#### Azure Stack HCI VM Contributor
- `Grants permissions to perform all VM actions`
#### Azure Stack HCI VM Reader
- `Grants permissions to view VMs`
#### Azure Stack Registration Owner
- `Lets you manage Azure Stack registrations.`

## **Azure Custom Roles**
### CustomRole - ADF Operator - Sandbox
- `Custom role used for Azure Data Factories for administrators by running pipelines within ADF by a manual push instead of customizing - Sandbox`

### CustomRole - ADF Operator Cancel Pipeline - Sandbox
- `Custom role used for Azure Data Factories for administrators by cancelling pipelines within ADF by a manual push instead of customizing - Sandbox`

### CustomRole - ADF Repository Config - Sandbox
- `Custom Role used for Azure Data Factories v2 for configuration of repo by Pipelines - Sandbox`

### CustomRole - App Creator - Sandbox
- `Custom Role used for application owner creation and Resource Group creator / editor - Sandbox`

### CustomRole - App Service - Sandbox
- `Custom role used for the vendor to stop and (re)start app service - Sandbox`

### CustomRole - Auditing - Sandbox
- `Custom Role used for Auditing - Sandbox`

### CustomRole - Automation Account LimitedReader - Sandbox
- `Custom Role used for limited reader rights on automation accounts to get insight in update management - Sandbox`

### CustomRole - AzureML Data Scientist Reader - Sandbox
- `Custom Role used for an Azure Machine Learning(ML) workspace log reader - Sandbox`

### CustomRole - CustomContributorDev - Sandbox
- `A custom Contributor role for NS teams so they can manage IAM on their Azure resources - Sandbox`

### CustomRole - CustomOwnerDev - Sandbox
- `A custom owner role for NS teams so they can manage IAM on their Azure resources - Sandbox`

### CustomRole - CustomOwnerMC - Sandbox
- `A custom owner role for NS teams so they can manage resources except certain Subscription and VNET actions - Sandbox`

### CustomRole - Dashboard Contributor - Sandbox
- `Custom Role used for allowing modification in Dashboards - Sandbox`

### CustomRole - DevTestLabs Administrator - Sandbox
- `Custom Role used for cleaning up labmachines of former employees in both public and private environments - Sandbox`

### CustomRole - Image Builder Service Image Creation - Sandbox
- `Custom role used for AVD to add/remove/change Compute images from the Gallery - Sandbox`

### CustomRole - MG KeyVault Purge - Sandbox
- `Custom Role used for Purge Soft Deleted Key Vault - Sandbox`

### CustomRole - PostgresSQL queryTexts - Sandbox
- `Custom Role used for giving dev teams permissions to use Query Performance Insight of postgresql databases - Sandbox`

### CustomRole - Private Link Write Private Endpoint - Sandbox
- `Custom Role used by Managed Identity from deployifnotexists policy to alter Private endpoint - Sandbox`

### CustomRole - Resource Lock - Sandbox
- `Custom Role used for reading/adding/deletion of locks on resources - Sandbox`

### CustomRole - Security Reader Plus - Sandbox
- `Custom role that adds PolicyInsights read to the existing Security Reader - Sandbox`

### CustomRole - Storage Key List - Sandbox
- `Custom Role used for listing storage account keys - Sandbox`

### CustomRole - Virtual Machine Operator - Sandbox
- `Custom Role used for starting, stopping and deallocating Virtual Machines - Sandbox`

### CustomRole - Virtual Network Reader - Sandbox
- `Custom role used for read permissions on VNET - Sandbox`

### CustomRole - VNet Subnet Join - Sandbox
- `Custom Role used for joining a service to an Virtual Network or Subnet - Sandbox`

### CustomRole - Write Role Assignments - Sandbox
- `Custom Role used for Creating a role assignment - Sandbox`

