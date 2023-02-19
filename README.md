# Config Connector Charts

This repository contains a collection of [Helm](https://helm.sh) charts for deploying [Google Cloud Platform (GCP) Config Connector](https://cloud.google.com/config-connector/docs/overview) resources. The Helm repository is accessible under `https://helm.3cloudarch.com/`.

## Prerequisites

Before you begin, you should have the following prerequisites:

- A [GCP project](https://cloud.google.com/resource-manager/docs/creating-managing-projects)
- The [Helm CLI](https://helm.sh/docs/intro/install/)
- The [gcloud CLI](https://cloud.google.com/sdk/gcloud/)
- [Kubernetes](https://kubernetes.io) cluster
- [Config Connector](https://cloud.google.com/config-connector/docs/install/install-connector) installed in the cluster

## Usage

To use the charts in this repository, follow these steps:

1. Add the repository to Helm:

    ```
    helm repo add config-connector-charts https://helm.3cloudarch.com/
    ```

2. Search for the chart you want to install:

    ```
    helm search repo config-connector-charts
    ```

3. Install the chart:

    ```
    helm install my-release config-connector-charts/<chart name>
    ```

## Contributing

We welcome contributions! If you would like to contribute, please read the [CONTRIBUTING](https://github.com/3cloudarch/config-connector-charts/blob/master/CONTRIBUTING.md) document for more information.
