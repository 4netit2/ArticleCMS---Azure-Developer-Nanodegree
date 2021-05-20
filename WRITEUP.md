# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
I choose App service because:
- development in app service is simpler than VM
- azure virtual machines are more expensive than app service
- even if it has limitations on the hardware side, it was enough for this project

For example:
 In Webapp a have the posibility to chose FreePlan which include:
    10 Web/mobile/API apps
    Disk space 1GB
    It doesn't include Autoscale/ Custom domain/ Virtual Network Conectivity, but for this particular project it's not necesarry.
    If I had chosen VM with the option B1s I would have availablea 1CPU/1GB RAM and 4GB temporary storage. But the price would be aproximatively 0.0104/hour.

If I needed more resources and the autoscale option, a dedicated server, more instances and more disk space, I would probably choose a virtual machine because the calculated cost is better compared to webapps.
Basically I would have chosen VM if it had been necessary to have more control over the environment or over the OS or installed software on the server. But also due to the fact that I have to pay for the service plan even if the service is not started.
