# Wordpress-Kubernetes

Deployment of Wordpress on Kubernetes.

Prerequisite:
Secrets
PV and PVC
MySql Container Image
Wordpress Container Image
Deployments
Service

This tutorial shows you how to deploy a WordPress site and a MySQL database using Minikube. Both applications use PersistentVolumes and PersistentVolumeClaims to store data.
A PersistentVolume (PV) is a piece of storage in the cluster that has been manually provisioned by an administrator, or dynamically provisioned by Kubernetes using a StorageClass. A PersistentVolumeClaim (PVC) is a request for storage by a user that can be fulfilled by a PV. PersistentVolumes and PersistentVolumeClaims are independent from Pod lifecycles and preserve data through restarting, rescheduling, and even deleting Pods.

![image](https://user-images.githubusercontent.com/61797840/128000922-a932dc5f-0ba9-4630-adfb-8fd37274862b.png)
