Docker:

Docker use containers;

Containers are way to build reproduceable lightweight environment for processes to run.

Before talking about containers, is important to know about virtualization:


Virtualization:

When it comes to virtualization, it need the things below:

1. Needs a host machine, that can be a local PC, a server up in the cloud, a server in a data center somewhere, so, it needs a piece of hardware.

2. The host machine needs different things that control how this hardware works, like, CPU, Memory and Hard Drive - I/O.

To start the process, we take little pieces of each of these peaces of hardware above and separate them out into a separate machine, which is called, virtual machine.

In this virtual machine, we run a full entire Operating System. (Its commonly used in the cloud if you're deploying somenthing to AWS or an ec2 instance)

Virtual machines have a special type of program that can run and manage the life cycle, which is called hypervisor.

The Hypervisor is in charge of virtual machines, it manages the life cycle. (Example: VMWare, VirtualBox).

Contanerization:

It creates a lightweight environment where processes can run on a host operating system.
They share the same things in an operating system, but can't touch anything outside.


Docker manages the life cycle of containers.

To install docker: brew install docker




