Using the pre-existing install process, also known as user provisioned
infrastructure or UPI, gives the administrator the ability to create and
manage OpenShift nodes themselves. The OpenShift install process changes when
using this method, where the Ignition configs must be provided to the nodes
so that they may cofigure and join the cluster. For more information, refer
to the [installer
documentation](https://docs.openshift.com/container-platform/4.2/installing/installing_bare_metal/installing-bare-metal.html)

## Video

In this video, an installation is done on Bare Metal using [Packet.net](https://packet.net).

<iframe width="560" height="315" src="https://www.youtube.com/embed/3klCv49nayY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this video, a Bare Metal install is done from start to finish. This video
also goes through all the prerequisites and how to satisfy them before
installation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/wZYx4_xBSUQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Blog

In this blog we will go over how to get you up and running with a Red Hat
OpenShift 4 Bare Metal install on pre-existing infrastructure. Although this
quickstart focuses on the bare metal installer, this can also be seen as a
"manual" way to install OpenShift 4. Moreover, this is also applicable to
installing to any platform which doesn’t have the ability to provide
[ignition](https://coreos.com/ignition/docs/latest/) pre-boot.

* [Bare Metal UPI Blog](https://blog.openshift.com/openshift-4-bare-metal-install-quickstart/)

## Additional Resources

* OpenShift documentation: [Installing a cluster on Bare Metal](https://docs.openshift.com/container-platform/4.2/installing/installing_bare_metal/installing-bare-metal.html)
