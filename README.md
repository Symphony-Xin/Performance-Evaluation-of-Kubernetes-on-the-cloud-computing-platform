# Performance-Evaluation-of-Kubernetes-on-the-cloud-computing-platform-AWS-
Course project for CS5296 Cloud Computing:Theo &amp; Prac

This document describes how to use the EKS (Amazon Elastic Kubernetes Service) service on AWS (Amazon Web Services) to deploy a Kubernetes cluster, and conduct benchmark tests to evaluate performance indicators such as CPU, memory, network, and disk read and write. It also includes deploying two simple applications (kind and Ingress), testing the failover time and cluster scaling time of the Amazon EKS cluster hosting node group, and viewing and analyzing monitoring logs on the AWS backend.

Prerequisites：
  Before you begin, make sure you have the following prerequisites:
  1. Have a valid AWS account and have access to the EKS service.
  2. Installed and configured the AWS CLI tool to interact with AWS services.
  3. Familiar with Kubernetes and basic cluster management concepts.

Step：
  Step 1: Create an EKS cluster
  Step 2: Benchmark testing
  Step 3: Deploy the application：Deploy two simple applications (kind and Ingress) to the EKS cluster using Kubernetes configuration files or Helm charts. Make sure the application is running and accessible.
  Step 4: Cluster failover and scaling testing：Test the failover time of the Amazon EKS cluster hosting node group, including testing under load and without load.
  Test the scaling time of the cluster's managed node group, including testing under load and without load, using different scaling methods.
  Step 5: Background Monitoring and Analysis
In the AWS management console, view the monitoring logs of the EKS cluster, including CPU usage, memory usage, network traffic and other information.

The experimental process and related configuration files will be placed in the folder of each experiment.
