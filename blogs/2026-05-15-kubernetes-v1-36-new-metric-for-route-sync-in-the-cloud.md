---
title: "Kubernetes v1.36: New Metric for Route Sync in the Cloud Controller Manager"
url: "https://kubernetes.io/blog/2026/05/15/ccm-new-metric-route-sync-total/"
date: "2026-05-15"
author: ""
feed_url: "https://kubernetes.io/feed.xml"
---
This article was originally published with the wrong date. It was later republished, dated the 15th of May 2026. Kubernetes v1.36 introduces a new alpha counter metric route_controller_route_sync_total to the Cloud Controller Manager (CCM) route controller implementation at k8s.io/cloud-provider . This metric increments each time routes are synced with the cloud provider. A/B testing watch-based...
