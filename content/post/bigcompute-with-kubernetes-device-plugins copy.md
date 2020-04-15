---
title: "Bigcompute with kubernetes device plugins"
date: 2018-10-03T14:34:55+01:00
draft: false
---


#### Limitless with k8s Device plugins.

From [k8s website](https://kubernetes.io/docs/concepts/extend-kubernetes/compute-storage-net/device-plugins/)
Starting in version 1.8, Kubernetes provides a device plugin framework for vendors to advertise their resources to the kubelet without changing Kubernetes core code. Instead of writing custom Kubernetes code, vendors can implement a device plugin that can be deployed manually or as a DaemonSet. The targeted devices include GPUs, High-performance NICs, FPGAs, InfiniBand, and other similar computing resources that may require vendor specific initialization and setup.

We at cloudgear have been dabbling with device plugins and are more interested in using it for Direct RDMA fabrics using Infiniband and standard mpiruns across the k8s clusters. This also provides the opportunity to use RDMA based direct GPU without p2p. GPUs without p2p is a reality these days in the cloud including a decent implementation for the Azure Kubernetes Cluster.
Have a peek in https://github.com/dwaiba/aks-terraform which has simple automations in place for the Daemonset.
Looking forward to some interesting comments and more on this topic.
