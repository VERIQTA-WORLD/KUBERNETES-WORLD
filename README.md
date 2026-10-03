<div align="center">

# KUBERNETES-WORLD

### Understand the cluster. Build the workload. Operate the system.

<img src="assets/covers/kubernetes-world-cover.png" width="560" alt="Kubernetes World, cluster, workload, and production engineering">

</div>

KUBERNETES-WORLD is VERIQTA's learning and reference hub for Kubernetes engineering. Explore the platform from declarative state and reconciliation to workload design, networking, storage, security, observability, and production operations.

Understand how the cluster behaves, how its resources fit together, and how to investigate failures with evidence. Connect individual objects to the applications, platforms, and operating decisions they support.

## Choose your starting point

| Your goal | Explore |
| :--- | :--- |
| Learn Kubernetes from the beginning | [Learning paths](01-Beginner-to-Advanced/) and [foundations](02-Cloud-Native-and-Kubernetes-Foundations/) |
| Understand the control plane and nodes | [Cluster architecture](03-Cluster-Architecture-and-Control-Plane/) and [node operations](05-Nodes-Runtimes-and-Operating-Systems/) |
| Deploy and manage an application | [Workloads](07-Workloads-and-Controllers/) and [configuration](08-Configuration-Secrets-and-Application-Lifecycle/) |
| Connect and expose services | [Networking](10-Networking-CNI-and-Service-Discovery/) and [Ingress and Gateway API](11-Ingress-Gateway-API-and-Traffic-Management/) |
| Operate stateful systems | [Storage and CSI](12-Storage-CSI-and-Stateful-Applications/) |
| Secure access and workloads | [Identity and RBAC](13-Identity-RBAC-and-Access-Control/) and [security](14-Security-Policy-and-Supply-Chain/) |
| Investigate a production failure | [Observability](15-Observability-Metrics-Logs-and-Traces/) and [troubleshooting](26-Troubleshooting-and-Incident-Response/) |
| Build practical experience | [Labs](31-Labs/) and [projects](30-Projects/) |
| Prepare for interviews or certification | [Interview preparation](32-Interview-Preparation/) and [certification](33-Certification-Preparation/) |

## Explore the complete learning catalogue

Study the subjects in sequence or go directly to the engineering problem you need to understand.

| Subject | Engineering focus |
| :--- | :--- |
| [Start Here](00-Start-Here/) | How to Use, Learning Paths, Lab Environments, Version and Compatibility Guide, Cost and Cleanup, Evidence and Redaction. |
| [Beginner to Advanced](01-Beginner-to-Advanced/) | Beginner Track, Intermediate Track, Advanced Track, Skills Checklist. |
| [Cloud Native and Kubernetes Foundations](02-Cloud-Native-and-Kubernetes-Foundations/) | Containers and Orchestration, Declarative State, Reconciliation, Labels and Selectors, Namespaces, API Groups and Versions, Object Metadata, Ownership and Garbage Collection. |
| [Cluster Architecture and Control Plane](03-Cluster-Architecture-and-Control-Plane/) | API Server, etcd, Scheduler, Controller Manager, Cloud Controller Manager, Control Plane High Availability, Leader Election, Cluster Communication. |
| [Installation Bootstrap and Cluster Lifecycle](04-Installation-Bootstrap-and-Cluster-Lifecycle/) | kubeadm, kind, minikube, k3s, Talos, Bootstrap, Certificates, Cluster Upgrades, Version Skew, Cluster API, Node Join and Removal. |
| [Nodes Runtimes and Operating Systems](05-Nodes-Runtimes-and-Operating-Systems/) | kubelet, Container Runtime Interface, containerd, CRI O, RuntimeClass, Node Lifecycle, Linux and cgroups, Windows Nodes, Node Resource Managers, Node Problem Detection. |
| [Kubectl API and Client Tools](06-Kubectl-API-and-Client-Tools/) | kubeconfig, Contexts, API Discovery, kubectl Get and Describe, Logs Exec and Debug, Apply Patch and Replace, Server Side Apply, Watches and ResourceVersions, Client Libraries, API Access. |
| [Workloads and Controllers](07-Workloads-and-Controllers/) | Pods, Deployments, ReplicaSets, StatefulSets, DaemonSets, Jobs, CronJobs, ReplicationControllers, Init Containers, Sidecars, Lifecycle Hooks, Rollouts and Rollbacks. |
| [Configuration Secrets and Application Lifecycle](08-Configuration-Secrets-and-Application-Lifecycle/) | ConfigMaps, Secrets, Environment and Volumes, Configuration Reload, Probes, Graceful Termination, Pod Lifecycle, Application Dependencies, Image Pull Credentials. |
| [Scheduling Placement and Resource Management](09-Scheduling-Placement-and-Resource-Management/) | Requests and Limits, Affinity and Anti Affinity, Taints and Tolerations, Topology Spread, Priority and Preemption, Scheduler Configuration, ResourceQuota, LimitRange, PodDisruptionBudget, Dynamic Resource Allocation. |
| [Networking CNI and Service Discovery](10-Networking-CNI-and-Service-Discovery/) | Pod Networking, Services, EndpointSlices, CoreDNS, kube proxy, CNI, Calico, Cilium, NetworkPolicy, Dual Stack, Egress, Network Diagnostics. |
| [Ingress Gateway API and Traffic Management](11-Ingress-Gateway-API-and-Traffic-Management/) | Ingress, IngressClass, GatewayClass, Gateway, HTTPRoute, GRPCRoute, TLSRoute, TCPRoute, UDPRoute, ReferenceGrant, TLS and Certificates, Traffic Splitting, Controller Selection, Ingress NGINX Legacy and Migration. |
| [Storage CSI and Stateful Applications](12-Storage-CSI-and-Stateful-Applications/) | Volumes, PersistentVolumes, PersistentVolumeClaims, StorageClass, CSI, CSIDriver, CSINode, VolumeAttachment, Snapshots, Expansion, Access Modes, Stateful Recovery, Database Operators. |
| [Identity RBAC and Access Control](13-Identity-RBAC-and-Access-Control/) | ServiceAccounts, Authentication, Authorization, Roles, RoleBindings, ClusterRoles, ClusterRoleBindings, Tokens, OIDC, CertificateSigningRequests, Cloud Workload Identity. |
| [Security Policy and Supply Chain](14-Security-Policy-and-Supply-Chain/) | Pod Security Standards, SecurityContext, Admission Policy, Kyverno, OPA Gatekeeper, Secrets Encryption, Image Scanning, Signing and Provenance, Runtime Security, Falco, Trivy, Threat Modeling. |
| [Observability Metrics Logs and Traces](15-Observability-Metrics-Logs-and-Traces/) | Prometheus, Grafana, kube state metrics, Metrics Server, OpenTelemetry, Loki, Fluent Bit, Jaeger, Tempo, Alertmanager, Audit Logs, Service Level Indicators. |
| [Autoscaling Capacity and Performance](16-Autoscaling-Capacity-and-Performance/) | Horizontal Pod Autoscaling, Vertical Pod Autoscaling, Cluster Autoscaler, Karpenter, KEDA, Custom and External Metrics, Capacity Planning, Load Testing, CPU Throttling, Memory Pressure. |
| [Helm Kustomize and Package Management](17-Helm-Kustomize-and-Package-Management/) | Helm Charts, Values and Templates, Chart Dependencies, Release Management, OCI Registries, Kustomize Bases and Overlays, Patches, Generators, Manifest Validation. |
| [CI CD GitOps and Progressive Delivery](18-CI-CD-GitOps-and-Progressive-Delivery/) | Argo CD, Flux, Jenkins, GitHub Actions, GitLab CI, Tekton, Argo Rollouts, Flagger, Canary and Blue Green, Deployment Gates, GitOps Recovery. |
| [Service Mesh and Advanced Traffic](19-Service-Mesh-and-Advanced-Traffic/) | Istio, Linkerd, Envoy, Mutual TLS, Traffic Policy, Telemetry, Ambient and Sidecar Models, Mesh Troubleshooting. |
| [CRDs Operators and API Extensions](20-CRDs-Operators-and-API-Extensions/) | CustomResourceDefinitions, Custom Resources, Operators, Kubebuilder, Operator SDK, Admission Webhooks, Conversion Webhooks, Aggregated APIs, APIService, Finalizers, Controller Testing. |
| [Multi Tenancy and Platform Engineering](21-Multi-Tenancy-and-Platform-Engineering/) | Namespace Tenancy, Isolation Boundaries, Resource Quotas, Policy Enforcement, Self Service, Backstage, Crossplane, Platform APIs, Developer Experience. |
| [Managed Kubernetes and Cloud Integration](22-Managed-Kubernetes-and-Cloud-Integration/) | Amazon EKS, Azure AKS, Google GKE, Cloud Networking, Cloud Storage, Load Balancer Controllers, Workload Identity, Managed Control Planes, Cloud Costs. |
| [On Premises Hybrid Edge and Windows](23-On-Premises-Hybrid-Edge-and-Windows/) | Bare Metal, MetalLB, k3s, Edge Connectivity, Hybrid Networking, Disconnected Clusters, Windows Workloads, Multi Architecture Images. |
| [Reliability Backup and Disaster Recovery](24-Reliability-Backup-and-Disaster-Recovery/) | etcd Backups, Velero, Application Backups, Restore Testing, Failure Domains, Recovery Objectives, Control Plane Recovery, Cluster Rebuilds. |
| [Production Operations and CloudOps](25-Production-Operations-and-CloudOps/) | Operational Readiness, Runbooks, Change Management, Certificates and Rotation, Node Maintenance, Patch and Upgrade, Incident Response, Audit Evidence. |
| [Troubleshooting and Incident Response](26-Troubleshooting-and-Incident-Response/) | CrashLoopBackOff, ImagePullBackOff, Pending Pods, OOMKilled, DNS Failures, Service Connectivity, Ingress Failures, Storage Failures, Node NotReady, Control Plane Failures, Admission Failures, etcd Latency. |
| [Architecture Patterns](27-Architecture-Patterns/) | Stateless Web, Stateful Service, Event Driven, Batch and Scheduled, Multi Tenant, Private Platform, Multi Cluster, GitOps Platform, Observability Stack. |
| [Cost Management and FinOps](28-Cost-Management-and-FinOps/) | Resource Efficiency, Rightsizing, Node Utilization, Idle Resources, Storage and Network Costs, Kubecost, OpenCost, Cost Allocation. |
| [Specialized Workloads](29-Specialized-Workloads/) | GPU and Accelerators, AI and ML, Distributed Training, Batch and HPC, Data Platforms, Real Time Applications, DRA, Device Plugins, Topology Management. |
| [Projects](30-Projects/) | Junior, Mid Level, Senior, Portfolio Capstones. |
| [Labs](31-Labs/) | Junior, Mid Level, Senior. |
| [Interview Preparation](32-Interview-Preparation/) | Junior, Mid Level, Senior, Architecture Discussions. |
| [Certification Preparation](33-Certification-Preparation/) | CKA, CKAD, CKS, KCNA, KCSA. |
| [Engineer Notebooks](34-Engineer-Notebooks/) | Notebook Standards, Evidence and Redaction, Junior, Mid Level, Senior, Shared Templates. |
| [Toolkit and Automation](35-Toolkit-and-Automation/) | kubectl Cheat Sheets, Shell Scripts, Python Clients, Manifest Templates, Helm Templates, Kustomize Templates, Diagnostics, Cleanup Checklists. |
| [Kubernetes API Resource Catalog](36-Kubernetes-API-Resource-Catalog/) | API Discovery, Scope and Versions, Deprecations and Migrations. |
| [Ecosystem and Extension Resource Catalog](37-Ecosystem-and-Extension-Resource-Catalog/) | Gateway API, CSI Snapshots, Prometheus Operator, cert manager, Argo CD, Flux, Kyverno, Cilium, Istio, Crossplane, KEDA. |
| [Resources and Official References](38-Resources-and-Official-References/) | Official Documentation, API Reference, Release Notes, Enhancement Proposals, Community and SIGs. |
| [Versioning Compatibility and Deprecations](39-Versioning-Compatibility-and-Deprecations/) | Supported Versions, Feature Gates, API Availability, Upgrade Compatibility, Component Compatibility, Deprecated APIs, Extension Version Matrix. |

## Understand the cluster

The Kubernetes API connects the components that persist state, schedule Pods, reconcile resources, and execute workloads. Follow these relationships when reasoning about behaviour or investigating a failure.

<img src="assets/diagrams/cluster-architecture.png" width="560" alt="Kubernetes API relationships with etcd, scheduler, controllers, and a worker node">

## Kubernetes API resource catalogue

Explore resources by kind, API group, version, and scope. Use cluster API discovery and compatibility guidance to establish which resources are available in your environment. Some kinds represent requests or reviews rather than persistent workload objects.

| Resource kind | Icon | API group | Versions | Scope | Learn |
|---|---|---|---|---|---|
| MutatingAdmissionPolicy | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingAdmissionPolicy, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingAdmissionPolicy/) |
| MutatingAdmissionPolicyBinding | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingAdmissionPolicyBinding, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingAdmissionPolicyBinding/) |
| MutatingWebhookConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="MutatingWebhookConfiguration, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/MutatingWebhookConfiguration/) |
| ValidatingAdmissionPolicy | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingAdmissionPolicy, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingAdmissionPolicy/) |
| ValidatingAdmissionPolicyBinding | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingAdmissionPolicyBinding, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingAdmissionPolicyBinding/) |
| ValidatingWebhookConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="ValidatingWebhookConfiguration, Kubernetes resource"/> | `admissionregistration.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/admissionregistration-k8s-io/ValidatingWebhookConfiguration/) |
| CustomResourceDefinition | <img src="assets/resource-icons/resources/unlabeled/crd.svg" width="30" alt="CustomResourceDefinition, Kubernetes resource"/> | `apiextensions.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/apiextensions-k8s-io/CustomResourceDefinition/) |
| APIService | <img src="assets/logos/kubernetes.svg" width="30" alt="APIService, Kubernetes resource"/> | `apiregistration.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/apiregistration-k8s-io/APIService/) |
| ControllerRevision | <img src="assets/logos/kubernetes.svg" width="30" alt="ControllerRevision, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/apps/ControllerRevision/) |
| DaemonSet | <img src="assets/resource-icons/resources/unlabeled/ds.svg" width="30" alt="DaemonSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/apps/DaemonSet/) |
| Deployment | <img src="assets/resource-icons/resources/unlabeled/deploy.svg" width="30" alt="Deployment, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/apps/Deployment/) |
| ReplicaSet | <img src="assets/resource-icons/resources/unlabeled/rs.svg" width="30" alt="ReplicaSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/apps/ReplicaSet/) |
| StatefulSet | <img src="assets/resource-icons/resources/unlabeled/sts.svg" width="30" alt="StatefulSet, Kubernetes resource"/> | `apps` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/apps/StatefulSet/) |
| SelfSubjectReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectReview, Kubernetes resource"/> | `authentication.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/authentication-k8s-io/SelfSubjectReview/) |
| TokenReview | <img src="assets/logos/kubernetes.svg" width="30" alt="TokenReview, Kubernetes resource"/> | `authentication.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/authentication-k8s-io/TokenReview/) |
| LocalSubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="LocalSubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/LocalSubjectAccessReview/) |
| SelfSubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SelfSubjectAccessReview/) |
| SelfSubjectRulesReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SelfSubjectRulesReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SelfSubjectRulesReview/) |
| SubjectAccessReview | <img src="assets/logos/kubernetes.svg" width="30" alt="SubjectAccessReview, Kubernetes resource"/> | `authorization.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/authorization-k8s-io/SubjectAccessReview/) |
| HorizontalPodAutoscaler | <img src="assets/resource-icons/resources/unlabeled/hpa.svg" width="30" alt="HorizontalPodAutoscaler, Kubernetes resource"/> | `autoscaling` | v1, v2 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/autoscaling/HorizontalPodAutoscaler/) |
| CronJob | <img src="assets/resource-icons/resources/unlabeled/cronjob.svg" width="30" alt="CronJob, Kubernetes resource"/> | `batch` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/batch/CronJob/) |
| Job | <img src="assets/resource-icons/resources/unlabeled/job.svg" width="30" alt="Job, Kubernetes resource"/> | `batch` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/batch/Job/) |
| CertificateSigningRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="CertificateSigningRequest, Kubernetes resource"/> | `certificates.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/CertificateSigningRequest/) |
| ClusterTrustBundle | <img src="assets/logos/kubernetes.svg" width="30" alt="ClusterTrustBundle, Kubernetes resource"/> | `certificates.k8s.io` | v1, v1beta1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/ClusterTrustBundle/) |
| PodCertificateRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="PodCertificateRequest, Kubernetes resource"/> | `certificates.k8s.io` | v1, v1beta1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/certificates-k8s-io/PodCertificateRequest/) |
| Lease | <img src="assets/logos/kubernetes.svg" width="30" alt="Lease, Kubernetes resource"/> | `coordination.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/coordination-k8s-io/Lease/) |
| LeaseCandidate | <img src="assets/logos/kubernetes.svg" width="30" alt="LeaseCandidate, Kubernetes resource"/> | `coordination.k8s.io` | v1alpha2, v1beta1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/coordination-k8s-io/LeaseCandidate/) |
| Binding | <img src="assets/logos/kubernetes.svg" width="30" alt="Binding, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Binding/) |
| ComponentStatus | <img src="assets/logos/kubernetes.svg" width="30" alt="ComponentStatus, Kubernetes resource"/> | `core` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/core/ComponentStatus/) |
| ConfigMap | <img src="assets/resource-icons/resources/unlabeled/cm.svg" width="30" alt="ConfigMap, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/ConfigMap/) |
| Endpoints | <img src="assets/logos/kubernetes.svg" width="30" alt="Endpoints, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Endpoints/) |
| Event | <img src="assets/logos/kubernetes.svg" width="30" alt="Event, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Event/) |
| LimitRange | <img src="assets/resource-icons/resources/unlabeled/limits.svg" width="30" alt="LimitRange, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/LimitRange/) |
| Namespace | <img src="assets/resource-icons/resources/unlabeled/ns.svg" width="30" alt="Namespace, Kubernetes resource"/> | `core` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/core/Namespace/) |
| Node | <img src="assets/resource-icons/infrastructure_components/unlabeled/node.svg" width="30" alt="Node, Kubernetes resource"/> | `core` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/core/Node/) |
| PersistentVolume | <img src="assets/resource-icons/resources/unlabeled/pv.svg" width="30" alt="PersistentVolume, Kubernetes resource"/> | `core` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/core/PersistentVolume/) |
| PersistentVolumeClaim | <img src="assets/resource-icons/resources/unlabeled/pvc.svg" width="30" alt="PersistentVolumeClaim, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/PersistentVolumeClaim/) |
| Pod | <img src="assets/resource-icons/resources/unlabeled/pod.svg" width="30" alt="Pod, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Pod/) |
| PodTemplate | <img src="assets/logos/kubernetes.svg" width="30" alt="PodTemplate, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/PodTemplate/) |
| ReplicationController | <img src="assets/logos/kubernetes.svg" width="30" alt="ReplicationController, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/ReplicationController/) |
| ResourceQuota | <img src="assets/resource-icons/resources/unlabeled/quota.svg" width="30" alt="ResourceQuota, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/ResourceQuota/) |
| Secret | <img src="assets/resource-icons/resources/unlabeled/secret.svg" width="30" alt="Secret, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Secret/) |
| Service | <img src="assets/resource-icons/resources/unlabeled/svc.svg" width="30" alt="Service, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/Service/) |
| ServiceAccount | <img src="assets/resource-icons/resources/unlabeled/sa.svg" width="30" alt="ServiceAccount, Kubernetes resource"/> | `core` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/core/ServiceAccount/) |
| EndpointSlice | <img src="assets/logos/kubernetes.svg" width="30" alt="EndpointSlice, Kubernetes resource"/> | `discovery.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/discovery-k8s-io/EndpointSlice/) |
| Event | <img src="assets/logos/kubernetes.svg" width="30" alt="Event, Kubernetes resource"/> | `events.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/events-k8s-io/Event/) |
| FlowSchema | <img src="assets/logos/kubernetes.svg" width="30" alt="FlowSchema, Kubernetes resource"/> | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/flowcontrol-apiserver-k8s-io/FlowSchema/) |
| PriorityLevelConfiguration | <img src="assets/logos/kubernetes.svg" width="30" alt="PriorityLevelConfiguration, Kubernetes resource"/> | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/flowcontrol-apiserver-k8s-io/PriorityLevelConfiguration/) |
| StorageVersion | <img src="assets/logos/kubernetes.svg" width="30" alt="StorageVersion, Kubernetes resource"/> | `internal.apiserver.k8s.io` | v1alpha1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/internal-apiserver-k8s-io/StorageVersion/) |
| Eviction | <img src="assets/logos/kubernetes.svg" width="30" alt="Eviction, Kubernetes resource"/> | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/lifecycle-k8s-io/Eviction/) |
| EvictionRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="EvictionRequest, Kubernetes resource"/> | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/lifecycle-k8s-io/EvictionRequest/) |
| IPAddress | <img src="assets/logos/kubernetes.svg" width="30" alt="IPAddress, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/IPAddress/) |
| Ingress | <img src="assets/resource-icons/resources/unlabeled/ing.svg" width="30" alt="Ingress, Kubernetes resource"/> | `networking.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/Ingress/) |
| IngressClass | <img src="assets/logos/kubernetes.svg" width="30" alt="IngressClass, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/IngressClass/) |
| NetworkPolicy | <img src="assets/resource-icons/resources/unlabeled/netpol.svg" width="30" alt="NetworkPolicy, Kubernetes resource"/> | `networking.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/NetworkPolicy/) |
| ServiceCIDR | <img src="assets/logos/kubernetes.svg" width="30" alt="ServiceCIDR, Kubernetes resource"/> | `networking.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/networking-k8s-io/ServiceCIDR/) |
| RuntimeClass | <img src="assets/logos/kubernetes.svg" width="30" alt="RuntimeClass, Kubernetes resource"/> | `node.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/node-k8s-io/RuntimeClass/) |
| PodDisruptionBudget | <img src="assets/logos/kubernetes.svg" width="30" alt="PodDisruptionBudget, Kubernetes resource"/> | `policy` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/policy/PodDisruptionBudget/) |
| ClusterRole | <img src="assets/resource-icons/resources/unlabeled/c-role.svg" width="30" alt="ClusterRole, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/ClusterRole/) |
| ClusterRoleBinding | <img src="assets/resource-icons/resources/unlabeled/crb.svg" width="30" alt="ClusterRoleBinding, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/ClusterRoleBinding/) |
| Role | <img src="assets/resource-icons/resources/unlabeled/role.svg" width="30" alt="Role, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/Role/) |
| RoleBinding | <img src="assets/resource-icons/resources/unlabeled/rb.svg" width="30" alt="RoleBinding, Kubernetes resource"/> | `rbac.authorization.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/rbac-authorization-k8s-io/RoleBinding/) |
| DeviceClass | <img src="assets/logos/kubernetes.svg" width="30" alt="DeviceClass, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/DeviceClass/) |
| DeviceTaintRule | <img src="assets/logos/kubernetes.svg" width="30" alt="DeviceTaintRule, Kubernetes resource"/> | `resource.k8s.io` | v1, v1alpha3, v1beta2 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/DeviceTaintRule/) |
| ResourceClaim | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceClaim, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceClaim/) |
| ResourceClaimTemplate | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceClaimTemplate, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceClaimTemplate/) |
| ResourcePoolStatusRequest | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourcePoolStatusRequest, Kubernetes resource"/> | `resource.k8s.io` | v1alpha3 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourcePoolStatusRequest/) |
| ResourceSlice | <img src="assets/logos/kubernetes.svg" width="30" alt="ResourceSlice, Kubernetes resource"/> | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/resource-k8s-io/ResourceSlice/) |
| CompositePodGroup | <img src="assets/logos/kubernetes.svg" width="30" alt="CompositePodGroup, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/CompositePodGroup/) |
| PodGroup | <img src="assets/logos/kubernetes.svg" width="30" alt="PodGroup, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/PodGroup/) |
| PriorityClass | <img src="assets/logos/kubernetes.svg" width="30" alt="PriorityClass, Kubernetes resource"/> | `scheduling.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/PriorityClass/) |
| Workload | <img src="assets/logos/kubernetes.svg" width="30" alt="Workload, Kubernetes resource"/> | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/scheduling-k8s-io/Workload/) |
| CSIDriver | <img src="assets/logos/kubernetes.svg" width="30" alt="CSIDriver, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSIDriver/) |
| CSINode | <img src="assets/logos/kubernetes.svg" width="30" alt="CSINode, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSINode/) |
| CSIStorageCapacity | <img src="assets/logos/kubernetes.svg" width="30" alt="CSIStorageCapacity, Kubernetes resource"/> | `storage.k8s.io` | v1 | Namespaced | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/CSIStorageCapacity/) |
| StorageClass | <img src="assets/resource-icons/resources/unlabeled/sc.svg" width="30" alt="StorageClass, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/StorageClass/) |
| VolumeAttachment | <img src="assets/logos/kubernetes.svg" width="30" alt="VolumeAttachment, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/VolumeAttachment/) |
| VolumeAttributesClass | <img src="assets/logos/kubernetes.svg" width="30" alt="VolumeAttributesClass, Kubernetes resource"/> | `storage.k8s.io` | v1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storage-k8s-io/VolumeAttributesClass/) |
| StorageVersionMigration | <img src="assets/logos/kubernetes.svg" width="30" alt="StorageVersionMigration, Kubernetes resource"/> | `storagemigration.k8s.io` | v1, v1beta1 | Cluster | [Explore](36-Kubernetes-API-Resource-Catalog/storagemigration-k8s-io/StorageVersionMigration/) |

[Explore the API catalogue](36-Kubernetes-API-Resource-Catalog/) | [Versioning and compatibility](39-Versioning-Compatibility-and-Deprecations/)

## Extensions and ecosystem resources

Kubernetes extensions introduce their own APIs and operating models. Explore Gateway API, snapshots, observability operators, certificate management, GitOps, policy, networking, platform APIs, and autoscaling in their installation and version context.

[Explore extension resources](37-Ecosystem-and-Extension-Resource-Catalog/) | [CRDs and operators](20-CRDs-Operators-and-API-Extensions/)

<img src="assets/galleries/ecosystem-01.png" width="460" alt="Kubernetes ecosystem project logos, gallery 1">

<img src="assets/galleries/ecosystem-02.png" width="460" alt="Kubernetes ecosystem project logos, gallery 2">

<img src="assets/galleries/ecosystem-03.png" width="460" alt="Kubernetes ecosystem project logos, gallery 3">

## Connect resources to application behaviour

A workload specification, its controller, the scheduler, and the node runtime participate in different parts of the application lifecycle. Services and EndpointSlices connect traffic to backends. Storage claims connect applications to persistent volumes.

<img src="assets/galleries/api-resources-01.png" width="460" alt="Kubernetes workload lifecycle from specification to running containers">
<img src="assets/galleries/api-resources-02.png" width="460" alt="Service discovery and connectivity to ready Pods">
<img src="assets/galleries/api-resources-03.png" width="460" alt="Stateful application identity, volume claims, binding, and recovery">

## Learn through engineering practice

1. Understand the resource and the behaviour it controls.
2. Apply a small change in a controlled environment.
3. Observe events, logs, metrics, and the resulting object state.
4. Introduce a failure and explain what the evidence shows.
5. Verify recovery and record the operational lesson.

For production changes, consider impact, permissions, rollback, capacity, and verification. Keep workload data and credentials out of shared evidence.

[Engineer notebooks](34-Engineer-Notebooks/) | [Toolkit and automation](35-Toolkit-and-Automation/) | [Production operations](25-Production-Operations-and-CloudOps/)

## Design for production

Connect scheduling, tenancy, identity, connectivity, state, delivery, and observability. Explore managed clusters, on-premises and edge systems, multi-cluster platforms, recovery, FinOps, and specialised GPU and data workloads.

[Architecture patterns](27-Architecture-Patterns/) | [Reliability and recovery](24-Reliability-Backup-and-Disaster-Recovery/) | [Platform engineering](21-Multi-Tenancy-and-Platform-Engineering/) | [Specialised workloads](29-Specialized-Workloads/)

## References and project information

[Official references](38-Resources-and-Official-References/) | [Contributing](CONTRIBUTING.md) | [Resource standard](RESOURCE-STANDARD.md) | [Roadmap](ROADMAP.md) | [Security](SECURITY.md) | [Support](SUPPORT.md) | [License](LICENSE)

Third-party project names and logos belong to their owners. Inclusion does not imply endorsement. See [asset sources](docs/ASSET-SOURCES.json).
