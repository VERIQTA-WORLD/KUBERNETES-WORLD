<div align="center">

# Kubernetes World

### Understand the cluster. Build the workload. Operate the system.

<img src="assets/covers/kubernetes-world-cover.png" width="460" alt="VERIQTA Kubernetes World cover"/>

<img src="assets/badges/resources.svg" alt="API resource catalogue"/>
<img src="assets/badges/sections.svg" alt="40 learning sections"/>

</div>

Kubernetes World is VERIQTA’s engineering hub for the Kubernetes platform and its surrounding ecosystem. Explore API resources, cluster components, workload design, networking, storage, security, observability, automation, production operations, and specialized workloads.

**Current edition:** Visual assets, indexes, and the repository structure are available. Individual learning, lab, project, and interview files are intentionally empty.

## Explore Kubernetes World

| Section | Focus |
|---|---|
| [00-Start-Here](00-Start-Here/) | How-to-Use, Learning-Paths, Lab-Environments, Version-and-Compatibility-Guide, Cost-and-Cleanup, Evidence-and-Redaction |
| [01-Beginner-to-Advanced](01-Beginner-to-Advanced/) | Beginner-Track, Intermediate-Track, Advanced-Track, Skills-Checklist |
| [02-Cloud-Native-and-Kubernetes-Foundations](02-Cloud-Native-and-Kubernetes-Foundations/) | Containers-and-Orchestration, Declarative-State, Reconciliation, Labels-and-Selectors, Namespaces, API-Groups-and-Versions, Object-Metadata, Ownership-and-Garbage-Collection |
| [03-Cluster-Architecture-and-Control-Plane](03-Cluster-Architecture-and-Control-Plane/) | API-Server, etcd, Scheduler, Controller-Manager, Cloud-Controller-Manager, Control-Plane-High-Availability, Leader-Election, Cluster-Communication |
| [04-Installation-Bootstrap-and-Cluster-Lifecycle](04-Installation-Bootstrap-and-Cluster-Lifecycle/) | kubeadm, kind, minikube, k3s, Talos, Bootstrap, Certificates, Cluster-Upgrades, Version-Skew, Cluster-API, Node-Join-and-Removal |
| [05-Nodes-Runtimes-and-Operating-Systems](05-Nodes-Runtimes-and-Operating-Systems/) | kubelet, Container-Runtime-Interface, containerd, CRI-O, RuntimeClass, Node-Lifecycle, Linux-and-cgroups, Windows-Nodes, Node-Resource-Managers, Node-Problem-Detection |
| [06-Kubectl-API-and-Client-Tools](06-Kubectl-API-and-Client-Tools/) | kubeconfig, Contexts, API-Discovery, kubectl-Get-and-Describe, Logs-Exec-and-Debug, Apply-Patch-and-Replace, Server-Side-Apply, Watches-and-ResourceVersions, Client-Libraries, API-Access |
| [07-Workloads-and-Controllers](07-Workloads-and-Controllers/) | Pods, Deployments, ReplicaSets, StatefulSets, DaemonSets, Jobs, CronJobs, ReplicationControllers, Init-Containers, Sidecars, Lifecycle-Hooks, Rollouts-and-Rollbacks |
| [08-Configuration-Secrets-and-Application-Lifecycle](08-Configuration-Secrets-and-Application-Lifecycle/) | ConfigMaps, Secrets, Environment-and-Volumes, Configuration-Reload, Probes, Graceful-Termination, Pod-Lifecycle, Application-Dependencies, Image-Pull-Credentials |
| [09-Scheduling-Placement-and-Resource-Management](09-Scheduling-Placement-and-Resource-Management/) | Requests-and-Limits, Affinity-and-Anti-Affinity, Taints-and-Tolerations, Topology-Spread, Priority-and-Preemption, Scheduler-Configuration, ResourceQuota, LimitRange, PodDisruptionBudget, Dynamic-Resource-Allocation |
| [10-Networking-CNI-and-Service-Discovery](10-Networking-CNI-and-Service-Discovery/) | Pod-Networking, Services, EndpointSlices, CoreDNS, kube-proxy, CNI, Calico, Cilium, NetworkPolicy, Dual-Stack, Egress, Network-Diagnostics |
| [11-Ingress-Gateway-API-and-Traffic-Management](11-Ingress-Gateway-API-and-Traffic-Management/) | Ingress, IngressClass, GatewayClass, Gateway, HTTPRoute, GRPCRoute, TLSRoute, TCPRoute, UDPRoute, ReferenceGrant, TLS-and-Certificates, Traffic-Splitting, Controller-Selection, Ingress-NGINX-Legacy-and-Migration |
| [12-Storage-CSI-and-Stateful-Applications](12-Storage-CSI-and-Stateful-Applications/) | Volumes, PersistentVolumes, PersistentVolumeClaims, StorageClass, CSI, CSIDriver, CSINode, VolumeAttachment, Snapshots, Expansion, Access-Modes, Stateful-Recovery, Database-Operators |
| [13-Identity-RBAC-and-Access-Control](13-Identity-RBAC-and-Access-Control/) | ServiceAccounts, Authentication, Authorization, Roles, RoleBindings, ClusterRoles, ClusterRoleBindings, Tokens, OIDC, CertificateSigningRequests, Cloud-Workload-Identity |
| [14-Security-Policy-and-Supply-Chain](14-Security-Policy-and-Supply-Chain/) | Pod-Security-Standards, SecurityContext, Admission-Policy, Kyverno, OPA-Gatekeeper, Secrets-Encryption, Image-Scanning, Signing-and-Provenance, Runtime-Security, Falco, Trivy, Threat-Modeling |
| [15-Observability-Metrics-Logs-and-Traces](15-Observability-Metrics-Logs-and-Traces/) | Prometheus, Grafana, kube-state-metrics, Metrics-Server, OpenTelemetry, Loki, Fluent-Bit, Jaeger, Tempo, Alertmanager, Audit-Logs, Service-Level-Indicators |
| [16-Autoscaling-Capacity-and-Performance](16-Autoscaling-Capacity-and-Performance/) | Horizontal-Pod-Autoscaling, Vertical-Pod-Autoscaling, Cluster-Autoscaler, Karpenter, KEDA, Custom-and-External-Metrics, Capacity-Planning, Load-Testing, CPU-Throttling, Memory-Pressure |
| [17-Helm-Kustomize-and-Package-Management](17-Helm-Kustomize-and-Package-Management/) | Helm-Charts, Values-and-Templates, Chart-Dependencies, Release-Management, OCI-Registries, Kustomize-Bases-and-Overlays, Patches, Generators, Manifest-Validation |
| [18-CI-CD-GitOps-and-Progressive-Delivery](18-CI-CD-GitOps-and-Progressive-Delivery/) | Argo-CD, Flux, Jenkins, GitHub-Actions, GitLab-CI, Tekton, Argo-Rollouts, Flagger, Canary-and-Blue-Green, Deployment-Gates, GitOps-Recovery |
| [19-Service-Mesh-and-Advanced-Traffic](19-Service-Mesh-and-Advanced-Traffic/) | Istio, Linkerd, Envoy, Mutual-TLS, Traffic-Policy, Telemetry, Ambient-and-Sidecar-Models, Mesh-Troubleshooting |
| [20-CRDs-Operators-and-API-Extensions](20-CRDs-Operators-and-API-Extensions/) | CustomResourceDefinitions, Custom-Resources, Operators, Kubebuilder, Operator-SDK, Admission-Webhooks, Conversion-Webhooks, Aggregated-APIs, APIService, Finalizers, Controller-Testing |
| [21-Multi-Tenancy-and-Platform-Engineering](21-Multi-Tenancy-and-Platform-Engineering/) | Namespace-Tenancy, Isolation-Boundaries, Resource-Quotas, Policy-Enforcement, Self-Service, Backstage, Crossplane, Platform-APIs, Developer-Experience |
| [22-Managed-Kubernetes-and-Cloud-Integration](22-Managed-Kubernetes-and-Cloud-Integration/) | Amazon-EKS, Azure-AKS, Google-GKE, Cloud-Networking, Cloud-Storage, Load-Balancer-Controllers, Workload-Identity, Managed-Control-Planes, Cloud-Costs |
| [23-On-Premises-Hybrid-Edge-and-Windows](23-On-Premises-Hybrid-Edge-and-Windows/) | Bare-Metal, MetalLB, k3s, Edge-Connectivity, Hybrid-Networking, Disconnected-Clusters, Windows-Workloads, Multi-Architecture-Images |
| [24-Reliability-Backup-and-Disaster-Recovery](24-Reliability-Backup-and-Disaster-Recovery/) | etcd-Backups, Velero, Application-Backups, Restore-Testing, Failure-Domains, Recovery-Objectives, Control-Plane-Recovery, Cluster-Rebuilds |
| [25-Production-Operations-and-CloudOps](25-Production-Operations-and-CloudOps/) | Operational-Readiness, Runbooks, Change-Management, Certificates-and-Rotation, Node-Maintenance, Patch-and-Upgrade, Incident-Response, Audit-Evidence |
| [26-Troubleshooting-and-Incident-Response](26-Troubleshooting-and-Incident-Response/) | CrashLoopBackOff, ImagePullBackOff, Pending-Pods, OOMKilled, DNS-Failures, Service-Connectivity, Ingress-Failures, Storage-Failures, Node-NotReady, Control-Plane-Failures, Admission-Failures, etcd-Latency |
| [27-Architecture-Patterns](27-Architecture-Patterns/) | Stateless-Web, Stateful-Service, Event-Driven, Batch-and-Scheduled, Multi-Tenant, Private-Platform, Multi-Cluster, GitOps-Platform, Observability-Stack |
| [28-Cost-Management-and-FinOps](28-Cost-Management-and-FinOps/) | Resource-Efficiency, Rightsizing, Node-Utilization, Idle-Resources, Storage-and-Network-Costs, Kubecost, OpenCost, Cost-Allocation |
| [29-Specialized-Workloads](29-Specialized-Workloads/) | GPU-and-Accelerators, AI-and-ML, Distributed-Training, Batch-and-HPC, Data-Platforms, Real-Time-Applications, DRA, Device-Plugins, Topology-Management |
| [30-Projects](30-Projects/) | Junior, Mid-Level, Senior, Portfolio-Capstones |
| [31-Labs](31-Labs/) | Junior, Mid-Level, Senior |
| [32-Interview-Preparation](32-Interview-Preparation/) | Junior, Mid-Level, Senior, Architecture-Discussions |
| [33-Certification-Preparation](33-Certification-Preparation/) | CKA, CKAD, CKS, KCNA, KCSA |
| [34-Engineer-Notebooks](34-Engineer-Notebooks/) | Notebook-Standards, Evidence-and-Redaction, Junior, Mid-Level, Senior, Shared-Templates |
| [35-Toolkit-and-Automation](35-Toolkit-and-Automation/) | kubectl-Cheat-Sheets, Shell-Scripts, Python-Clients, Manifest-Templates, Helm-Templates, Kustomize-Templates, Diagnostics, Cleanup-Checklists |
| [36-Kubernetes-API-Resource-Catalog](36-Kubernetes-API-Resource-Catalog/) | API-Discovery, Scope-and-Versions, Deprecations-and-Migrations |
| [37-Ecosystem-and-Extension-Resource-Catalog](37-Ecosystem-and-Extension-Resource-Catalog/) | Gateway-API, CSI-Snapshots, Prometheus-Operator, cert-manager, Argo-CD, Flux, Kyverno, Cilium, Istio, Crossplane, KEDA |
| [38-Resources-and-Official-References](38-Resources-and-Official-References/) | Official-Documentation, API-Reference, Release-Notes, Enhancement-Proposals, Community-and-SIGs |
| [39-Versioning-Compatibility-and-Deprecations](39-Versioning-Compatibility-and-Deprecations/) | Supported-Versions, Feature-Gates, API-Availability, Upgrade-Compatibility, Component-Compatibility, Deprecated-APIs, Extension-Version-Matrix |

## Core API resource directory

This inventory is generated from the official v1.37.1 API specification. Versions are documented separately from availability on an actual cluster. Some listed kinds are transient API requests or reviews.

| Resource kind | Icon | API group | Versions | Scope | Learn |
|---|---|---|---|---|---|
| MutatingAdmissionPolicy | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingAdmissionPolicy, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingAdmissionPolicy/) |
| MutatingAdmissionPolicyBinding | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingAdmissionPolicyBinding, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingAdmissionPolicyBinding/) |
| MutatingWebhookConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingWebhookConfiguration, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingWebhookConfiguration/) |
| ValidatingAdmissionPolicy | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingAdmissionPolicy, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingAdmissionPolicy/) |
| ValidatingAdmissionPolicyBinding | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingAdmissionPolicyBinding, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingAdmissionPolicyBinding/) |
| ValidatingWebhookConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingWebhookConfiguration, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingWebhookConfiguration/) |
| CustomResourceDefinition | <img src="assets/resource-icons/resources/unlabeled/crd.svg" width="30" alt="CustomResourceDefinition, Kubernetes resource"/> | `apiextensions.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/apiextensions-k8s-io/CustomResourceDefinition/) |
| APIService | <img src="assets/logos/kubernetes.svg" width="30" alt="APIService, Kubernetes resource"/> | `apiregistration.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/apiregistration-k8s-io/APIService/) |
| ControllerRevision | <img src="assets/logos/kubernetes.svg" width="30" alt="ControllerRevision, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/apps/ControllerRevision/) |
| DaemonSet | <img src="assets/resource-icons/resources/unlabeled/ds.svg" width="30" alt="DaemonSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/apps/DaemonSet/) |
| Deployment | <img src="assets/resource-icons/resources/unlabeled/deploy.svg" width="30" alt="Deployment, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/apps/Deployment/) |
| ReplicaSet | <img src="assets/resource-icons/resources/unlabeled/rs.svg" width="30" alt="ReplicaSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/apps/ReplicaSet/) |
| StatefulSet | <img src="assets/resource-icons/resources/unlabeled/sts.svg" width="30" alt="StatefulSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/apps/StatefulSet/) |
| SelfSubjectReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectReview, Kubernetes resource"/> | `authentication.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/authentication-k8s-io/SelfSubjectReview/) |
| TokenReview | <img src="assets/logos/kubernetes.svg" width="30" alt="TokenReview, Kubernetes resource"/> | `authentication.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/authentication-k8s-io/TokenReview/) |
| LocalSubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="LocalSubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/LocalSubjectAccessReview/) |
| SelfSubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SelfSubjectAccessReview/) |
| SelfSubjectRulesReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectRulesReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SelfSubjectRulesReview/) |
| SubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SubjectAccessReview/) |
| HorizontalPodAutoscaler | <img src="assets/resource-icons/resources/unlabeled/hpa.svg" width="30" alt="HorizontalPodAutoscaler, Kubernetes resource"/> | `autoscaling` | v1, v2 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/autoscaling/HorizontalPodAutoscaler/) |
| CronJob | <img src="assets/resource-icons/resources/unlabeled/cronjob.svg" width="30" alt="CronJob, Kubernetes resource"/> | `batch` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/batch/CronJob/) |
| Job | <img src="assets/resource-icons/resources/unlabeled/job.svg" width="30" alt="Job, Kubernetes resource"/> | `batch` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/batch/Job/) |
| CertificateSigningRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="CertificateSigningRequest, Kubernetes resource"/> | `certificates.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/CertificateSigningRequest/) |
| ClusterTrustBundle | <img src="assets/logos/kubernetes.svg" width="30" alt="ClusterTrustBundle, Kubernetes resource"/> | `certificates.k8s.io` | v1, v1beta1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/ClusterTrustBundle/) |
| PodCertificateRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="PodCertificateRequest, Kubernetes resource"/> | `certificates.k8s.io` | v1, v1beta1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/PodCertificateRequest/) |
| Lease | <img src="assets/logos/kubernetes.svg" width="30" alt="Lease, Kubernetes resource"/> | `coordination.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/coordination-k8s-io/Lease/) |
| LeaseCandidate | <img src="assets/logos/kubernetes.svg" width="30" alt="LeaseCandidate, Kubernetes resource"/> | `coordination.k8s.io` | v1alpha2, v1beta1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/coordination-k8s-io/LeaseCandidate/) |
| Binding | <img src="assets/logos/kubernetes.svg" width="30" alt="Binding, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Binding/) |
| ComponentStatus | <img src="assets/logos/kubernetes.svg" width="30" alt="ComponentStatus, Kubernetes resource"/> | `core` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/core/ComponentStatus/) |
| ConfigMap | <img src="assets/resource-icons/resources/unlabeled/cm.svg" width="30" alt="ConfigMap, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/ConfigMap/) |
| Endpoints | <img src="assets/logos/kubernetes.svg" width="30" alt="Endpoints, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Endpoints/) |
| Event | <img src="assets/logos/kubernetes.svg" width="30" alt="Event, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Event/) |
| LimitRange | <img src="assets/resource-icons/resources/unlabeled/limits.svg" width="30" alt="LimitRange, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/LimitRange/) |
| Namespace | <img src="assets/resource-icons/resources/unlabeled/ns.svg" width="30" alt="Namespace, Kubernetes resource"/> | `core` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/core/Namespace/) |
| Node | <img src="assets/resource-icons/infrastructure_components/unlabeled/node.svg" width="30" alt="Node, Kubernetes resource"/> | `core` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/core/Node/) |
| PersistentVolume | <img src="assets/resource-icons/resources/unlabeled/pv.svg" width="30" alt="PersistentVolume, Kubernetes resource"/> | `core` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/core/PersistentVolume/) |
| PersistentVolumeClaim | <img src="assets/resource-icons/resources/unlabeled/pvc.svg" width="30" alt="PersistentVolumeClaim, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/PersistentVolumeClaim/) |
| Pod | <img src="assets/resource-icons/resources/unlabeled/pod.svg" width="30" alt="Pod, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Pod/) |
| PodTemplate | <img src="assets/logos/kubernetes.svg" width="30" alt="PodTemplate, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/PodTemplate/) |
| ReplicationController | <img src="assets/logos/kubernetes.svg" width="30" alt="ReplicationController, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/ReplicationController/) |
| ResourceQuota | <img src="assets/resource-icons/resources/unlabeled/quota.svg" width="30" alt="ResourceQuota, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/ResourceQuota/) |
| Secret | <img src="assets/resource-icons/resources/unlabeled/secret.svg" width="30" alt="Secret, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Secret/) |
| Service | <img src="assets/resource-icons/resources/unlabeled/svc.svg" width="30" alt="Service, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/Service/) |
| ServiceAccount | <img src="assets/resource-icons/resources/unlabeled/sa.svg" width="30" alt="ServiceAccount, Kubernetes resource"/> | `core` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/core/ServiceAccount/) |
| EndpointSlice | <img src="assets/logos/kubernetes.svg" width="30" alt="EndpointSlice, Kubernetes resource"/> | `discovery.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/discovery-k8s-io/EndpointSlice/) |
| Event | <img src="assets/logos/kubernetes.svg" width="30" alt="Event, Kubernetes resource"/> | `events.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/events-k8s-io/Event/) |
| FlowSchema | <img src="assets/logos/kubernetes.svg" width="30" alt="FlowSchema, Kubernetes resource"/> | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/flowcontrol-apiserver-k8s-io/FlowSchema/) |
| PriorityLevelConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="PriorityLevelConfiguration, Kubernetes resource"/> | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/flowcontrol-apiserver-k8s-io/PriorityLevelConfiguration/) |
| StorageVersion | <img src="assets/logos/kubernetes.svg" width="30" alt="StorageVersion, Kubernetes resource"/> | `internal.apiserver.k8s.io` | v1alpha1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/internal-apiserver-k8s-io/StorageVersion/) |
| Eviction | <img src="assets/logos/kubernetes.svg" width="30" alt="Eviction, Kubernetes resource"/> | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/lifecycle-k8s-io/Eviction/) |
| EvictionRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="EvictionRequest, Kubernetes resource"/> | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/lifecycle-k8s-io/EvictionRequest/) |
| IPAddress | <img src="assets/logos/kubernetes.svg" width="30" alt="IPAddress, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/IPAddress/) |
| Ingress | <img src="assets/resource-icons/resources/unlabeled/ing.svg" width="30" alt="Ingress, Kubernetes resource"/> | `networking.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/Ingress/) |
| IngressClass | <img src="assets/logos/kubernetes.svg" width="30" alt="IngressClass, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/IngressClass/) |
| NetworkPolicy | <img src="assets/resource-icons/resources/unlabeled/netpol.svg" width="30" alt="NetworkPolicy, Kubernetes resource"/> | `networking.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/NetworkPolicy/) |
| ServiceCIDR | <img src="assets/logos/kubernetes.svg" width="30" alt="ServiceCIDR, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/ServiceCIDR/) |
| RuntimeClass | <img src="assets/logos/kubernetes.svg" width="30" alt="RuntimeClass, Kubernetes resource"/> | `node.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/node-k8s-io/RuntimeClass/) |
| PodDisruptionBudget | <img src="assets/logos/kubernetes.svg" width="30" alt="PodDisruptionBudget, Kubernetes resource"/> | `policy` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/policy/PodDisruptionBudget/) |
| ClusterRole | <img src="assets/resource-icons/resources/unlabeled/c-role.svg" width="30" alt="ClusterRole, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/ClusterRole/) |
| ClusterRoleBinding | <img src="assets/resource-icons/resources/unlabeled/crb.svg" width="30" alt="ClusterRoleBinding, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/ClusterRoleBinding/) |
| Role | <img src="assets/resource-icons/resources/unlabeled/role.svg" width="30" alt="Role, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/Role/) |
| RoleBinding | <img src="assets/resource-icons/resources/unlabeled/rb.svg" width="30" alt="RoleBinding, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/RoleBinding/) |
| DeviceClass | <img src="assets/logos/kubernetes.svg" width="30" alt="DeviceClass, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/DeviceClass/) |
| DeviceTaintRule | <img src="assets/logos/kubernetes.svg" width="30" alt="DeviceTaintRule, Kubernetes resource"/> | `resource.k8s.io` | v1, v1alpha3, v1beta2 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/DeviceTaintRule/) |
| ResourceClaim | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceClaim, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceClaim/) |
| ResourceClaimTemplate | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceClaimTemplate, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceClaimTemplate/) |
| ResourcePoolStatusRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourcePoolStatusRequest, Kubernetes resource"/> | `resource.k8s.io` | v1alpha3 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourcePoolStatusRequest/) |
| ResourceSlice | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceSlice, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceSlice/) |
| CompositePodGroup | <img src="assets/logos/kubernetes.svg" width="30" alt="CompositePodGroup, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/CompositePodGroup/) |
| PodGroup | <img src="assets/logos/kubernetes.svg" width="30" alt="PodGroup, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/PodGroup/) |
| PriorityClass | <img src="assets/logos/kubernetes.svg" width="30" alt="PriorityClass, Kubernetes resource"/> | `scheduling.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/PriorityClass/) |
| Workload | <img src="assets/logos/kubernetes.svg" width="30" alt="Workload, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/Workload/) |
| CSIDriver | <img src="assets/logos/kubernetes.svg" width="30" alt="CSIDriver, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSIDriver/) |
| CSINode | <img src="assets/logos/kubernetes.svg" width="30" alt="CSINode, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSINode/) |
| CSIStorageCapacity | <img src="assets/logos/kubernetes.svg" width="30" alt="CSIStorageCapacity, Kubernetes resource"/> | `storage.k8s.io` | v1 | Namespaced | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSIStorageCapacity/) |
| StorageClass | <img src="assets/resource-icons/resources/unlabeled/sc.svg" width="30" alt="StorageClass, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/StorageClass/) |
| VolumeAttachment | <img src="assets/logos/kubernetes.svg" width="30" alt="VolumeAttachment, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/VolumeAttachment/) |
| VolumeAttributesClass | <img src="assets/logos/kubernetes.svg" width="30" alt="VolumeAttributesClass, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/VolumeAttributesClass/) |
| StorageVersionMigration | <img src="assets/logos/kubernetes.svg" width="30" alt="StorageVersionMigration, Kubernetes resource"/> | `storagemigration.k8s.io` | v1, v1beta1 | Cluster | [Folder](36-Kubernetes-API-Resource-Catalog/storagemigration-k8s-io/StorageVersionMigration/) |

Where an exact resource icon is not available, the Kubernetes project mark identifies the platform. It is not presented as a unique resource logo.

[Full API catalogue](36-Kubernetes-API-Resource-Catalog/) | [Resource visual gallery](assets/galleries/api-resources-01.png)

## Ecosystem directory

Project logos identify their owners, not built-in Kubernetes components. Tools and extensions are optional and require their own compatibility checks.

| Project or tool | Logo | Learning area |
|---|---|---|
| argo | <img src="assets/logos/argo.svg" width="34" alt="argo"/> | [Explore](18-CI-CD-GitOps-and-Progressive-Delivery/) |
| backstage | <img src="assets/logos/backstage.svg" width="34" alt="backstage"/> | [Explore](21-Multi-Tenancy-and-Platform-Engineering/) |
| cert-manager | <img src="assets/logos/cert-manager.svg" width="34" alt="cert-manager"/> | [Explore](14-Security-Policy-and-Supply-Chain/) |
| cilium | <img src="assets/logos/cilium.svg" width="34" alt="cilium"/> | [Explore](10-Networking-CNI-and-Service-Discovery/) |
| clusternet | <img src="assets/logos/clusternet.svg" width="34" alt="clusternet"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| containerd | <img src="assets/logos/containerd.svg" width="34" alt="containerd"/> | [Explore](05-Nodes-Runtimes-and-Operating-Systems/) |
| crio | <img src="assets/logos/crio.png" width="34" alt="crio"/> | [Explore](05-Nodes-Runtimes-and-Operating-Systems/) |
| crossplane | <img src="assets/logos/crossplane.svg" width="34" alt="crossplane"/> | [Explore](21-Multi-Tenancy-and-Platform-Engineering/) |
| docker | <img src="assets/logos/docker.svg" width="34" alt="docker"/> | [Explore](05-Nodes-Runtimes-and-Operating-Systems/) |
| envoy | <img src="assets/logos/envoy.svg" width="34" alt="envoy"/> | [Explore](19-Service-Mesh-and-Advanced-Traffic/) |
| falco | <img src="assets/logos/falco.svg" width="34" alt="falco"/> | [Explore](14-Security-Policy-and-Supply-Chain/) |
| fluentd | <img src="assets/logos/fluentd.svg" width="34" alt="fluentd"/> | [Explore](15-Observability-Metrics-Logs-and-Traces/) |
| flux | <img src="assets/logos/flux.svg" width="34" alt="flux"/> | [Explore](18-CI-CD-GitOps-and-Progressive-Delivery/) |
| git | <img src="assets/logos/git.svg" width="34" alt="git"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| grafana | <img src="assets/logos/grafana.svg" width="34" alt="grafana"/> | [Explore](15-Observability-Metrics-Logs-and-Traces/) |
| harbor | <img src="assets/logos/harbor.svg" width="34" alt="harbor"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| helm | <img src="assets/logos/helm.svg" width="34" alt="helm"/> | [Explore](17-Helm-Kustomize-and-Package-Management/) |
| istio | <img src="assets/logos/istio.svg" width="34" alt="istio"/> | [Explore](19-Service-Mesh-and-Advanced-Traffic/) |
| jaeger | <img src="assets/logos/jaeger.svg" width="34" alt="jaeger"/> | [Explore](15-Observability-Metrics-Logs-and-Traces/) |
| jenkins | <img src="assets/logos/jenkins.svg" width="34" alt="jenkins"/> | [Explore](18-CI-CD-GitOps-and-Progressive-Delivery/) |
| keda | <img src="assets/logos/keda.svg" width="34" alt="keda"/> | [Explore](16-Autoscaling-Capacity-and-Performance/) |
| knative | <img src="assets/logos/knative.svg" width="34" alt="knative"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| kubeflow | <img src="assets/logos/kubeflow.svg" width="34" alt="kubeflow"/> | [Explore](29-Specialized-Workloads/) |
| kubernetes | <img src="assets/logos/kubernetes.svg" width="34" alt="kubernetes"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| kubevirt | <img src="assets/logos/kubevirt.svg" width="34" alt="kubevirt"/> | [Explore](29-Specialized-Workloads/) |
| kyverno | <img src="assets/logos/kyverno.svg" width="34" alt="kyverno"/> | [Explore](14-Security-Policy-and-Supply-Chain/) |
| linkerd | <img src="assets/logos/linkerd.svg" width="34" alt="linkerd"/> | [Explore](19-Service-Mesh-and-Advanced-Traffic/) |
| longhorn | <img src="assets/logos/longhorn.svg" width="34" alt="longhorn"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| opencost | <img src="assets/logos/opencost.svg" width="34" alt="opencost"/> | [Explore](28-Cost-Management-and-FinOps/) |
| opentelemetry | <img src="assets/logos/opentelemetry.svg" width="34" alt="opentelemetry"/> | [Explore](15-Observability-Metrics-Logs-and-Traces/) |
| prometheus | <img src="assets/logos/prometheus.svg" width="34" alt="prometheus"/> | [Explore](15-Observability-Metrics-Logs-and-Traces/) |
| python | <img src="assets/logos/python.svg" width="34" alt="python"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| rook | <img src="assets/logos/rook.svg" width="34" alt="rook"/> | [Explore](37-Ecosystem-and-Extension-Resource-Catalog/) |
| tekton | <img src="assets/logos/tekton.svg" width="34" alt="tekton"/> | [Explore](18-CI-CD-GitOps-and-Progressive-Delivery/) |
| velero | <img src="assets/logos/velero.svg" width="34" alt="velero"/> | [Explore](24-Reliability-Backup-and-Disaster-Recovery/) |
| vitess | <img src="assets/logos/vitess.svg" width="34" alt="vitess"/> | [Explore](29-Specialized-Workloads/) |
| volcano | <img src="assets/logos/volcano.svg" width="34" alt="volcano"/> | [Explore](29-Specialized-Workloads/) |

## Extension resource catalogue

| Extension | Example resource kinds | Directory |
|---|---|---|
| Gateway-API | GatewayClass, Gateway, HTTPRoute, GRPCRoute, TLSRoute, TCPRoute, UDPRoute, ReferenceGrant, BackendTLSPolicy | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Gateway-API/) |
| CSI-Snapshots | VolumeSnapshot, VolumeSnapshotContent, VolumeSnapshotClass | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/CSI-Snapshots/) |
| Prometheus-Operator | Prometheus, Alertmanager, ServiceMonitor, PodMonitor, PrometheusRule, Probe, ScrapeConfig | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Prometheus-Operator/) |
| cert-manager | Certificate, CertificateRequest, Issuer, ClusterIssuer, Order, Challenge | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/cert-manager/) |
| Argo-CD | Application, ApplicationSet, AppProject | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Argo-CD/) |
| Flux | GitRepository, OCIRepository, HelmRepository, Kustomization, HelmRelease, ImageRepository, ImagePolicy, ImageUpdateAutomation | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Flux/) |
| Kyverno | Policy, ClusterPolicy, PolicyException | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Kyverno/) |
| Cilium | CiliumNetworkPolicy, CiliumClusterwideNetworkPolicy, CiliumEndpoint | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Cilium/) |
| Istio | VirtualService, DestinationRule, Gateway, ServiceEntry, AuthorizationPolicy, PeerAuthentication | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Istio/) |
| Crossplane | Composition, CompositeResourceDefinition, Provider, ProviderConfig | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/Crossplane/) |
| KEDA | ScaledObject, ScaledJob, TriggerAuthentication, ClusterTriggerAuthentication | [Browse](37-Ecosystem-and-Extension-Resource-Catalog/KEDA/) |

## Cluster architecture visual

[View the control plane and worker-node diagram](assets/diagrams/cluster-architecture.png).

[Browse API subresource operations](36-Kubernetes-API-Resource-Catalog/Subresources/). The exact source schema is included in `docs/KUBERNETES-OPENAPI.json`.

## Choose a learning path

| Goal | Suggested focus |
|---|---|
| Start with Kubernetes | Foundations, local clusters, kubectl, Pods, Deployments, Services |
| Build applications | Workloads, configuration, networking, storage, Helm, delivery |
| Administer clusters | Architecture, lifecycle, nodes, access, backup, upgrades |
| Work in security | Identity, RBAC, admission, policy, secrets, supply chain |
| Operate production | Observability, capacity, reliability, incident response |
| Build platforms | GitOps, operators, tenancy, managed clusters, platform APIs |

## Coverage and compatibility

Kubernetes World covers the core API snapshot and broad engineering domains. Kubernetes can be extended through CRDs and aggregated APIs, so no fixed directory can enumerate every possible resource. Gateway API, CSI snapshots, service meshes, and operator resources remain separate from built-in APIs.

Alpha and beta versions in the source specification do not establish that an API is enabled. Verify the installed cluster version, feature gates, runtime configuration, and extension releases. Legacy subjects belong in migration context rather than new-installation instructions.

## References and visual credits

- [Kubernetes API reference](https://kubernetes.io/docs/reference/kubernetes-api/)
- [Kubernetes concepts](https://kubernetes.io/docs/concepts/)
- [Kubernetes release information](https://kubernetes.io/releases/)
- [Local asset attribution](assets/ATTRIBUTION.md)

## VERIQTA

Practical engineering starts with understanding the system, gathering evidence, and verifying the result. Star Kubernetes World to follow new learning materials.
