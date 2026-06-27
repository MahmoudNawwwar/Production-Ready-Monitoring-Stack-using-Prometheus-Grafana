# Production-Ready Monitoring Stack using Prometheus & Grafana

## Overview

This project demonstrates deploying a production-ready Kubernetes monitoring stack using the **kube-prometheus-stack** Helm chart on a **Minikube multi-node cluster**.

The deployed monitoring stack includes:

- Prometheus
- Grafana
- Alertmanager
- Prometheus Operator
- kube-state-metrics
- Node Exporter

---

# Technologies

- Kubernetes
- Minikube
- Helm
- Prometheus
- Grafana

---

# Project Tasks

### ✅ Configure Helm

- Added Prometheus Community Helm repository.
- Updated Helm repositories.
- Verified the latest kube-prometheus-stack chart.

### ✅ Deploy Monitoring Stack

- Created the `monitoring` namespace.
- Installed the kube-prometheus-stack using Helm.
- Waited until all resources became ready.

### ✅ Verify Installation

Verified the following Kubernetes resources:

- Pods
- Services
- Deployments
- StatefulSets
- DaemonSets
- ConfigMaps
- Secrets
- ServiceAccounts

### ✅ Verify Monitoring Components

Successfully verified:

- Prometheus Server
- Grafana
- Alertmanager
- Prometheus Operator
- kube-state-metrics
- Node Exporter

### ✅ Grafana Verification

Verified:

- Successful login
- Prometheus configured as the default data source
- Alertmanager configured
- Kubernetes dashboards displaying metrics

### ✅ Prometheus Verification

Verified:

- Target Health
- Service Discovery
- PromQL query execution (`up`)
- Kubernetes monitoring targets

### ✅ Deploy Sample Application

Deployed an NGINX sample application and verified:

- Pod is running
- Service is available

---

# Screenshots

## Helm Release

![Helm Release](screenshots/01-helm-release.png)

---

## Monitoring Pods

![Monitoring Pods](screenshots/02-monitoring-pods.png)

---

## Monitoring Services

![Monitoring Services](screenshots/03-monitoring-services.png)

---

## Service Monitors

![Service Monitors](screenshots/04-service-monitors.png)

---

## Grafana Data Sources

![Grafana Data Sources](screenshots/05-grafana-data-sources.png)

---

## Grafana Dashboard - CoreDNS

![CoreDNS Dashboard](screenshots/06-grafana-dashboard-CoreDNS.png)

---

## Grafana Dashboard - Alertmanager

![Alertmanager Dashboard](screenshots/07-grafana-dashboard-Alertmanager.png)

---

## Grafana Dashboard - Kubernetes API Server

![Kubernetes API Server Dashboard](screenshots/08-grafana-dashboard-kubernetes-ApiServer.png)

---

## Grafana Dashboard - Kubernetes Kubelet

![Kubernetes Kubelet Dashboard](screenshots/09-grafana-dashboard-Kubernetes-Kubelet.png)

---

## Prometheus Target Health

![Prometheus Target Health](screenshots/10-prometheus-target-health.png)

---

## Prometheus Query

![Prometheus Query](screenshots/11-prometheus-query-up.png)

---

## Prometheus Service Discovery

![Prometheus Service Discovery](screenshots/12-prometheus-service-discovery.png)

---

## Sample Application

![Sample Application](screenshots/13-sample-application.png)

---

# Result

The monitoring stack was successfully deployed and verified.

The project confirms:

- Helm deployment completed successfully.
- Grafana and Prometheus are fully operational.
- Kubernetes components are being monitored.
- A sample application was deployed successfully.
- Monitoring dashboards and Prometheus targets are working as expected.
