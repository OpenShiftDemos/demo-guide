# vSphere pre-existing infrastructure install

Using the pre-existing install process, also known as user provisioned infrastructure or UPI, gives the administrator the ability to create and manage OpenShift nodes themselves.  The OpenShift install process changes when using this method, where the Ignition configs must be provided to the nodes so that they may cofigure and join the cluster.  This video demonstrates the process of deploying RHEL CoreOS to VMware virtual machines and deploying OpenShift 4 to those VMs.  For more information, refer to the installer documentation at https://github.com/openshift/installer and the training materials at https://github.com/openshift/training.

## Video

This video demonstrates using Terraform to create vSphere virtual machines from the Red Hat CoreOS OVA template.

<iframe width="560" height="315" src="https://www.youtube.com/embed/TsAJEEDv-gg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Additional Resources

* OpenShift documentation: [Installing a cluster on vSphere](https://docs.openshift.com/container-platform/4.2/installing/installing_vsphere/installing-vsphere.html)
* Blogs
  * [OpenShift 4.2 vSphere Install Quickstart](https://blog.openshift.com/openshift-4-2-vsphere-install-quickstart/)
  * [OpenShift 4.2 vSphere Install with Static IPs](https://blog.openshift.com/openshift-4-2-vsphere-install-with-static-ips/)
  * [Deploying a User Provisoined Infrastructure environment for OpenShift 4.1 on vSphere](https://blog.openshift.com/deploying-a-user-provisioned-infrastructure-environment-for-openshift-4-1-on-vsphere/)
