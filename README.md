---
services: compute
platforms: java
author: selvasingh
---

#Getting Started with Compute - Manage Virtual Machines - in Java #

Compute Manage Virtual Machine Sample - demonstrates how to perform common tasks using the Microsoft Azure Compute service.

- Create a virtual machine
- Start a virtual machine
- Stop a virtual machine
- Restart a virtual machine
- Update a virtual machine
	- Expand the OS drive
	- Tag a virtual machine (there are many possible variations here)
	- Attach data disks
	- Detach data disks
- List virtual machines
- Delete a virtual machine.

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the location of the auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-vm.git

    cd compute-java-manage-vm

    mvn clean compile exec:java

## More information ##

[Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

[Virtual Machines - Learning Path](https://azure.microsoft.com/en-us/documentation/learning-paths/virtual-machines/)