The AI/ML Workflows OpenShift demo aims to illustrate that, for data
scientists, the entire data science development pipeline is really just a
standard DevOps one. By demonstrating how Jupyter notebooks can be used as a
part of an Artificial Intelligence / Machine Learning model training and
deployment flow, the demo shows how easy it can be to use OpenShift for data
science from concept to production. It also incorporates the new OpenShift
4.3 feature of showing application metrics directly in the OpenShift web
interface.

## Video Recording
You can find a recording of the demo on YouTube:

<div style="
    position: relative; 
    padding-bottom: 56.25%; 
    margin-bottom: 2em;
    height: 0; 
    overflow: hidden; 
    max-width: 100%; 
    height: auto;">
    <iframe 
        src="https://www.youtube.com/embed/1REuOX6egnQ" 
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

## Demo
This demo can be provisioned using the Red Hat Product Demo System (RHPDS).
For those with access, it can be found in the "OpenShift Demos" section and
is titled "OpenShift 4 AI/ML Workflows Demo".

To conduct this demo in your own cluster is not particularly complicated. It
is a vanilla deployment of the [Open Data Hub](https://opendatahub.io/) using
the Jupyter that is deployed by it. The Jupyter Notebook is launched pointing
at the source repo linked below.

## Notebook Source
The source code repository that houses the various Jupyter Notebook files can
be found here: <https://github.com/willb/openshift-ml-workflows-workshop>