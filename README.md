# Kubernetes EKS 2048 Application

A Kubernetes practice project demonstrating deployment of a containerized web application on Amazon EKS.

## Architecture

**User → AWS Load Balancer → Kubernetes Service → Pods**

## Technologies

- Docker
- Kubernetes
- Amazon EKS
- EC2 worker nodes
- kubectl
- eksctl
- AWS CLI
- Kubernetes Deployment
- Kubernetes Service of type LoadBalancer

## Deployment Flow

1. Prepare the container image
2. Create an EKS cluster
3. Configure kubectl with the cluster
4. Deploy the application
5. Expose the application through a LoadBalancer Service
6. Verify pods, nodes and service
7. Scale application replicas when required

## Kubernetes Concepts Practiced

- Pods
- Deployments
- Replica scaling
- Services
- Selectors
- Container ports
- EKS node groups
- AWS Load Balancer integration

## Deployment Status

This repository documents an EKS learning/practice implementation. It does not claim a currently running AWS cluster.
