---
date: 2020-03-17T13:36:18+01:00
title: "KIND"
---

## KIND

[KIND](https://github.com/kubernetes-sigs/kind) is a tool to run local Kubernetes clusters inside Docker container nodes.
Submariner provides with scripts that deploy 3 Kubernetes clusters locally, 1 broker and 2 data clusters with submariner
running on both the data clusters.

To deploy the setup, clone [submariner repo](https://github.com/submariner-io/submariner) and run

`make ci e2e status=keep`

This will deploy 3 Kubernetes clusters and run basic [end-to-end](https://github.com/submariner-io/submariner/tree/master/test/e2e) tests.

More details can be found [here.](https://github.com/submariner-io/submariner/tree/master/scripts/kind-e2e)

