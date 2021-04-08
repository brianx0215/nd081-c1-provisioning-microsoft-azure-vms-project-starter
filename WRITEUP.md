###Comparision between App Service and VM

There are two deployment methods we can use for our web application. One is VM, and the other is App Service. In this project, we decide to move forward to App Service.

First of all, the system is relatively small. It is only for demonstration and verifying purposes. We won't concentrate too much on the performance but on the cost. Therefore, we don't need a very powerful infrastructure to hold our application. Compare VM with App Service, VM provides a relatively low cost, which perfectly matches up against our goal. 

Next, both VM and App Service give the application great availability. Our application will run steadily without bothering too much on disaster tolerance. 

About the scalability, both methods have a certain amount of scalability. VM option may give the application more scalability by using the load balancer. While the option also increases the complexity when we are configuring the network. In this project, we don't have a massive burden on computation. So, App Service is enough for us to finish the project.

App Service helps us simplify many steps during the entire workflow and focus less on the deployment pipeline. We can construct our application quicker and use less technology stack of the operating system compared with VM.

In conclusion, App Service is a better choice for this project. While if the system's size expands dramatically in the future, we may consider the VM option.

###[Web App portal](https://bxwebapp.azurewebsites.net)
###[Screenshots](https://github.com/brianx0215/nd081-c1-provisioning-microsoft-azure-vms-project-starter/tree/master/images)