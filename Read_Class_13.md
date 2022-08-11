# Virtualization in the Amazon EC2 Cloud

“Virtualization is the creation of a virtual, rather than actual, version of something.”

The concept dates back to the 60s, but was popularized by VMWare in 1999. 

### Virtualization and the Amazon IaaS Cloud Service Model

Iaas is characterized by delivering virtualized computer infrastructure in the form of a service. A good example is EC2 or Amazon Elastic Compute Cloud.  This is essentially an IaaS service that provides virtual servers based on the Xen hypervisor. A hypervisor acts as a virtual machine manager that sits on top of a host system where all the virtual machines are run.

Another critical part of virtualization in EC2 is (AMI) or Amazon Machine Image.  This is also a virtual appliance. AMI is mostly used for creating “on-demand machines” within EC2.  

EC2 would not exist without the virtualization which is at the core of the IaaS cloud model and EC2 implementation. Virtualization allows Amazon to run different types of virtual machines of various sizes on top of their hardware.
