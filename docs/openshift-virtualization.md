OpenShift Virtualization lets developers bring virtual machines (VMs)
into containerized workflows by running a virtual machine within a container.
By combining these two technologies into a single management platform,
organizations take advantage of the simplicity and speed of containers and
Kubernetes while still benefiting from the applications and services that
have been architected for virtual machines.

Please note that the name has recently changed from "Container-native virtualization"
to "OpenShift Virtualization".  Some materials may still use the previous name or
abbreviation, "CNV".  Please use the new name when referencing or discussing the 
virtualization capabilties of OpenShift.

## Video

**Demo and overview of OpenShift Virtualization**

This 30-minute video provides a guided overview of many aspects of OpenShift Virtualization, including compute, storage, and networking.  

The video was created using OpenShift 4.4 and OpenShift Virtualization 2.3, which are the versions immediately preceeding general availability.  As a result, please expect some minor changes to the GUI.

<iframe width="560" height="315" src="https://www.youtube.com/embed/JzfXhdcsdRs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* [Managing virtual machines using Red Hat Virtualization and OpenShift Virtualization](https://youtu.be/MMEaZAxj9_8) - Demonstrates creating and managing OpenShift Virtualization VMs using the Red Hat Virtualization Manager interface, highlighting how both traditional virtualization administrators and OpenShift / Kubernetes administrators can create and consume resources using the interface they are most familiar with.
  
* [Deploying Microsoft Windows Server 2019 to OpenShift Virtualization](https://youtu.be/Kx110kqoHo0) - Creating and managing virtual machines, including those based on Red Hat and Microsoft operating systems, is quick and easy using the OpenShift Virtualization wizard, or via the command line.  This demo highlights creating a Windows Server 2019 VM using the Containerized Data Importer to import a QCOW2 OS disk.

**Import to OpenShift Virtualization**

Importing virtual machines from existing hosting environments makes it easy to bring the application components to the solution which best fits the needs of the application, developer, and administrator teams.

* [Import from VMware vSphere](https://youtu.be/nUgd7sN-9NA)
* [Import from Red Hat Virtualization](https://youtu.be/TDXg4j3VXrg)

**OpenShift Virtualization livestream**

[This recorded livestream](https://www.youtube.com/embed/ucllLdo-e4M), about two hours in length, spends time highlighting the cabilities and features of OpenShift Virtualization, including walking through the process of installing the Operator, deploying the hypervisor resources, and instantiating virtual machines.

## Self-Paced Learning and demo environment

A full demo and workshop environment is being created in RHPDS with availability expected in the near future.  Until that time, you may use the automation found [in this repository](https://github.com/rdoxenham/openshift-virt-labs) to deploy a local instance of OpenShift with OpenShift Virtualization, along with an internally hosted lab guide.

Additionally, KubeVirt, the upstream project for OpenShift Virtualization, has several [self-pased labs hosted in by KataCoda](https://www.katacoda.com/kubevirt).  Finally, the KubeVirt community has a [demo repository](https://github.com/kubevirt/demo) which can use used, however the integration with OpenShift 4.x via Operators will not be present.  

Please contact CPBU tech marketing for additional resources regarding OpenShift Virtualization demos.

## Additional Resources

* [OpenShift Virtualization landing page](https://www.openshift.com/virtualization/)
* [KubeVirt](https://kubevirt.io/), the upstream project for OpenShift Virtualization
* [Documentation](https://docs.openshift.com/container-platform/4.4/cnv/cnv-about-cnv.html)
* Blogs
    * [OpenShift Virtualization: What's new with virtualization from Red Hat](https://www.openshift.com/blog/blog-openshift-virtualization-whats-new-with-virtualization-from-red-hat)
    * [OpenShift Virtualization: Containers, KVM, and your VMs](https://www.openshift.com/blog/openshift-virtualization-containers-kvm-and-your-vms)
    * [OpenShift 4.3: Creating virtual machines on Kubernetes with OpenShift's CNV](https://www.openshift.com/blog/openshift-4-3-creating-virtual-machines-on-kubernetes-with-openshifts-cnv)
