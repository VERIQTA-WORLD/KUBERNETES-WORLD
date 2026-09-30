# Kubernetes API Resource Catalog

Inventory generated from the official Kubernetes v1.37.1 OpenAPI specification. This table includes resource collection endpoints, including request/review resources; it does not imply that every kind is persistent or enabled on your cluster.

| Kind | API group | Versions in specification | Scope | Learning folder |
|---|---|---|---|---|
| MutatingAdmissionPolicy | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Open](admissionregistration-k8s-io/MutatingAdmissionPolicy/) |
| MutatingAdmissionPolicyBinding | `admissionregistration.k8s.io` | v1, v1alpha1, v1beta1 | Cluster | [Open](admissionregistration-k8s-io/MutatingAdmissionPolicyBinding/) |
| MutatingWebhookConfiguration | `admissionregistration.k8s.io` | v1 | Cluster | [Open](admissionregistration-k8s-io/MutatingWebhookConfiguration/) |
| ValidatingAdmissionPolicy | `admissionregistration.k8s.io` | v1 | Cluster | [Open](admissionregistration-k8s-io/ValidatingAdmissionPolicy/) |
| ValidatingAdmissionPolicyBinding | `admissionregistration.k8s.io` | v1 | Cluster | [Open](admissionregistration-k8s-io/ValidatingAdmissionPolicyBinding/) |
| ValidatingWebhookConfiguration | `admissionregistration.k8s.io` | v1 | Cluster | [Open](admissionregistration-k8s-io/ValidatingWebhookConfiguration/) |
| CustomResourceDefinition | `apiextensions.k8s.io` | v1 | Cluster | [Open](apiextensions-k8s-io/CustomResourceDefinition/) |
| APIService | `apiregistration.k8s.io` | v1 | Cluster | [Open](apiregistration-k8s-io/APIService/) |
| ControllerRevision | `apps` | v1 | Namespaced | [Open](apps/ControllerRevision/) |
| DaemonSet | `apps` | v1 | Namespaced | [Open](apps/DaemonSet/) |
| Deployment | `apps` | v1 | Namespaced | [Open](apps/Deployment/) |
| ReplicaSet | `apps` | v1 | Namespaced | [Open](apps/ReplicaSet/) |
| StatefulSet | `apps` | v1 | Namespaced | [Open](apps/StatefulSet/) |
| SelfSubjectReview | `authentication.k8s.io` | v1 | Cluster | [Open](authentication-k8s-io/SelfSubjectReview/) |
| TokenReview | `authentication.k8s.io` | v1 | Cluster | [Open](authentication-k8s-io/TokenReview/) |
| LocalSubjectAccessReview | `authorization.k8s.io` | v1 | Namespaced | [Open](authorization-k8s-io/LocalSubjectAccessReview/) |
| SelfSubjectAccessReview | `authorization.k8s.io` | v1 | Cluster | [Open](authorization-k8s-io/SelfSubjectAccessReview/) |
| SelfSubjectRulesReview | `authorization.k8s.io` | v1 | Cluster | [Open](authorization-k8s-io/SelfSubjectRulesReview/) |
| SubjectAccessReview | `authorization.k8s.io` | v1 | Cluster | [Open](authorization-k8s-io/SubjectAccessReview/) |
| HorizontalPodAutoscaler | `autoscaling` | v1, v2 | Namespaced | [Open](autoscaling/HorizontalPodAutoscaler/) |
| CronJob | `batch` | v1 | Namespaced | [Open](batch/CronJob/) |
| Job | `batch` | v1 | Namespaced | [Open](batch/Job/) |
| CertificateSigningRequest | `certificates.k8s.io` | v1 | Cluster | [Open](certificates-k8s-io/CertificateSigningRequest/) |
| ClusterTrustBundle | `certificates.k8s.io` | v1, v1beta1 | Cluster | [Open](certificates-k8s-io/ClusterTrustBundle/) |
| PodCertificateRequest | `certificates.k8s.io` | v1, v1beta1 | Namespaced | [Open](certificates-k8s-io/PodCertificateRequest/) |
| Lease | `coordination.k8s.io` | v1 | Namespaced | [Open](coordination-k8s-io/Lease/) |
| LeaseCandidate | `coordination.k8s.io` | v1alpha2, v1beta1 | Namespaced | [Open](coordination-k8s-io/LeaseCandidate/) |
| Binding | `core` | v1 | Namespaced | [Open](core/Binding/) |
| ComponentStatus | `core` | v1 | Cluster | [Open](core/ComponentStatus/) |
| ConfigMap | `core` | v1 | Namespaced | [Open](core/ConfigMap/) |
| Endpoints | `core` | v1 | Namespaced | [Open](core/Endpoints/) |
| Event | `core` | v1 | Namespaced | [Open](core/Event/) |
| LimitRange | `core` | v1 | Namespaced | [Open](core/LimitRange/) |
| Namespace | `core` | v1 | Cluster | [Open](core/Namespace/) |
| Node | `core` | v1 | Cluster | [Open](core/Node/) |
| PersistentVolume | `core` | v1 | Cluster | [Open](core/PersistentVolume/) |
| PersistentVolumeClaim | `core` | v1 | Namespaced | [Open](core/PersistentVolumeClaim/) |
| Pod | `core` | v1 | Namespaced | [Open](core/Pod/) |
| PodTemplate | `core` | v1 | Namespaced | [Open](core/PodTemplate/) |
| ReplicationController | `core` | v1 | Namespaced | [Open](core/ReplicationController/) |
| ResourceQuota | `core` | v1 | Namespaced | [Open](core/ResourceQuota/) |
| Secret | `core` | v1 | Namespaced | [Open](core/Secret/) |
| Service | `core` | v1 | Namespaced | [Open](core/Service/) |
| ServiceAccount | `core` | v1 | Namespaced | [Open](core/ServiceAccount/) |
| EndpointSlice | `discovery.k8s.io` | v1 | Namespaced | [Open](discovery-k8s-io/EndpointSlice/) |
| Event | `events.k8s.io` | v1 | Namespaced | [Open](events-k8s-io/Event/) |
| FlowSchema | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Open](flowcontrol-apiserver-k8s-io/FlowSchema/) |
| PriorityLevelConfiguration | `flowcontrol.apiserver.k8s.io` | v1 | Cluster | [Open](flowcontrol-apiserver-k8s-io/PriorityLevelConfiguration/) |
| StorageVersion | `internal.apiserver.k8s.io` | v1alpha1 | Cluster | [Open](internal-apiserver-k8s-io/StorageVersion/) |
| Eviction | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Open](lifecycle-k8s-io/Eviction/) |
| EvictionRequest | `lifecycle.k8s.io` | v1alpha1 | Namespaced | [Open](lifecycle-k8s-io/EvictionRequest/) |
| IPAddress | `networking.k8s.io` | v1 | Cluster | [Open](networking-k8s-io/IPAddress/) |
| Ingress | `networking.k8s.io` | v1 | Namespaced | [Open](networking-k8s-io/Ingress/) |
| IngressClass | `networking.k8s.io` | v1 | Cluster | [Open](networking-k8s-io/IngressClass/) |
| NetworkPolicy | `networking.k8s.io` | v1 | Namespaced | [Open](networking-k8s-io/NetworkPolicy/) |
| ServiceCIDR | `networking.k8s.io` | v1 | Cluster | [Open](networking-k8s-io/ServiceCIDR/) |
| RuntimeClass | `node.k8s.io` | v1 | Cluster | [Open](node-k8s-io/RuntimeClass/) |
| PodDisruptionBudget | `policy` | v1 | Namespaced | [Open](policy/PodDisruptionBudget/) |
| ClusterRole | `rbac.authorization.k8s.io` | v1 | Cluster | [Open](rbac-authorization-k8s-io/ClusterRole/) |
| ClusterRoleBinding | `rbac.authorization.k8s.io` | v1 | Cluster | [Open](rbac-authorization-k8s-io/ClusterRoleBinding/) |
| Role | `rbac.authorization.k8s.io` | v1 | Namespaced | [Open](rbac-authorization-k8s-io/Role/) |
| RoleBinding | `rbac.authorization.k8s.io` | v1 | Namespaced | [Open](rbac-authorization-k8s-io/RoleBinding/) |
| DeviceClass | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Open](resource-k8s-io/DeviceClass/) |
| DeviceTaintRule | `resource.k8s.io` | v1, v1alpha3, v1beta2 | Cluster | [Open](resource-k8s-io/DeviceTaintRule/) |
| ResourceClaim | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Open](resource-k8s-io/ResourceClaim/) |
| ResourceClaimTemplate | `resource.k8s.io` | v1, v1beta1, v1beta2 | Namespaced | [Open](resource-k8s-io/ResourceClaimTemplate/) |
| ResourcePoolStatusRequest | `resource.k8s.io` | v1alpha3 | Cluster | [Open](resource-k8s-io/ResourcePoolStatusRequest/) |
| ResourceSlice | `resource.k8s.io` | v1, v1beta1, v1beta2 | Cluster | [Open](resource-k8s-io/ResourceSlice/) |
| CompositePodGroup | `scheduling.k8s.io` | v1alpha3 | Namespaced | [Open](scheduling-k8s-io/CompositePodGroup/) |
| PodGroup | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Open](scheduling-k8s-io/PodGroup/) |
| PriorityClass | `scheduling.k8s.io` | v1 | Cluster | [Open](scheduling-k8s-io/PriorityClass/) |
| Workload | `scheduling.k8s.io` | v1alpha3, v1beta1 | Namespaced | [Open](scheduling-k8s-io/Workload/) |
| CSIDriver | `storage.k8s.io` | v1 | Cluster | [Open](storage-k8s-io/CSIDriver/) |
| CSINode | `storage.k8s.io` | v1 | Cluster | [Open](storage-k8s-io/CSINode/) |
| CSIStorageCapacity | `storage.k8s.io` | v1 | Namespaced | [Open](storage-k8s-io/CSIStorageCapacity/) |
| StorageClass | `storage.k8s.io` | v1 | Cluster | [Open](storage-k8s-io/StorageClass/) |
| VolumeAttachment | `storage.k8s.io` | v1 | Cluster | [Open](storage-k8s-io/VolumeAttachment/) |
| VolumeAttributesClass | `storage.k8s.io` | v1 | Cluster | [Open](storage-k8s-io/VolumeAttributesClass/) |
| StorageVersionMigration | `storagemigration.k8s.io` | v1, v1beta1 | Cluster | [Open](storagemigration-k8s-io/StorageVersionMigration/) |

Feature gates, runtime configuration, API lifecycle, and distribution affect availability. Discover your cluster with `kubectl api-resources` and `kubectl api-versions`.

[Source specification](https://raw.githubusercontent.com/kubernetes/kubernetes/v1.37.1/api/openapi-spec/swagger.json)

[Subresource operations](Subresources/)
