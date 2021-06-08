###Comparision between App Service and VM

There are two deployment methods we can choose for our web application.The Azure Virtual Machines and the Azure App Service.

Azure Virtual Machines provides the developers virtual machines in the cloud and gives them complete control over application management and deployment. Compared with On-Premises deployment, the developers don't need to purchase and maintain hardware. Therefore, it costs less to build the application. Multiple VMs can be grouped to provide high availability, scalability, and redundancy. In contrast, this architecture can be more time-consuming for the developer to set everything properly.

Azure App Service is an HTTP-based service for hosting web applications. This deployment method is even more cost-effective compared with the Azure Virtual Machines. It also provides the developers a high availability, auto-scaling environment. Developers can scale their applications vertically or horizontally by changing the App Service pricing tier and the number of Virtual Machine instances. The workflow is relatively simple than the Azure Virtual Machines but the developers have limited access to the host server and the hardware.

I think using the Azure App Service to deploy our application is a better choice for this project. The main reason is the size of our application is not quite complicated. We won't concentrate too much on the performance but the cost. The Azure App Service satisfies our requirements very well. Therefore, we choose the Azure App Service for deployment

###[Web App portal](https://bxwebapp.azurewebsites.net)
###[Screenshots](https://github.com/brianx0215/nd081-c1-provisioning-microsoft-azure-vms-project-starter/tree/master/images)