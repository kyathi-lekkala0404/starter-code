Analyze, choose, and justify the appropriate resource option for deploying the app
Virtual Machine (VM)

Cost:
A Virtual Machine can be more expensive because it runs continuously and requires paying for compute resources even when the application is idle.

Scalability:
Scaling a VM requires manual configuration such as creating additional VMs and setting up load balancing.

Availability:
Availability must be managed manually with monitoring, backups, and failover configurations.

Workflow:
Deployment requires manual setup of the server environment, installing dependencies, and maintaining the system.

App Service

Cost:
Azure App Service provides low-cost plans and even free tiers suitable for small web applications.

Scalability:
App Service supports easy scaling directly from the Azure portal.

Availability:
It is a managed service, so Azure handles infrastructure maintenance and reliability.

Workflow:
Deployment is easier because it integrates with GitHub and supports automatic deployment.

Chosen Solution

App Service was chosen because it simplifies deployment and reduces the need to manage infrastructure. It allows easy configuration, automated deployment, and built-in monitoring, which makes it ideal for this CMS application.

Assess app changes that would change your decision

If the application required more control over the operating system, custom server configurations, or complex infrastructure management, a Virtual Machine would be more suitable. In such cases, a VM would provide greater flexibility and control over the environment.
