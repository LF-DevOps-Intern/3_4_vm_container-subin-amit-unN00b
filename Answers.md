#### 1. Explain Working mechanism of Virtual Machine.

The Virtual Machine (VM) works by leveraging a technique called virtualization. Virtualization is the technology that makes
suitable virtual environment by managing, sharing, and allocating and hardware resources to VMs. The VM is installed on top of a hypervisor,
which lies on top of computer hardware. The hypervisor is responsible to manage VMs. It acts as a broker
between hardware and VM. This enables a computer system to run more than one virtual machines at a time. If some hardware is needed to be accessed directly by a VM,
then a feature called passthrough is used. All the resources like CPU, RAM, network interfaces, storage are emulated by the hypervisor and to a VM it looks like
its running on a real hardware.

#### 2. Explain Working mechanism of Containers.
#### 3. What problem does Virtualization solves and what is its drawback in context to modern application deployments?
#### 4. What are the problems Container solves in regard to app deployment and how it solves?
