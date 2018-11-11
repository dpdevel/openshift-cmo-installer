# Install Cluster Monitoring Operator on openshift 3.9

#### This project allows you to install cmo on ocp3.9

The Cluster Monitoring Operator manages and updates the Prometheus-based cluster monitoring stack deployed on top of OpenShift.

It contains the following components:

* [Prometheus Operator](https://github.com/coreos/prometheus-operator)
* [Prometheus](https://github.com/prometheus/prometheus)
* [Alertmanager](https://github.com/prometheus/alertmanager) cluster for cluster and application level alerting
* [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics)
* [node_exporter](https://github.com/prometheus/node_exporter)

Project:
* [cluster-monitoring-operator](https://github.com/openshift/cluster-monitoring-operator)


# Install on 3.9

`git clone https://github.com/dpdevel/openshift-cmo-installer.git`
`cd openshift-cmo-instller`
`oc login -u system:admin https://your.openshift.console:8443`
`oc apply -f manifests/`
