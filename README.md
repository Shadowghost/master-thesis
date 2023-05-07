# Master's Thesis
This repository includes Kubernetes manifests used by my master's thesis.
They provide configurations to test different user stories based on Istio's [Bookinfo application](https://istio.io/latest/docs/examples/bookinfo/) on the Istio and Consul service meshes.

The provided manifests are split into three groups:

- **BaseCluster**: Includes all manifests used to setup the common base Kubernetes Cluster and the respective minimal installations of the service meshes
- **Istio**: Includes all manifests used to implement the user stories in Isto
- **Consul**: Includes all manifests used to implement the user stories in Consul
