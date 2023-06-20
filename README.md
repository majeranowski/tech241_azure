# What is cloud?

Cloud computing, often referred to as simply "the cloud," is a model for delivering computing resources over the internet on-demand. Instead of relying on local servers or personal computers to store and process data, cloud computing allows users to access and use shared computing resources provided by a third-party provider.
On-premises: office or branch
in the cloud: Microsoft-owned (Azure) internet
In cloud means resources are delivered as a service On-demand on the internet
Data centres in cloud have own water supplies, power generators, own networking. They are resilient and more reliable. Data centres from cloud provider can be in some distance from each other.

### Benefits of using clouds:
* Protection and security
* Huge capacity and storage (enormous computing power) but still economic
* Reliable, they can keep power by generators and batteries powers but still sustainable.

Renting a dedicated server

* Public cloud –> multiple occupant cloud – sharing a server, not dedicated one. We don’t know who else running VM on that server. 
* Private cloud -> Single tenant cloud – Cloud infrastructure dedicated to a private company. Can be owned or hoster by 3rd party company.  Can be used when there is no internet access.
* Hybrid cloud -> Combination of on-premises and on the cloud mixed together. Database run on premises and web app running in the cloud (Azure). Web app connected to a database that is on-prem.

* Multi-cloud -> Different cloud providers for example use of Azure and AWS.

Types of Cloud Services: IaaS, PaaS, SaaS

On premises you are in control and have to manage everything:

* IaaS – Infrastructure as a Service
* PaaS – Platform as a Service
* SaaS – Software as a Service

 ![Services](shared-responsibility.png)

SaaS – e.g Office 365, Dropbox etc.
PaaS – You designed web application and you don’t have to worry about anything else but deploying your code.
IaaS – VM, running a virtual machine

### Advantages and disadvantages of cloud:
* Advantages:
-	Scalability – if you need more computing resources it can almost automatically happen. Rapid adaptations
-	Cost Efficiency
-	Accessibility and Mobility – can be access from anywhere
-	Automatic Updates and Maintenance
-	Data Backup
* Disadvantages:
-	Internet Dependency
-	Moving from one provider to another
-	Security concerns
-	Limited control 
* What are the disadvantages of using hybrid or multi-cloud:
-	Complexity - You need to have an expert in every cloud service you use
-	Cost – quite expensive 
-	Data Security and Compliance
-	A lot of maintenance

On-prem or cloud, what is cheaper?
Probably cloud because you pay for what you use and you can predict the costs.

Probably AWS


Azure:

 ![Services](cloud-advantage-service-credit.png)

If they don’t deliver you can get a credit back. It is almost 100% of what are you paying

Report of cost efficiency from Azure calculator:

  ![Services](cloud-advantage-tco-comparison.png)

Big 3: AWS, Azure (Microsoft),  Google

 ![comparison](cloud-providers-market-share-2022.png)

Microsoft is doing good because of the integration. A lot of businesses use it. They own a whole ecosystem. 

### What is Azure?

![scope](scope-levels.png)
 
Above Management groups – root (in Azure / Azure Active Directory Tenet)

Management Group – helps you to manage access, policy and compliance of many subscriptions. way to manage your organisation. For a particular department in a company you might want them to use only specific part of VM. It will help you with cost. You can have 6 levels of it. Management groups of management groups etc..

Subscription – separate payment account, way of separating billing (e.g. sales team in organisation or marketing team). Pay as you go Subscription, Student Subscription in Azure. There are limits and quoters for subscriptions. A subscription can have max of some number of Resource groups.

Resource groups – like containers. You can’t have resource group inside resource group. AWS you don’t have to use Resource groups. In Azure you have to. 

Resources 


