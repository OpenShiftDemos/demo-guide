Using the pre-existing infrastructure install process, also known as user
provisioned infrastructure or UPI, gives the administrator the ability to
create and manage OpenShift nodes themselves. The OpenShift install process
changes when using this method, where the Ignition configs must be provided
to the nodes so that they may cofigure and join the cluster. This video
demonstrates the process of deploying RHEL CoreOS to VMware virtual machines
and deploying OpenShift 4 to those VMs. For more information, refer to the
[installer
documentation](https://docs.openshift.com/container-platform/latest/installing/installing_vsphere/installing-vsphere.html)

## Video

**Pre-existing infrastructure (UPI) install using OpenShift 4.4**
  
  <iframe width="560" height="315" src="https://www.youtube.com/embed/PdyNQXpYknI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Recorded livestream OpenShift on vSphere (UPI and IPI) demo**
  
  <iframe width="560" height="315" src="https://www.youtube.com/embed/Be0dRq0wjWE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


[This **deprecated** video](https://www.youtube.com/watch?v=TsAJEEDv-gg) 
demonstrates deploying OpenShift 4.1 with the pre-existing (UPI) method, 
automating VM deployment using Terraform to create vSphere virtual 
machines from the Red Hat Enterprise Linux CoreOS OVA template.

## Additional Resources

* OpenShift documentation:
    * [Installing a cluster on vSphere](https://docs.openshift.com/container-platform/latest/installing/installing_vsphere/installing-vsphere.html)
* Blogs
    * [Deploying OpenShift 4.4 to VMware vSphere 7](https://www.openshift.com/blog/deploying-openshift-4.4-to-vmware-vsphere-7)
    * [OpenShift 4.2 vSphere Install Quickstart](https://blog.openshift.com/openshift-4-2-vsphere-install-quickstart/)
    * [OpenShift 4.2 vSphere Install with Static IPs](https://blog.openshift.com/openshift-4-2-vsphere-install-with-static-ips/)
    * [Deploying a User Provisoined Infrastructure environment for OpenShift 4.1 on vSphere](https://blog.openshift.com/deploying-a-user-provisioned-infrastructure-environment-for-openshift-4-1-on-vsphere/)
