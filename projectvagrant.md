## Vagrant Documentation

To understand Vagrant, the starting point is to learn about teh role of Virtual Machines (VM) and how it works with Vagrant.

## Virtual Machine

As the name implies, it is a Virtual Machine, unlike a physical Windows or Mac laptop. My Windows laptop already has it's own operating system (OS) but I want to use another (OS) e.g Linux. To do this, I would need a VM. 

My Windows laptop will house a VM as the host machine while a VM will run as a guest machine using the hypervisor already built into my Windows laptop.  

Hypervisor allocates resources such as CPU, memory etc when a VM is installed on a host machine.

### Virtual Machine (Cloud Based Examples)

- Amazon EC2 
- Oracle Virtual Box
- Digital Ocean
- Google Cloud Compute Engine
- Microsoft Azure

## What is Vagrant, and how does it simplify environment provisioning and management for DevOps teams?

As a DevOps Engineer, if I am responsible for setting up development environment, testing environment, production environment etc, this would require different VMs and this is where Vagrant comes in handy. As defined by Hashicorp, it is a tool for building **complete** development environment in a single workflow. With Vagrant, there's no need for manual confuguration which is sometimes error prone.

## What are the key components and concepts in Vagrant, such as Vagrantfiles and providers?

Vagrantfiles
- When Vagrant is installed we can write the configuration of all the Vms we want to set up in a file called Vagrantfile using a Vagrant command known as `vagrant up`

- All configurations and softyware details can be added in Vagrantfile

## Providers
After installing Vagrant, we can run a command known as `vagrant init` which will automatically create Vagrantfile and then specify a provider (V) we want to use. *See cloud based examples listed above earlier*

## Vagrant Setup and Configuration:
How can Vagrant be installed and configured on different operating systems?

- On the your host machine, visit [Hashicorp.com](https://developer.hashicorp.com/vagrant/downloads) to download Vagrant for Windows or Mac. It is advisable to download I686 because it is compatible with the 64-bit of Windows OS

- Follow all the installation commands to install it 

- Check on on Windows Powershell to confirm that it has installed by typing the command `vagrant` or `vagrant --version` 

## Installation Outputs

[Vagrant-output](./Images/Vagrant-output.png)
