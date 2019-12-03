
The OpenShift Cloud Native Development workshop is a series of exercises
targeted at individuals who are interested in cloud native development
practices and how the Red Hat portfolio of solutions work in that context.
The workshop consists of four distinct modules covering various topics:

1. Optimizing Existing Applications
1. Debugging, Monitoring and Continuous Delivery
1. Control Cloud Native Apps with Service Mesh
1. Advanced Cloud Native with Event-Driven Serverless

## Workshop
Within RHPDS, the catalog item is in the _Workshops_ category and is called
_CCN Roadshow for Dev Track_. The instructor will provision one cluster for the entire workshop. In RHPDS, before ordering, the catalog item
description links to instructions for how to set up your environment and
other details about performing the workshop.

While RHPDS uses [AgnosticD](https://github.com/redhat-cop/agnosticd) to
provision environments under the covers, this particular workshop only uses a
single role, [ocp4-workload-ccnrd](https://github.com/redhat-cop/agnosticd/tree/development/ansible/roles/ocp4-workload-ccnrd) to deploy the lab guide.

## Source
- The source code for the lab infrastructure required for these labs can be found [here](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2-infra).
- The source code for the RHPDS role can be found [here](https://github.com/redhat-cop/agnosticd/tree/development/ansible/roles/ocp4-workload-ccnrd).
- The source code for the lab guides can be found here:
    1. [Optimizing Existing Applications](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m1-guides)
    1. [Debugging, Monitoring and Continuous Delivery](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m2-guides)
    1. [Control Cloud Native Apps with Service Mesh](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m3-guides)
    1. [Advanced Cloud Native with Event-Driven Serverless](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m4-guides)
- The source code for the lab content utilized within the labs can be found here:
    1. [Optimizing Existing Applications](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m1-labs)
    1. [Debugging, Monitoring and Continuous Delivery](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m2-labs)
    1. [Control Cloud Native Apps with Service Mesh](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m3-labs)
    1. [Advanced Cloud Native with Event-Driven Serverless](https://github.com/RedHat-Middleware-Workshops/cloud-native-workshop-v2m4-labs)
