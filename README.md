# Docker and Virtualization

## Docker

Docker uses **containers**.

Containers are a way to create lightweight, reproducible environments for processes to run.

## Virtualization

Before discussing containers, it's important to understand virtualization:

### What is Virtualization?

Virtualization requires the following components:

- **Host Machine**: This can be a local PC, a server in the cloud, or a server in a data center. A piece of hardware is needed.

- **Required Resources**: The host machine needs components that control how the hardware operates, such as CPU, Memory, and Hard Drive (I/O).

### Virtualization Process

To start the process, we take small pieces of each of these hardware components and separate them into a distinct machine called a **Virtual Machine (VM)**.

In a virtual machine, we run a complete operating system. This is commonly used in the cloud if you're deploying something to AWS or an EC2 instance.

### Hypervisor

Virtual machines utilize a special type of program that can run and manage their lifecycle, called a **Hypervisor**.

The hypervisor is in charge of virtual machines, managing their lifecycle. Examples of hypervisors include **VMWare** and **VirtualBox**.

## Containerization

Containerization creates a lightweight environment where processes can run on a host operating system. Containers share the same resources of the operating system but cannot access anything outside of their environment.

Docker manages the lifecycle of containers.

## Installing Docker

To install Docker, use the following command:

```bash
brew install docker
