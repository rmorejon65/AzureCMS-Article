# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.
Azure App Service is a "Platform as a Service" offering. It is a fully managed environment. The cloud service provider (in this case Azure) manages the underlying infrastructure (i.e Servers, Networking, Storage and even Virtualization). They are also responsible for installing the operating system updates, critical patches, runtime or middleware components. We just manage the application that we are building and it's data. 


I choose App Service as my appropiate resource option for deploying the app for the following reasons:

1. As a developper this kind of deployment allows me to focus more on my applications than the underlying infrastructure.
2. It's the less expensive option.
3. It's a quicker way of deploying web applications, without actually worrying about the underlying responsibilities of creating and deploying the environment.
4. As the application doesn't have scope to expand for future.
5. It requires much less managerial efforts in comparison to Azure Virtual Machines.
6. The development of app is much simpler and faster.
7. It allows high availability and scaling.
8. Vertical and Horizontal Scaling


*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.
Virtual Machine  is an "Infrastructure as a Service".
1. The application needs to expand for future so as Azure App Service have constraints in comparison to Azure VMs in terms of scalability we should evaluate changing to VM.
2. We need to change the programming language and reimplement the application on one programming language not supported by the App Service.
3. We need higher availability and scaling.
4. We need more control over the environment.
5. We need full access to the underlying OS.
6. We need to have complete control over our development, test and staging environments. So, basically, the application that we are developing has strong dependencies on the server and we want to take infrastructure related things like networking, load-balancer, scale-out and scale-in, web server management, and so on into our own hands.
7. We need to migrate legacy apps to the cloud, but since this is a legacy app with it's own custom middleware and runtime requirements, it does not have an equivalent platform as a service offering.


*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 