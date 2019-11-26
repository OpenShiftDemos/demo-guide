# OpenShift and Container Storage for Admins

The OpenShift and Container Storage for Admins workshop is a series of
exercises targeted at individuals who would be installing or managing an
OpenShift Container Platform environment with or without OpenShift Container
Storage.

## Source
The source code for the lab guide can be found
[here](https://github.com/openshift/openshift-cns-testdrive/tree/ocp4-prod).
Note that there is an `ocp4-dev` and `ocp4-prod` branch. Please feel free to
submit issues against the repository but make sure that pull requests go to
`ocp4-dev`. The source repository includes instructions for how to deploy the
workshop yourself.
 
## RHPDS
Within RHPDS, the catalog item is in the _Workshops_ category and is called
_OCP and Container Storage for Admins_. Each student/participant will be
using their own cluster. In RHPDS, before ordering, the catalog item
description links to instructions for how to set up your environment and
other details about performing the workshop.

While RHPDS uses [AgnosticD](https://github.com/redhat-cop/agnosticd) to
provision environments under the covers, this particular workshop only uses a
single role, `ocp4-workload-workshop-admin-storage` to deploy the lab guide,
which is based on [Homeroom](https://github.com/openshift-homeroom).