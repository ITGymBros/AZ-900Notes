
### Infrastructure-as-a-Service (IaaS)
* Infrastructure = actual servers
* Scaling is fast
* No ownership of hardware
IaaS offers VMs & Servers, Storage, Networking components, firewall and the physical hardware everything runs on.

### Platform-as-a-Service (PaaS)
* Superset of IaaS
	* Offers all that IaaS
		* Also offers Middleware, development tools, business intelligent, services, database management systems, and more.
* PaaS supports web application life cycle
* Avoids software license hell

### Software-as-a-Service (SaaS)
* Providing a managed service
	* Provides all that PaaS and IaaS provides
		* Also offers apps/software
* Pay an access fee to use
* No maintenance and latest features

### Serverless
* There are servers, this just means you don't have to manage any servers. You are using someone else's servers
* Azure Functions is the best know serverless service
* Extreme PaaS

## Identifying Cloud Service Models
* IaaS
	* Organization has complete control of the infrastructure
	* Dynamic and flexible. You can do almost anything.
	* Cost varies depending on consumption
	* Services are highly scalable
	* Multiple users share a single piece of hardware
	* Examples:
		* VM
		* VNet
		* Storage
* PaaS
	* Resources are virtualized and can easily be scaled up or down as needed
	* Services often assist with the development, testing, and deployment of apps
	* Multi-user access via the same development application
	* Integrates web services and databases
	* Examples:
		* App Services
		* Azure CDN
		* Cosmos DB
* SaaS
	* Managed from a central location
	* Hosted on a remote server
	* Accessible over the internet
	* Users not responsible for hardware or software updates
	* Rate limiting/QoS
	* Examples:
		* Microsoft 365

### Exam Tips
Service is the core of Azure, and there are three main ways to go about it.
* IaaS provides servers, storage and networking as a service
* PaaS is a superset of IaaS and also includes middleware, such as database management tools
* SaaS is when service is built on top of PaaS, like Office 365
* Serverless means that you don't have any servers. Let's a single function be hosted, deployed, run and managed on its own