# Skaffold Config for Kubernetes Deployment

This repository contains the Kubernetes deployment files in the `infra/k8s` folder, along with a Skaffold configuration file for easy deployment.

## Getting Started

To get started, clone this repository:

## Prerequisites

Before deploying the Kubernetes resources, ensure that you have the following:

- A Kubernetes cluster set up and running
- Skaffold installed on your local machine

## Deploying the Kubernetes Resources

To deploy the Kubernetes resources, follow these steps:

1. Navigate to the root of the repository.
2. Run the following command to deploy the resources:

This command will deploy the resources to your Kubernetes cluster, and output the status of the deployment.

If you make changes to the Kubernetes resources, you can run `skaffold dev` instead. This will start a development loop that will redeploy the resources automatically whenever you save changes.

## Customizing the Deployment

If you need to customize the deployment, you can modify the `skaffold.yaml` file. This file specifies the build and deployment settings for your Kubernetes resources.

## Cleaning up the Deployment

To clean up the deployment, run the following command:

This command will delete all resources deployed by Skaffold.

## Troubleshooting

If you encounter issues while deploying the Kubernetes resources, check the following:

- Ensure that your Kubernetes cluster is set up and running correctly.
- Check that Skaffold is installed on your local machine and that it is up to date.
- Check the logs for your Kubernetes resources to identify any issues with the deployment.

## Conclusion

This repository provides the Kubernetes deployment files in the `infra/k8s` folder, along with a Skaffold configuration file for easy deployment. By following the steps outlined in this README, you should be able to deploy your Kubernetes resources quickly and easily. If you encounter any issues, refer to the troubleshooting section or seek help from the Kubernetes community.
