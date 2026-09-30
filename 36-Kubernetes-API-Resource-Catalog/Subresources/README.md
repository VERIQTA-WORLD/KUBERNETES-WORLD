# API subresource operations

Subresource paths from the same official API specification. These are operations on resources, not additional independent resource kinds. Reserved notes are empty.

| Path | HTTP methods | Notes |
|---|---|---|
| `/api/v1/namespaces/{namespace}/persistentvolumeclaims/{name}/status` | GET, PATCH, PUT | [Reserved file](001-status.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/attach` | GET, POST | [Reserved file](002-attach.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/binding` | POST | [Reserved file](003-binding.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/ephemeralcontainers` | GET, PATCH, PUT | [Reserved file](004-ephemeralcontainers.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/eviction` | POST | [Reserved file](005-eviction.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/exec` | GET, POST | [Reserved file](006-exec.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/log` | GET | [Reserved file](007-log.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/portforward` | GET, POST | [Reserved file](008-portforward.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/proxy` | DELETE, GET, PATCH, POST, PUT | [Reserved file](009-proxy.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/resize` | GET, PATCH, PUT | [Reserved file](010-resize.md) |
| `/api/v1/namespaces/{namespace}/pods/{name}/status` | GET, PATCH, PUT | [Reserved file](011-status.md) |
| `/api/v1/namespaces/{namespace}/replicationcontrollers/{name}/scale` | GET, PATCH, PUT | [Reserved file](012-scale.md) |
| `/api/v1/namespaces/{namespace}/replicationcontrollers/{name}/status` | GET, PATCH, PUT | [Reserved file](013-status.md) |
| `/api/v1/namespaces/{namespace}/resourcequotas/{name}/status` | GET, PATCH, PUT | [Reserved file](014-status.md) |
| `/api/v1/namespaces/{namespace}/serviceaccounts/{name}/token` | POST | [Reserved file](015-token.md) |
| `/api/v1/namespaces/{namespace}/services/{name}/proxy` | DELETE, GET, PATCH, POST, PUT | [Reserved file](016-proxy.md) |
| `/api/v1/namespaces/{namespace}/services/{name}/status` | GET, PATCH, PUT | [Reserved file](017-status.md) |
| `/api/v1/namespaces/{name}/finalize` | PUT | [Reserved file](018-finalize.md) |
| `/api/v1/namespaces/{name}/status` | GET, PATCH, PUT | [Reserved file](019-status.md) |
| `/api/v1/nodes/{name}/proxy` | DELETE, GET, PATCH, POST, PUT | [Reserved file](020-proxy.md) |
| `/api/v1/nodes/{name}/status` | GET, PATCH, PUT | [Reserved file](021-status.md) |
| `/api/v1/persistentvolumes/{name}/status` | GET, PATCH, PUT | [Reserved file](022-status.md) |
| `/apis/admissionregistration.k8s.io/v1/validatingadmissionpolicies/{name}/status` | GET, PATCH, PUT | [Reserved file](023-status.md) |
| `/apis/apiextensions.k8s.io/v1/customresourcedefinitions/{name}/status` | GET, PATCH, PUT | [Reserved file](024-status.md) |
| `/apis/apiregistration.k8s.io/v1/apiservices/{name}/status` | GET, PATCH, PUT | [Reserved file](025-status.md) |
| `/apis/apps/v1/namespaces/{namespace}/daemonsets/{name}/status` | GET, PATCH, PUT | [Reserved file](026-status.md) |
| `/apis/apps/v1/namespaces/{namespace}/deployments/{name}/scale` | GET, PATCH, PUT | [Reserved file](027-scale.md) |
| `/apis/apps/v1/namespaces/{namespace}/deployments/{name}/status` | GET, PATCH, PUT | [Reserved file](028-status.md) |
| `/apis/apps/v1/namespaces/{namespace}/replicasets/{name}/scale` | GET, PATCH, PUT | [Reserved file](029-scale.md) |
| `/apis/apps/v1/namespaces/{namespace}/replicasets/{name}/status` | GET, PATCH, PUT | [Reserved file](030-status.md) |
| `/apis/apps/v1/namespaces/{namespace}/statefulsets/{name}/scale` | GET, PATCH, PUT | [Reserved file](031-scale.md) |
| `/apis/apps/v1/namespaces/{namespace}/statefulsets/{name}/status` | GET, PATCH, PUT | [Reserved file](032-status.md) |
| `/apis/autoscaling/v1/namespaces/{namespace}/horizontalpodautoscalers/{name}/status` | GET, PATCH, PUT | [Reserved file](033-status.md) |
| `/apis/autoscaling/v2/namespaces/{namespace}/horizontalpodautoscalers/{name}/status` | GET, PATCH, PUT | [Reserved file](034-status.md) |
| `/apis/batch/v1/namespaces/{namespace}/cronjobs/{name}/status` | GET, PATCH, PUT | [Reserved file](035-status.md) |
| `/apis/batch/v1/namespaces/{namespace}/jobs/{name}/status` | GET, PATCH, PUT | [Reserved file](036-status.md) |
| `/apis/certificates.k8s.io/v1/certificatesigningrequests/{name}/approval` | GET, PATCH, PUT | [Reserved file](037-approval.md) |
| `/apis/certificates.k8s.io/v1/certificatesigningrequests/{name}/status` | GET, PATCH, PUT | [Reserved file](038-status.md) |
| `/apis/certificates.k8s.io/v1/namespaces/{namespace}/podcertificaterequests/{name}/status` | GET, PATCH, PUT | [Reserved file](039-status.md) |
| `/apis/certificates.k8s.io/v1beta1/namespaces/{namespace}/podcertificaterequests/{name}/status` | GET, PATCH, PUT | [Reserved file](040-status.md) |
| `/apis/flowcontrol.apiserver.k8s.io/v1/flowschemas/{name}/status` | GET, PATCH, PUT | [Reserved file](041-status.md) |
| `/apis/flowcontrol.apiserver.k8s.io/v1/prioritylevelconfigurations/{name}/status` | GET, PATCH, PUT | [Reserved file](042-status.md) |
| `/apis/internal.apiserver.k8s.io/v1alpha1/storageversions/{name}/status` | GET, PATCH, PUT | [Reserved file](043-status.md) |
| `/apis/lifecycle.k8s.io/v1alpha1/namespaces/{namespace}/evictionrequests/{name}/status` | GET, PATCH, PUT | [Reserved file](044-status.md) |
| `/apis/lifecycle.k8s.io/v1alpha1/namespaces/{namespace}/evictions/{name}/status` | GET, PATCH, PUT | [Reserved file](045-status.md) |
| `/apis/networking.k8s.io/v1/namespaces/{namespace}/ingresses/{name}/status` | GET, PATCH, PUT | [Reserved file](046-status.md) |
| `/apis/networking.k8s.io/v1/servicecidrs/{name}/status` | GET, PATCH, PUT | [Reserved file](047-status.md) |
| `/apis/policy/v1/namespaces/{namespace}/poddisruptionbudgets/{name}/status` | GET, PATCH, PUT | [Reserved file](048-status.md) |
| `/apis/resource.k8s.io/v1/devicetaintrules/{name}/status` | GET, PATCH, PUT | [Reserved file](049-status.md) |
| `/apis/resource.k8s.io/v1/namespaces/{namespace}/resourceclaims/{name}/status` | GET, PATCH, PUT | [Reserved file](050-status.md) |
| `/apis/resource.k8s.io/v1alpha3/devicetaintrules/{name}/status` | GET, PATCH, PUT | [Reserved file](051-status.md) |
| `/apis/resource.k8s.io/v1alpha3/resourcepoolstatusrequests/{name}/status` | GET, PATCH, PUT | [Reserved file](052-status.md) |
| `/apis/resource.k8s.io/v1beta1/namespaces/{namespace}/resourceclaims/{name}/status` | GET, PATCH, PUT | [Reserved file](053-status.md) |
| `/apis/resource.k8s.io/v1beta2/devicetaintrules/{name}/status` | GET, PATCH, PUT | [Reserved file](054-status.md) |
| `/apis/resource.k8s.io/v1beta2/namespaces/{namespace}/resourceclaims/{name}/status` | GET, PATCH, PUT | [Reserved file](055-status.md) |
| `/apis/scheduling.k8s.io/v1alpha3/namespaces/{namespace}/compositepodgroups/{name}/status` | GET, PATCH, PUT | [Reserved file](056-status.md) |
| `/apis/scheduling.k8s.io/v1alpha3/namespaces/{namespace}/podgroups/{name}/status` | GET, PATCH, PUT | [Reserved file](057-status.md) |
| `/apis/scheduling.k8s.io/v1beta1/namespaces/{namespace}/podgroups/{name}/status` | GET, PATCH, PUT | [Reserved file](058-status.md) |
| `/apis/storage.k8s.io/v1/csinodes/{name}/status` | GET, PATCH, PUT | [Reserved file](059-status.md) |
| `/apis/storage.k8s.io/v1/volumeattachments/{name}/status` | GET, PATCH, PUT | [Reserved file](060-status.md) |
| `/apis/storagemigration.k8s.io/v1/storageversionmigrations/{name}/status` | GET, PATCH, PUT | [Reserved file](061-status.md) |
| `/apis/storagemigration.k8s.io/v1beta1/storageversionmigrations/{name}/status` | GET, PATCH, PUT | [Reserved file](062-status.md) |
