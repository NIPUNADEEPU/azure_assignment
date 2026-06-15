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
