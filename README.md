# IaC-deployment-project
Before I started this project I assumed that it would be a simple task of creating code to auto-deploy T-Shirt sized VM’s in any “Cloud”, with the caveat that it must not cost any money. Well that threw me for a loop, as I have no cloud account (this would cost money), where I am currently employed we have just started looking at the value of moving to the “Cloud”, thus no access. So I went about this project trying to understand more than just writing a script. This would involve more of the where, why and how of this project scope.

Findings:
First I looked at the theory behind IaC (as being cubed up all day has its limitations). ITIL was one of the first thoughts that came to mind. How to accomplish the project by following some basic ITIL foundations. This project would be creating a uniform way of building and breaking down said VM’s in a uniform way. The thought process ehind this is removing the risk of making mistakes manually creating VM’s on a needed basis. Also capacity management can be effected by always manually creating VM’s. By setting up and following SLA's for autodeployment you will be ensuring current and future business requirements are met in a cost effective manner. 

Advantage of Dockers(Containers):

They have some significant advantages over VMs in the Infrastructure as Code model:

•	Containers are much faster to start than VMs. Container starts in seconds, while a VM takes minutes. IThis is an important aspect for the sevice you are trying to provide.

•	Containers can better utilize compute resources. Most computer resources of a VM running an application are underutilized. Launching multiple instances of the same application on one VM has a lot of difficulties: different application versions may need different versions of dependent libraries, init scripts require special configuration. With containers, running multiple instances of the same application on the same machine is easy and doesn't require any system configuration.

•	Containers are more lightweight than VMs. Container images are much smaller than machine images, because they don't need a full operating system in order to run. In fact, a container image can include just a single binary and take just a few MBs of your disk space. This means that we need less space for storing the images and the process of distributing images goes faster.
