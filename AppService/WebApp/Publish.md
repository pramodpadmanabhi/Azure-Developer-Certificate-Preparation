# Configure Workloads in Visual Studio

###### Workloads are pre-configured build of tools that are grouped to enable developers to build,create solutions
###### To Publish app in VS Azure Development Workload is required - installs latest Azure SDK for Dot NET and resources which can be viewed in VS Cloud Explorer

#### Examples

* ASP.NET & Web Development
* Azure Development

# App Service

* App Service is a platform for hosting application 
* Ideal for Websites which does not have tight control over infrastructure

# App Service Plan - Defines compute resources  
* no of VM Instances
* size of VM Instances
* Region ... includes selecting geographical location where plan will be hosted
* Pricing Tier
      1) Shared Compute -> Shared & free, runs app on same Azure VM with other customers <br/>
      2) Dedicated Compute    1. apps on the same service plan share same compute resources <br/>
                              2 .Basic <br/>
                              3 .Standard- prduction ready apps <br/>
                              4 .Premium - high capacity web apps <br/>
      3) Isolated Resources -> runs on dedicated Azure Virtual Network <br/>
                              1 .app is resource intensive <br/>
                              2 .needs resources on different geographical locations <br/>
                              3 .scale independently from other apps <br/>
      

