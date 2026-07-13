---
title: "Kubernetes v1.35: Mutable PersistentVolume Node Affinity (alpha)"
url: "https://kubernetes.io/blog/2026/01/08/kubernetes-v1-35-mutable-pv-nodeaffinity/"
date: "2026-01-08"
feed_url: "https://kubernetes.io/feed.xml"
---
The PersistentVolume node affinity API dates back to Kubernetes v1.10. It is widely used to express that volumes may not be equally accessible by all nodes in the cluster. This field was previously immutable, and it is now mutable in Kubernetes v1.35 (alpha).
