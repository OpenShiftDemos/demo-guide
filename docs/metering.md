
OpenShift Container Platform includes a solution for metering usage of
resources (CPU, memory, etc).

Metering is a general purpose data analysis tool that enables you to write
reports to process data from different data sources. As a cluster
administrator, you can use metering to analyze what is happening in your
cluster. You can either write your own, or use predefined SQL queries to
define how you want to process data from the different data sources you have
available.

Metering focuses primarily on in-cluster metric data using Prometheus as a
default data source, enabling users of metering to do reporting on pods,
namespaces, and most other Kubernetes resources.

## Additional Resources

You can find more information about OpenShift 4.2 metering in the
[documentation](https://docs.openshift.com/container-platform/4.2/metering/metering-about-metering.html)
