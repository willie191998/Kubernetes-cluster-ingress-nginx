# Kubernetes Cluster Deployment

This repository contains Kubernetes configuration files for creating cluster deployments and services. The files contain the Docker image names for the containers to 
be created. This setup includes multiple deployments: Redis, PostgreSQL, server, worker, and client. Each deployment has its corresponding service files. These 
configurations can be deployed to a local Kubernetes cluster or to a cloud environment like AWS EKS, Google Cloud Platform (GCP), or Azure.

## Contents
- **Deployments**: Contains YAML files for the various Kubernetes deployments.
- **Services**: Contains YAML files for the Kubernetes services, providing network access to the deployments.
- **Docker Images**: The docker images used in the files are hosted on docker hub.

## Prerequisites
To use this repository, ensure you have the following:

- **Docker**: For building and managing Docker containers.
- **kubectl**: For interacting with Kubernetes clusters.
- **Kubernetes Cluster**: You can deploy to a local Kubernetes environment or cloud-based clusters on AWS, GCP, or Azure.

## Instructions for Deployment
Here are the steps to deploy this setup to a Kubernetes cluster:

https://www.digitalspeed.online/all-articles/how-to-deploy-a-containerized-app-on-aws-eks-clusters-with-ingress-nginx-enabled/
