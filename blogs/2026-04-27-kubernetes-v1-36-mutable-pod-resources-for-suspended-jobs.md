---
title: "Kubernetes v1.36: Mutable Pod Resources for Suspended Jobs (beta)"
url: "https://kubernetes.io/blog/2026/04/27/kubernetes-v1-36-mutable-pod-resources-for-suspended-jobs/"
date: "2026-04-27"
author: ""
feed_url: "https://kubernetes.io/feed.xml"
---
Kubernetes v1.36 promotes the ability to modify container resource requests and limits in the pod template of a suspended Job to beta. First introduced as alpha in v1.35, this feature allows queue controllers and cluster administrators to adjust CPU, memory, GPU, and extended resource specifications on a Job while it is suspended, before it starts or resumes running. Why mutable pod resources for...
