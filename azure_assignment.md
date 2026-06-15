1. What are App Services and what are the different types of options available in App Services?
Azure app service is a platform that lets the user run web applications,mobile backends, and RESTful APIs without worrying about managing the underlying infrastructure. 
Types of Azure App Services:
Webapps - Used to host websites and web applications
API Apps - used to build and host RESTful APIs.
Mobile Apps -  Provides backend services for mobile applications.

2. Explain Cloud Availability Set and Availability Zones
Cloud Availability set - A feature in Azure that protects applications from hardware failures and maintenance events. Azure distributes virtual machines across multiple fault domains and update domains. 
- Improves application uptime
- Protects against hardware failures
- Minimizes downtime during planned maintenance

Avaliability zone - Physically separate datacenters within an Azure region. Each zone has independent power, cooling and networking.
- It has higher fault tolerance
- Protection against datacenter level failures
- Improved disaster recovery

3. What are the responsibilities of users when it comes to different cloud offerings like Infrastructure as Service, Platform as Service and Function as Service and mention which Azure resource falls under each option.
Infrastructure as a service(IAAS): In IAAS, Azure manages the physical infrastructure while users manage the operating system, applications, networking configurations and security settings.
examples:
- Azure Virtual Machines
- Azure Virtual Network
- Azure Load Balancer

Platform as a service(PAAS):In PAAS, Azure manages infrastructure, operating systems, and runtime environments. Users are responsible for application development, data and configuration.
examples:
- Azure App services 
- Azure SQL Database 
- Azure Database for MYSQL

Function as a service(FAAS): In FAAS, users only write and manage code functions while Azure manages everything else, including scaling and infrastructure.
examples:
- Azure functions

4.In a brief paragraph, explain networking options available in Azure mentioning each service discussed in the class.
Azure provides various networking services that enable secure communication between resources, users and applications.
Azure Virtual Network: Provides a private network environment for Azure resources.
Network Security Groups: Control inbound and outbound network traffic using security rules.
Azure Load Balancer:Distributes incoming traffic across multiple servers to improve availability and performance.
Azure VPN Gateway: Connects on-premises networks securely to Azure through encrypted VPN tunnels.
Azure Application Gateway:A web traffic load balancer that provides application level routing and web application firewall features.
Azure DNS: Provides domain name hosting and resolution services.
Azure ExpressRoute:Provides private, dedicated connectivity between on-premises infrastructure and Azure.

5.What are storage accounts and the different options available to access storage accounts.
A storage account is a container in Azure that provides a unique namespace to store and manage data services.
Types of storage services:
Blob storage: Stores unstructured data such as images, videos and documents.
File storage: Provides managed file shares accessible throught SMB protocols.
Queue storage: Stores messages for asynchronouss communication between applications.
Table storage: Stores structured NoSQL data.
Disk storage: Provides persistent storage for Azure Virtual Machines.
Access methods: Azure Portal, Azure storage Explorer, Azure CLI, Azure Powershell, REST APIs, SDKs, shared access signature(SAS), access keys, Azure Active Directory(Azure AD)

6.What are different options available to scale up and scale out Azure App Services.
Scale up(Vertical scaling): increases the resources available to an existing instance.
Examples: increse cpu power, increase RAM, move from basic plan to standard or premium plan
Advantages: better performance per instance and easy to implement

Scale out(Horizontal scaling): increases the number of applications instances.
Examples: add multiple instances of the application, configure automatic scaling based on CPU usage or traffic.
Advantages: improved availability, better handling of large traffic loads, supports automatic scaling.
