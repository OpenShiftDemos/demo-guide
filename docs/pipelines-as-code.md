Pipelines-as-code is the ability to define your pipeline within your application's git repository and let the CI/CD tool automatically create and run those pipelines upon specific events, such as as commit, or a Pull Request.

With OpenShift Pipelines-as-code, this feature allows you to create your pipelines in a specific folder of your application's code repository (called .tekton) and let OpenShift Pipelines (based on Tekton project) create all the necessary primitives and resources to run the pipeline on OpenShift.

This is very handy because it takes care of initiating a lot of things that needed to be done manually before (creating the pipelines, create the EventListeners etc...) and makes it easier to now keep your pipelines up-to-date with your application releases.

## Introduction to the concepts of Pipelines-as-code
** The following video gives an overview of this new feature on OpenShift

## Demo
** The following video shows a demontration of Pipelines-as-code running on OpenShift


## To 


