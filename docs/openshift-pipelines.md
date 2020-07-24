A pipeline in software development is an automated process that drives
software through a path of building, testing, and deploying code. By
automating the process, the objective is to minimize human error and maintain
a consistent process for how software is deployed.

Tekton is an open source project that provides a framework to create
cloud-native CI/CD pipelines quickly. As a Kubernetes-native framework,
Tekton makes it easier to deploy across multiple cloud providers or hybrid
environments. By leveraging the Custom Resource Definitions (CRDs) in
Kubernetes, Tekton uses the Kubernetes control plane to run pipeline tasks.
By using standard industry specifications, Tekton provides reusable
definitions of a CI/CD pipeline-as-code.

There are also public libraries of ready-to-use Tekton Tasks that help
speed-up the creation of pipelines, such as:

* [OpenShift Pipelines Tasks Catalog](https://github.com/openshift/pipelines-cat
alog)
* [Tekton Tasks Catalog](https://github.com/tektoncd/catalog)


## Video

In this video, Daniel Helfand goes through the OpenShift Pipelines tutorial
using OpenShift Pipelines version 0.4. The video shows users how to install
OpenShift Pipelines via an operator, how to create Kubernetes custom
resources based on Tekton, how to use the Tekton CLI, and discusses
high-level concepts of Tekton. The result of this video is showing how to
deploy a sample application out to an OpenShift 4 cluster using a Tekton
pipeline.

<div class="video">
    <iframe 
        src="https://www.youtube.com/embed/pMDiiW1UqLo" 
        frameborder="0" 
        allowfullscreen
    >
    </iframe>
</div>

## Workshops / Tutorials

* [OpenShift Pipelines tutorial on https://learn.openshift.com](https://learn.op
enshift.com/middleware/pipelines/)
* [A step-by-step tutorial showing OpenShift Pipelines](https://github.com/opens
hift/pipelines-tutorial)
* [openshift-labs/lab-tekton-pipelines: OpenShift Pipelines workshop](https://gi
thub.com/openshift-labs/lab-tekton-pipelines)
* [devnation Tekton master course slides](http://dn.dev/tektonmaster)
* [devnation Tekton master course tutorial](http://dn.dev/tekton-tutorial)

## Blogs

* [Cloud-Native CI/CD with OpenShift Pipelines – Red Hat OpenShift Blog](https:/
/blog.openshift.com/cloud-native-ci-cd-with-openshift-pipelines/)


## Additional Resources

* [OpenShift Pipelines Documentation](https://openshift.github.io/pipelines-docs
/)


## Source

* [tektoncd/cli](https://github.com/tektoncd/cli) — A CLI for interacting with 
Tekton!
* [tektoncd/pipeline](https://github.com/tektoncd/pipeline) — A K8s-native 
Pipeline resource.
