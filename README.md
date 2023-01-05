[![CI](https://github.com/aws/karpenter/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/aws/karpenter/actions/workflows/ci.yml)
![GitHub stars](https://img.shields.io/github/stars/aws/karpenter)
![GitHub forks](https://img.shields.io/github/forks/aws/karpenter)
[![GitHub License](https://img.shields.io/badge/License-Apache%202.0-ff69b4.svg)](https://github.com/aws/karpenter/blob/main/LICENSE)
[![Go Report Card](https://goreportcard.com/badge/github.com/aws/karpenter)](https://goreportcard.com/report/github.com/aws/karpenter)
[![Coverage Status](https://coveralls.io/repos/github/aws/karpenter/badge.svg?branch=main)](https://coveralls.io/github/aws/karpenter?branch=main)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/aws/karpenter/issues)


Karpenter is an open-source node provisioning project built for Kubernetes.
Karpenter improves the efficiency and cost of running workloads on Kubernetes clusters by:

* **Watching** for pods that the Kubernetes scheduler has marked as unschedulable
* **Evaluating** scheduling constraints (resource requests, nodeselectors, affinities, tolerations, and topology spread constraints) requested by the pods
* **Provisioning** nodes that meet the requirements of the pods
* **Removing** the nodes when the nodes are no longer needed

Come discuss Karpenter in the [#karpenter](https://kubernetes.slack.com/archives/C02SFFZSA2K) channel in the [Kubernetes slack](https://slack.k8s.io/)!

Check out the [Docs](https://karpenter.sh/) to learn more.

## Talks
- 09/08/2022 [Workload Consolidation with Karpenter](https://youtu.be/BnksdJ3oOEs)
- 05/19/2022 [Scaling K8s Nodes Without Breaking the Bank or Your Sanity](https://www.youtube.com/watch?v=UBb8wbfSc34)
- 03/25/2022 [Karpenter @ AWS Community Day 2022](https://youtu.be/sxDtmzbNHwE?t=3931)
- 12/20/2021 [How To Auto-Scale Kubernetes Clusters With Karpenter](https://youtu.be/C-2v7HT-uSA)
- 11/30/2021 [Karpenter vs Kubernetes Cluster Autoscaler](https://youtu.be/3QsVRHVdOnM)
- 11/19/2021 [Karpenter @ Container Day](https://youtu.be/qxWJRUF6JJc)
- 05/14/2021 [Groupless Autoscaling with Karpenter @ Kubecon](https://www.youtube.com/watch?v=43g8uPohTgc)
- 05/04/2021 [Karpenter @ Container Day](https://youtu.be/MZ-4HzOC_ac?t=7137)
