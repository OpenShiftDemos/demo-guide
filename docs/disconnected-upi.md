
Using the pre-existing install process, also known as user provisioned infrastructure or UPI, gives the administrator the ability to create and manage OpenShift nodes themselves.  The OpenShift install process changes when using this method, where the Ignition configs must be provided to the nodes so that they may cofigure and join the cluster. This manual install process is needed if you need to perform an install in an environment with limited or no access to the internet.  For more information, refer to the [installer documentation](https://docs.openshift.com/container-platform/4.2/installing/install_config/installing-restricted-networks-preparations.html)

### Blog

In this blog I will be going over how to perform an install in a lab environment with restricted access to the Internet.  I will also give an overview of my environment, how to mirror the needed images, and any other tips and tricks I’ve learned along the way.

* [Disconnected Install Blog](https://blog.openshift.com/openshift-4-2-disconnected-install/)


### Additional Resources

* OpenShift documentation: [Installing a cluster disconected](https://docs.openshift.com/container-platform/4.2/installing/install_config/installing-restricted-networks-preparations.html)
* [OpenTLC](https://labs.opentlc.com/catalog/explorer) lab guide for [disconnected install on RHOSP](http://ocp4-advanded-infra-8080-app-gpte-nstephan-slides.apps.shared.na.openshift.opentlc.com/03_Installation/03_1_OpenShift_UPI_Offline_Solution_Lab.html)
