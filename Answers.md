#### 1. Explain Working mechanism of Virtual Machine.

The Virtual Machine (VM) works by leveraging a technique called virtualization. Virtualization is the technology that makes
suitable virtual environment by managing, sharing, and allocating and hardware resources to VMs. The VM is installed on top of a hypervisor,
which lies on top of computer hardware. The hypervisor is responsible to manage VMs. It acts as a broker
between hardware and VM. This enables a computer system to run more than one virtual machines at a time. If some hardware is needed to be accessed directly by a VM,
then a feature called passthrough is used. All the resources like CPU, RAM, network interfaces, storage are emulated by the hypervisor and to a VM it looks like
its running on a real hardware.

#### 2. Explain Working mechanism of Containers.

Container, in simple terms can be thought of as a package that contains everything that is needed, inside a single unit.
Using the same concept, containers in IT contains all the required dependencies along with the code. This makes us easy
to set up the environment, whether it is for development or deployment. Unlike VMs, the container engine isolates the
programs from other programs. We can focus less on how to manage dependencies
and other nuances that we might face while setting up the environment.

#### 3. What problem does Virtualization solves and what is its drawback in context to modern application deployments?

Virtualization can be used to create many instances of virtual machines on the same hardware at a same time. This alone has many
benefits such as proper utilization of resources, sharing of unused resources and cost reduction. Virtualization also solves the problem
of scalability. Making backups, managing machines and creating snapshots is easy. It also helps to obtain more uptime.

However, virtualization has some drawbacks as well. During deployment, various types of machines need to be supported. This doesn't make sure
that it works well upon deployment. Also sometimes, application-level virtualization might be needed which is not supported by traditional virtualization.
Because we might need to isolate different applications without necessarily making different machines and
allocating more resources, this might be a major shortcoming.


#### 4. What are the problems Container solves in regard to app deployment and how it solves?

Firstly, containers provide application-level isolation. This greatly increases the performance so we don't need different virtual machines if we need to isolate a number
of applications.
