# Kube Prometheus Stack Example

This example is based on **[Kube Prometheus Stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack)**.

## Instructions

Generate the Kubernetes architecture diagram for the **Kube Prometheus Stack** Helm Chart:
```sh
$ helm-diagrams -c monitoring.coreos.com.kdc https://prometheus-community.github.io/helm-charts/kube-prometheus-stack
```

## Generated architecture diagrams

Architecture diagram for the **Kube Prometheus Stack** chart:

![kube-prometheus-stack.png](kube-prometheus-stack.png)

**Note**: The previous diagram shows that some metadata labels seem to be incorrectly used in the **Kube Prometheus Stack** chart. File [kube-prometheus-stack-corrected.yaml](kube-prometheus-stack-corrected.yaml) contains some possible corrections illustrated in the following diagram.

Corrected architecture diagram for the **Kube Prometheus Stack** Helm Chart:

![kube-prometheus-stack-corrected.png](kube-prometheus-stack-corrected.png):

Architecture diagram for a Kube Prometheus Stack deployed on minikube:

![kube-prometheus-stack-deployed-on-minikube.png](kube-prometheus-stack-deployed-on-minikube.png):
