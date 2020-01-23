### CI/CD with OpenShift Pipelines (Tekton)

A pipeline in software development is an automated process that drives software through a path of building, testing, and deploying code. By automating the process, the objective is to minimize human error and maintain a consistent process for how software is deployed.

Tekton is an open source project that provides a framework to create cloud-native CI/CD pipelines quickly. As a Kubernetes-native framework, Tekton makes it easier to deploy across multiple cloud providers or hybrid environments. By leveraging the Custom Resource Definitions (CRDs) in Kubernetes, Tekton uses the Kubernetes control plane to run pipeline tasks. By using standard industry specifications, Tekton will work well with existing CI/CD tools such as Jenkins, Jenkins X, Skaffold, and Knative.

### Video

In this video, Daniel Helfand goes through the OpenShift Pipelines tutorial using OpenShift Pipelines version 0.4. The video shows users how to install OpenShift Pipelines via an operator, how to create Kubernetes custom resources based on Tekton, how to use the Tekton CLI, and discusses high-level concepts of Tekton. The result of this video is showing how to deploy a sample application out to an OpenShift 4 cluster using a Tekton pipeline.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/pMDiiW1UqLo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Workshop

* [A step-by-step tutorial showing OpenShift Pipelines](https://github.com/openshift/pipelines-tutorial)
* [openshift-labs/lab-tekton-pipelines: OpenShift Pipelines workshop](https://github.com/openshift-labs/lab-tekton-pipelines)

### Additional Resources

* [OpenShift Pipelines Documentation](https://openshift.github.io/pipelines-docs/)
* [Cloud-Native CI/CD with OpenShift Pipelines – Red Hat OpenShift Blog](https://blog.openshift.com/cloud-native-ci-cd-with-openshift-pipelines/)

### Source

* [tektoncd/cli](https://github.com/tektoncd/cli) — A CLI for interacting with Tekton!
* [tektoncd/pipeline](https://github.com/tektoncd/pipeline) — A K8s-native Pipeline resource.
