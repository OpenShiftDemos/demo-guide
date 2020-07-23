Using the pre-existing install process, also known as user provisioned
infrastructure or UPI, gives the administrator the ability to create and
manage OpenShift nodes themselves. The OpenShift install process changes when
using this method, where the Ignition configs must be provided to the nodes
so that they may cofigure and join the cluster. For more information, refer
to the [installer documentation](https://docs.openshift.com/container-platform/l
atest/installing/installing_bare_metal/installing-bare-metal.html)

## Video

In this video, an installation is done on Bare Metal using [Packet.net](https://
packet.net).

<div style="
    position: relative; 
    padding-bottom: 56.25%; 
    margin-bottom: 2em;
    height: 0; 
    overflow: hidden; 
    max-width: 100%; 
    height: auto;">
    <iframe 
        src="https://www.youtube.com/embed/3klCv49nayY" 
        frameborder="0" 
        allowfullscreen 
        style="
            position: absolute; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100%;
        ">
    </iframe>
</div>

In this video, a Bare Metal install is done from start to finish. This video
also goes through all the prerequisites and how to satisfy them before
installation.

<div style="
    position: relative; 
    padding-bottom: 56.25%; 
    margin-bottom: 2em;
    height: 0; 
    overflow: hidden; 
    max-width: 100%; 
    height: auto;">
    <iframe 
        src="https://www.youtube.com/embed/wZYx4_xBSUQ" 
        frameborder="0" 
        allowfullscreen 
        style="
            position: absolute; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100%;
        ">
    </iframe>
</div>

## Blog

In this blog we will go over how to get you up and running with a Red Hat
OpenShift 4 Bare Metal install on pre-existing infrastructure. Although this
quickstart focuses on the bare metal installer, this can also be seen as a
"manual" way to install OpenShift 4. Moreover, this is also applicable to
installing to any platform which doesn’t have the ability to provide
[ignition](https://coreos.com/ignition/docs/latest/) pre-boot.

* [Bare Metal UPI Blog](https://blog.openshift.com/openshift-4-bare-metal-instal
l-quickstart/)

## Additional Resources

* OpenShift documentation: [Installing a cluster on Bare Metal](https://docs.ope
nshift.com/container-platform/latest/installing/installing_bare_metal/installing
-bare-metal.html)
* HelperNode: [OpenShift HelperNode Repo](https://github.com/RedHatOfficial/ocp4
-helpernode)
