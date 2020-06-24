OpenShift virtualization lets developers bring virtual machines (VMs)
into containerized workflows by running a virtual machine within a container.
By combining these two technologies into a single management platform,
organizations take advantage of the simplicity and speed of containers and
Kubernetes while still benefiting from the applications and services that
have been architected for virtual machines.

Please note that the name has recently changed from "Container-native virtualization"
to "OpenShift virtualization".  Some materials may still use the previous name or
abbreviation, "CNV".  Please use the new name when referencing or discussing the 
virtualization capabilties of OpenShift.

## Video

**Managing virtual machines using Red Hat Virtualization and OpenShift virtualization**

Demonstrates creating and managing OpenShift virtualization VMs using the Red Hat Virtualization Manager interface, highlighting how both traditional virtualization administrators and OpenShift / Kubernetes administrators can create and consume resources using the interface they are most familiar with.

<iframe width="560" height="315" src="https://www.youtube.com/embed/MMEaZAxj9_8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Deploying Microsoft Windows Server 2019 to OpenShift virtualization**

Creating and managing virtual machines, including those based on Red Hat and Microsoft operating systems, is quick and easy using the OpenShift virtualization wizard, or via the command line.  This demo highlights creating a Windows Server 2019 VM using the Containerized Data Importer to import a QCOW2 OS disk.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Kx110kqoHo0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Import from VMware to OpenShift virtualization**

Importing virtual machines from existing hosting environments makes it easy to bring the application components to the solution which best fits the needs of the application, developer, and administrator teams.  This demo shows the process of importing a VM from VMware vSphere to OpenShift virtualization.

<iframe width="560" height="315" src="https://www.youtube.com/embed/nUgd7sN-9NA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**OpenShift virtualization livestream**

This recorded livestream spends a significant amount of time highlight the cabilities and features of OpenShift virtualization, including walking through the process of installing the operator, deploying the hypervisor resources, and instantiating virtual machines.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ucllLdo-e4M" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Self-Paced Learning

KubeVirt, the upstream project for OpenShift virtualization, has several [self-pased labs hosted in by KataCoda](https://www.katacoda.com/kubevirt).

## Demo

A full demo and workshop environment is being created in RHPDS with availability expected in the near future.  Until that time, the KubeVirt community has a [demo repository](https://github.com/kubevirt/demo) which can use used, however the integration with OpenShift 4.x via Operators will not be present.  Please contact tech marketing for additional resources regarding OpenShift virtualization demos.

## Additional Resources

* [OpenShift virtualization landing page](https://www.openshift.com/learn/topics/virtualization/)
* [KubeVirt](https://kubevirt.io/), the upstream project for OpenShift virtualization
* [Documentation](https://docs.openshift.com/container-platform/4.4/cnv/cnv-about-cnv.html)
* Blogs
    * [OpenShift virtualization: What's new with virtualization from Red Hat](https://www.openshift.com/blog/blog-openshift-virtualization-whats-new-with-virtualization-from-red-hat)
    * [OpenShift virtualization: Containers, KVM, and your VMs](https://www.openshift.com/blog/openshift-virtualization-containers-kvm-and-your-vms)
    * [OpenShift 4.3: Creating virtual machines on Kubernetes with OpenShift's CNV](https://www.openshift.com/blog/openshift-4-3-creating-virtual-machines-on-kubernetes-with-openshifts-cnv)
