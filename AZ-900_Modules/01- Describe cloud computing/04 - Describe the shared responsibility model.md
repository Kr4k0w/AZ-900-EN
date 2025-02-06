## Describe the shared responsibility model

Shared responsability model in cloud computing divides responsabilities between provider and consumer. In a traditional corporate datacenter, the company handles everything, from physical space and security to maintaining infrastructure and software. Below we have these responsabilities:

- **Cloud Provider Responsabilities:** Physical security, power, cooling and network connectivity
- **Consumer/Customer Responsabilities:** Data and information storage, access security.
- **Situation-Dependent Responsabilities:** For cloud services like SQL databases, the cloud provider maintains the database, while the customer is responsible for the data

The extent of shared responsibilities varies based on the type of cloud service:
- **IaaS (Infrastructure as a Service)**: Most responsibilities are on the consumer.
- **PaaS (Platform as a Service)**: Responsibilities are more evenly shared.
- **SaaS (Software as a Service)**: Most responsibilities are on the cloud provider.

Ultimately, the model shifts responsibilities from the consumer (as in on-premises datacenters) to a shared approach with cloud providers.

![[Pasted image 20250206000043.png]]

During the use of an cloud provider, you'll always be responsible for:
- Information and data stored in the cloud
- Devices that are allowed to connect to your cloud (cell phones, computers, and so on)
- Identities and accounts of people, services, and devices within your organization

Provider is responsible for:
- Physical datacenter
- Physical network
- Physical hosts

Your service model will determine responsibility for things like:

- Operating systems
- Network controls
- Applications
- Identity and infrastructure