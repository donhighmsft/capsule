# Use cases for Capsule
Using Capsule, a cluster admin can implement complex multi-tenant scenarios for both public and private deployments. Here a list of common scenarios addressed by Capsule.

# Container as a Service (CaaS)
***Acme Corp***, our sample organization, built a Container as a Service platform (CaaS), based on Kubernetes to serve multiple lines of business. Each line of business, has its own team of engineers that are responsible for development, deployment, and operating their digital products.

To simplify the usage of Capsule in this scenario, we'll work with the following actors:

* ***Bill***:
  he is the cluster administrator from the operations department of Acme Corp. and he is in charge of administration and maintains the CaaS platform.

* ***Alice***:
  she works as the IT Project Leader in the Oil & Gas Business Units. These are two new lines of business at Acme Corp. Alice is responsible for all the strategic IT projects in the two LOB's. She also is responsible for a team made of different job responsibilities (developers, administrators, SRE engineers, etc.) working in separate departments.
  
* ***Joe***:
  he works at Acme Corp, as a lead developer of a distributed team in Alice's organization. Joe is responsible for developing a mission-critical project in the Oil market.

* ***Bob***:
  he is the head of Engineering for the Water Business Unit, the main and historical line of business at Acme Corp. He is responsible for development, deployment, and operating multiple digital products in production for a large set of customers.

Bill, at Acme Corp. can use Capsule to address any of the following scenarios:

* [Onboard a new Tenant](./onboarding.md)
* [Create Namespaces](./create-namespaces.md)
* [Assign Permissions](./permissions.md)
* [Enforce Resources Quotas and Limits](./resources-quota-limits.md)
* [Assign specific Node Pools](./nodes-pool.md)
* [Assign Ingress Classes](./ingress-classes.md)
* [Assign Ingress Hostnames](./ingress-hostnames.md)
* [Assign Storage Classes](./storage-classes.md)
* [Assign Network Policies](./network-policies.md)
* [Assign Trusted Images Registries](./images-registries.md)
* [Assign Pod Security Policies](./pod-security-policies.md)
* [Create Custom Resources](./custom-resources.md)
* [Taint Namespaces](./taint-namespaces.md)
* [Assign multiple Tenants to an owner](./multiple-tenants.md)

> NB: as we improve Capsule, more use cases about multi-tenancy and cluster governance will be covered.


# What’s next
Now let's see how the cluster admin onboards a new tenant. [Onboard a new tenant](./onboarding.md).
