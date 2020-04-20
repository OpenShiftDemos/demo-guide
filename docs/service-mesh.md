
The Service Mesh in Action Workshop is a half-day experience designed to
introduce people to Service Mesh and how it works in an OpenShift
environment. It includes exercises covering the primary features of Istio,
how they are observed with Kiali, and an introduction to Jaeger.

## Source
The source code for the experience can be found
[here](https://github.com/thoraxe/lab-ossm). Note that there is a `develop`
branch as well as a `master`. The public-facing experience is always running
off `master`, and pull requests should be submitted to `develop`. The source
repository includes instructions for how to deploy the workshop yourself.

## Workshop
Within RHPDS, the catalog item is in the _Workshops_ category and is called
_Red Hat OpenShift Service Mesh in Action_. Each student/participant will be
sharing a single cluster. 

RHPDS uses [AgnosticD](https://github.com/redhat-cop/agnosticd) to provision
environments under the covers. This workshop involves several AgonsticD
modules:

* `ocp4-workload-istio-controlplane-infra`
* `ocp4-workload-istio-controlplane-student`
* `ocp4-workload-istio-tutorial-student`

The lab guide itself uses [Homeroom](https://github.com/openshift-homeroom),
and this is deployed with an AgnosticD role:
`ocp4-workload-istio-workshop-homeroom`.