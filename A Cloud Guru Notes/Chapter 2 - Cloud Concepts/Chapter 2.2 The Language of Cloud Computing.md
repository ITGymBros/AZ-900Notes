
### Terms
* High availability
	* Traditional:
		* You own the hardware
		* You have physical access
		* You can't "just add servers"
	* Cloud:
		* You don't own the hardware
		* Add more servers with a click
		* If hardware fails, replace it instantly
		* Use clusters to ensure high availability
* Scalability
	* Automatically adjust resources to meet demand
		* Example: Increase the number of VMs to handle peak traffic
	* Don't overpay for services
		* Automatically reduce resources when demand drops
	* Horizontal vs. Vertical Scaling
		* Horizontal = Adding additional VMs/containers
			* "Scaling out"
		* Vertical = Increasing power (e.g., CPU/RAM) of existing VMs
			* "Scaling up"
		* 'Typical' cloud model = Horizontal scaling
* Predictability
	* Predictable Performance and Costs
		* Performance
			* Consistent experience for customers regardless of traffic
			* Autoscaling, load balancing, and high availability provide a consistent experience
		* Costs
			* No unexpected surprises
			* Track and forecast resource usage (costs) in real time
			* Analytics provide patterns/trends to optimize usage
* Reliability
	* Resilience
		* The ability of a system to recover from failures and continue to function
	* Deploy in Multiple Locations
		* Global-scale computing
		* Protects against regional failure/disaster
	* No Single Point of Failure
		* Resources in multiple locations
		* If one computer goes down, others pick up the load
* Security
	* Full control of the security of your cloud environment. Patches, maintenance, network control, and more.
* Governance
	* Standardize environments
	* Regulatory requirements
	* Audit for compliance
* Manageability
	* Management of the cloud:
		* Autoscaling
		* Monitoring
		* Template-based deployments
	* Management in the cloud:
		* Portal
		* CLI
		* APIs

## Exam Tips

#### Cloud computing has terms that are specific and critical to understanding it
* High availability means systems are always available -- even automatically.
* Reliability describes how Azure can tolerate failures or even disasters.
* Scalability refers to scaling out or scaling up while automatically providing resources as needed.
* Predictability is knowing your application will always perform as expected and knowing what it will cost.
* Security is having full control of  your cloud security posture.
* Governance is standardizing cloud deployments to meet requirements/company standards.
* Manageability is management of cloud resources and how we interact with them.