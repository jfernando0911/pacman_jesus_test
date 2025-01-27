# pacman
Pac-Man App Documentation

- [pacman](#pacman)
  - [Architecture](#architecture)
  - [Terraform and Azure](#terraform-and-azure)
  - [Ansible and Vault](#ansible-and-vault)
  - [Kubernetes, helm and pipelines](#kubernetes-helm-and-pipelines)
  - [Kubernetes namespace diagram](#kubernetes-namespace-diagram)
  - [Kubernetes diagram](#kubernetes-diagram)
  - [Image deploy](#image-deploy)
  - [Deploy to Kubernetes cluster](#deploy-to-kubernetes-cluster)
  - [Restart deployment](#restart-deployment)
  - [Uninstalling of deployment](#uninstalling-of-deployment)


## Architecture

![](./img/architecture.png)

---

## Terraform and Azure
Implementation of the infrastructure of Azure using Terraform:
- Resource group: Integrative-DevOps-Project
  - Container Registry: containerRegistry1123581321
  - Kubernetes Cluster: example-aks1
  - Network Interface: myNetworkInterface
  - Virtual Machine: Virtual-Machine-1

![](./img/06_terraform.png)

---

## Ansible and Vault

Ansible can install services, prepare services or resources and applications within the cloud. We use it to automate the installation of vault making the process faster and without errors.
And vault we use it to securely store secret data that we handle in this project
![](./img/vault%20.png)

---


## Kubernetes, helm and pipelines

## Kubernetes namespace diagram

Set up of a Kubernetes cluster to deploy an application that consists of two fundamental elements, a mongo db pod and nodejs pod. The pods contain, as the name says it, a container. In a a level above we have a cluster that is set up in the cloud.

## Kubernetes diagram

![](./img/01_diagram_namespace_pacman.png)

## Image deploy

![](./img/02_image_deploy.png)

## Deploy to Kubernetes cluster

![](./img/03_deploy_kubernetes.png)

## Restart deployment

![](./img/04_restart_pods.png)

## Uninstalling of deployment

![](./img/05_Uninstall.png)
