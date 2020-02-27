
## deployment
DEPRECATED - This group version of Deployment is deprecated by apps/v1/Deployment. See the release notes for more information. Deployment enables declarative updates for Pods and ReplicaSets.

**Functions:**

[`fn new`](#fn-new)  
[`fn metadata.withAnnotations`](#fn-metadatawithannotations)  
[`fn metadata.withClusterName`](#fn-metadatawithclustername)  
[`fn metadata.withCreationTimestamp`](#fn-metadatawithcreationtimestamp)  
[`fn metadata.withDeletionGracePeriodSeconds`](#fn-metadatawithdeletiongraceperiodseconds)  
[`fn metadata.withDeletionTimestamp`](#fn-metadatawithdeletiontimestamp)  
[`fn metadata.withFinalizers`](#fn-metadatawithfinalizers)  
[`fn metadata.withGenerateName`](#fn-metadatawithgeneratename)  
[`fn metadata.withGeneration`](#fn-metadatawithgeneration)  
[`fn metadata.withLabels`](#fn-metadatawithlabels)  
[`fn metadata.withManagedFields`](#fn-metadatawithmanagedfields)  
[`fn metadata.withName`](#fn-metadatawithname)  
[`fn metadata.withNamespace`](#fn-metadatawithnamespace)  
[`fn metadata.withOwnerReferences`](#fn-metadatawithownerreferences)  
[`fn metadata.withResourceVersion`](#fn-metadatawithresourceversion)  
[`fn metadata.withSelfLink`](#fn-metadatawithselflink)  
[`fn metadata.withUid`](#fn-metadatawithuid)  
[`fn spec.selector.withMatchExpressions`](#fn-specselectorwithmatchexpressions)  
[`fn spec.selector.withMatchLabels`](#fn-specselectorwithmatchlabels)  
[`fn spec.strategy.rollingUpdate.withMaxSurge`](#fn-specstrategyrollingupdatewithmaxsurge)  
[`fn spec.strategy.rollingUpdate.withMaxUnavailable`](#fn-specstrategyrollingupdatewithmaxunavailable)  
[`fn spec.strategy.withType`](#fn-specstrategywithtype)  
[`fn spec.template.metadata.withAnnotations`](#fn-spectemplatemetadatawithannotations)  
[`fn spec.template.metadata.withClusterName`](#fn-spectemplatemetadatawithclustername)  
[`fn spec.template.metadata.withCreationTimestamp`](#fn-spectemplatemetadatawithcreationtimestamp)  
[`fn spec.template.metadata.withDeletionGracePeriodSeconds`](#fn-spectemplatemetadatawithdeletiongraceperiodseconds)  
[`fn spec.template.metadata.withDeletionTimestamp`](#fn-spectemplatemetadatawithdeletiontimestamp)  
[`fn spec.template.metadata.withFinalizers`](#fn-spectemplatemetadatawithfinalizers)  
[`fn spec.template.metadata.withGenerateName`](#fn-spectemplatemetadatawithgeneratename)  
[`fn spec.template.metadata.withGeneration`](#fn-spectemplatemetadatawithgeneration)  
[`fn spec.template.metadata.withLabels`](#fn-spectemplatemetadatawithlabels)  
[`fn spec.template.metadata.withManagedFields`](#fn-spectemplatemetadatawithmanagedfields)  
[`fn spec.template.metadata.withName`](#fn-spectemplatemetadatawithname)  
[`fn spec.template.metadata.withNamespace`](#fn-spectemplatemetadatawithnamespace)  
[`fn spec.template.metadata.withOwnerReferences`](#fn-spectemplatemetadatawithownerreferences)  
[`fn spec.template.metadata.withResourceVersion`](#fn-spectemplatemetadatawithresourceversion)  
[`fn spec.template.metadata.withSelfLink`](#fn-spectemplatemetadatawithselflink)  
[`fn spec.template.metadata.withUid`](#fn-spectemplatemetadatawithuid)  
[`fn spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms`](#fn-spectemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)  
[`fn spec.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`](#fn-spectemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)  
[`fn spec.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`](#fn-spectemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)  
[`fn spec.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution`](#fn-spectemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)  
[`fn spec.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`](#fn-spectemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)  
[`fn spec.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution`](#fn-spectemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)  
[`fn spec.template.spec.dnsConfig.withNameservers`](#fn-spectemplatespecdnsconfigwithnameservers)  
[`fn spec.template.spec.dnsConfig.withOptions`](#fn-spectemplatespecdnsconfigwithoptions)  
[`fn spec.template.spec.dnsConfig.withSearches`](#fn-spectemplatespecdnsconfigwithsearches)  
[`fn spec.template.spec.securityContext.seLinuxOptions.withLevel`](#fn-spectemplatespecsecuritycontextselinuxoptionswithlevel)  
[`fn spec.template.spec.securityContext.seLinuxOptions.withRole`](#fn-spectemplatespecsecuritycontextselinuxoptionswithrole)  
[`fn spec.template.spec.securityContext.seLinuxOptions.withType`](#fn-spectemplatespecsecuritycontextselinuxoptionswithtype)  
[`fn spec.template.spec.securityContext.seLinuxOptions.withUser`](#fn-spectemplatespecsecuritycontextselinuxoptionswithuser)  
[`fn spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpec`](#fn-spectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)  
[`fn spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpecName`](#fn-spectemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)  
[`fn spec.template.spec.securityContext.windowsOptions.withRunAsUserName`](#fn-spectemplatespecsecuritycontextwindowsoptionswithrunasusername)  
[`fn spec.template.spec.securityContext.withFsGroup`](#fn-spectemplatespecsecuritycontextwithfsgroup)  
[`fn spec.template.spec.securityContext.withRunAsGroup`](#fn-spectemplatespecsecuritycontextwithrunasgroup)  
[`fn spec.template.spec.securityContext.withRunAsNonRoot`](#fn-spectemplatespecsecuritycontextwithrunasnonroot)  
[`fn spec.template.spec.securityContext.withRunAsUser`](#fn-spectemplatespecsecuritycontextwithrunasuser)  
[`fn spec.template.spec.securityContext.withSupplementalGroups`](#fn-spectemplatespecsecuritycontextwithsupplementalgroups)  
[`fn spec.template.spec.securityContext.withSysctls`](#fn-spectemplatespecsecuritycontextwithsysctls)  
[`fn spec.template.spec.withActiveDeadlineSeconds`](#fn-spectemplatespecwithactivedeadlineseconds)  
[`fn spec.template.spec.withAutomountServiceAccountToken`](#fn-spectemplatespecwithautomountserviceaccounttoken)  
[`fn spec.template.spec.withContainers`](#fn-spectemplatespecwithcontainers)  
[`fn spec.template.spec.withDnsPolicy`](#fn-spectemplatespecwithdnspolicy)  
[`fn spec.template.spec.withEnableServiceLinks`](#fn-spectemplatespecwithenableservicelinks)  
[`fn spec.template.spec.withEphemeralContainers`](#fn-spectemplatespecwithephemeralcontainers)  
[`fn spec.template.spec.withHostAliases`](#fn-spectemplatespecwithhostaliases)  
[`fn spec.template.spec.withHostIPC`](#fn-spectemplatespecwithhostipc)  
[`fn spec.template.spec.withHostNetwork`](#fn-spectemplatespecwithhostnetwork)  
[`fn spec.template.spec.withHostPID`](#fn-spectemplatespecwithhostpid)  
[`fn spec.template.spec.withHostname`](#fn-spectemplatespecwithhostname)  
[`fn spec.template.spec.withImagePullSecrets`](#fn-spectemplatespecwithimagepullsecrets)  
[`fn spec.template.spec.withInitContainers`](#fn-spectemplatespecwithinitcontainers)  
[`fn spec.template.spec.withNodeName`](#fn-spectemplatespecwithnodename)  
[`fn spec.template.spec.withNodeSelector`](#fn-spectemplatespecwithnodeselector)  
[`fn spec.template.spec.withOverhead`](#fn-spectemplatespecwithoverhead)  
[`fn spec.template.spec.withPreemptionPolicy`](#fn-spectemplatespecwithpreemptionpolicy)  
[`fn spec.template.spec.withPriority`](#fn-spectemplatespecwithpriority)  
[`fn spec.template.spec.withPriorityClassName`](#fn-spectemplatespecwithpriorityclassname)  
[`fn spec.template.spec.withReadinessGates`](#fn-spectemplatespecwithreadinessgates)  
[`fn spec.template.spec.withRestartPolicy`](#fn-spectemplatespecwithrestartpolicy)  
[`fn spec.template.spec.withRuntimeClassName`](#fn-spectemplatespecwithruntimeclassname)  
[`fn spec.template.spec.withSchedulerName`](#fn-spectemplatespecwithschedulername)  
[`fn spec.template.spec.withServiceAccount`](#fn-spectemplatespecwithserviceaccount)  
[`fn spec.template.spec.withServiceAccountName`](#fn-spectemplatespecwithserviceaccountname)  
[`fn spec.template.spec.withShareProcessNamespace`](#fn-spectemplatespecwithshareprocessnamespace)  
[`fn spec.template.spec.withSubdomain`](#fn-spectemplatespecwithsubdomain)  
[`fn spec.template.spec.withTerminationGracePeriodSeconds`](#fn-spectemplatespecwithterminationgraceperiodseconds)  
[`fn spec.template.spec.withTolerations`](#fn-spectemplatespecwithtolerations)  
[`fn spec.template.spec.withTopologySpreadConstraints`](#fn-spectemplatespecwithtopologyspreadconstraints)  
[`fn spec.template.spec.withVolumes`](#fn-spectemplatespecwithvolumes)  
[`fn spec.withMinReadySeconds`](#fn-specwithminreadyseconds)  
[`fn spec.withPaused`](#fn-specwithpaused)  
[`fn spec.withProgressDeadlineSeconds`](#fn-specwithprogressdeadlineseconds)  
[`fn spec.withReplicas`](#fn-specwithreplicas)  
[`fn spec.withRevisionHistoryLimit`](#fn-specwithrevisionhistorylimit)  

---


### `fn new`
new returns an instance of Deployment
```jsonnet
{
  new(name):: {}
}
```

### `fn metadata.withAnnotations`
Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations
```jsonnet
{
  withAnnotations(annotations):: {}
}
```

### `fn metadata.withClusterName`
The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request.
```jsonnet
{
  withClusterName(clusterName):: {}
}
```

### `fn metadata.withCreationTimestamp`
Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers.
```jsonnet
{
  withCreationTimestamp(creationTimestamp):: {}
}
```

### `fn metadata.withDeletionGracePeriodSeconds`
Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only.
```jsonnet
{
  withDeletionGracePeriodSeconds(deletionGracePeriodSeconds):: {}
}
```

### `fn metadata.withDeletionTimestamp`
Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers.
```jsonnet
{
  withDeletionTimestamp(deletionTimestamp):: {}
}
```

### `fn metadata.withFinalizers`
Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed.
```jsonnet
{
  withFinalizers(finalizers):: {}
}
```

### `fn metadata.withGenerateName`
GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.

If this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).

Applied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency
```jsonnet
{
  withGenerateName(generateName):: {}
}
```

### `fn metadata.withGeneration`
A sequence number representing a specific generation of the desired state. Populated by the system. Read-only.
```jsonnet
{
  withGeneration(generation):: {}
}
```

### `fn metadata.withLabels`
Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels
```jsonnet
{
  withLabels(labels):: {}
}
```

### `fn metadata.withManagedFields`
ManagedFields maps workflow-id and version to the set of fields that are managed by that workflow. This is mostly for internal housekeeping, and users typically shouldn't need to set or understand this field. A workflow can be the user's name, a controller's name, or the name of a specific apply path like "ci-cd". The set of fields is always in the version that the workflow used when modifying the object.
```jsonnet
{
  withManagedFields(managedFields):: {}
}
```

### `fn metadata.withName`
Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names
```jsonnet
{
  withName(name):: {}
}
```

### `fn metadata.withNamespace`
Namespace defines the space within each name must be unique. An empty namespace is equivalent to the "default" namespace, but "default" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.

Must be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces
```jsonnet
{
  withNamespace(namespace):: {}
}
```

### `fn metadata.withOwnerReferences`
List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller.
```jsonnet
{
  withOwnerReferences(ownerReferences):: {}
}
```

### `fn metadata.withResourceVersion`
An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.

Populated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency
```jsonnet
{
  withResourceVersion(resourceVersion):: {}
}
```

### `fn metadata.withSelfLink`
SelfLink is a URL representing this object. Populated by the system. Read-only.

DEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release.
```jsonnet
{
  withSelfLink(selfLink):: {}
}
```

### `fn metadata.withUid`
UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.

Populated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids
```jsonnet
{
  withUid(uid):: {}
}
```

### `fn spec.selector.withMatchExpressions`
matchExpressions is a list of label selector requirements. The requirements are ANDed.
```jsonnet
{
  withMatchExpressions(matchExpressions):: {}
}
```

### `fn spec.selector.withMatchLabels`
matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels map is equivalent to an element of matchExpressions, whose key field is "key", the operator is "In", and the values array contains only "value". The requirements are ANDed.
```jsonnet
{
  withMatchLabels(matchLabels):: {}
}
```

### `fn spec.strategy.rollingUpdate.withMaxSurge`
IntOrString is a type that can hold an int32 or a string.  When used in JSON or YAML marshalling and unmarshalling, it produces or consumes the inner type.  This allows you to have, for example, a JSON field that can accept a name or number.
```jsonnet
{
  withMaxSurge(maxSurge):: {}
}
```

### `fn spec.strategy.rollingUpdate.withMaxUnavailable`
IntOrString is a type that can hold an int32 or a string.  When used in JSON or YAML marshalling and unmarshalling, it produces or consumes the inner type.  This allows you to have, for example, a JSON field that can accept a name or number.
```jsonnet
{
  withMaxUnavailable(maxUnavailable):: {}
}
```

### `fn spec.strategy.withType`
Type of deployment. Can be "Recreate" or "RollingUpdate". Default is RollingUpdate.
```jsonnet
{
  withType(type):: {}
}
```

### `fn spec.template.metadata.withAnnotations`
Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations
```jsonnet
{
  withAnnotations(annotations):: {}
}
```

### `fn spec.template.metadata.withClusterName`
The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request.
```jsonnet
{
  withClusterName(clusterName):: {}
}
```

### `fn spec.template.metadata.withCreationTimestamp`
Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers.
```jsonnet
{
  withCreationTimestamp(creationTimestamp):: {}
}
```

### `fn spec.template.metadata.withDeletionGracePeriodSeconds`
Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only.
```jsonnet
{
  withDeletionGracePeriodSeconds(deletionGracePeriodSeconds):: {}
}
```

### `fn spec.template.metadata.withDeletionTimestamp`
Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers.
```jsonnet
{
  withDeletionTimestamp(deletionTimestamp):: {}
}
```

### `fn spec.template.metadata.withFinalizers`
Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed.
```jsonnet
{
  withFinalizers(finalizers):: {}
}
```

### `fn spec.template.metadata.withGenerateName`
GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.

If this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).

Applied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency
```jsonnet
{
  withGenerateName(generateName):: {}
}
```

### `fn spec.template.metadata.withGeneration`
A sequence number representing a specific generation of the desired state. Populated by the system. Read-only.
```jsonnet
{
  withGeneration(generation):: {}
}
```

### `fn spec.template.metadata.withLabels`
Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels
```jsonnet
{
  withLabels(labels):: {}
}
```

### `fn spec.template.metadata.withManagedFields`
ManagedFields maps workflow-id and version to the set of fields that are managed by that workflow. This is mostly for internal housekeeping, and users typically shouldn't need to set or understand this field. A workflow can be the user's name, a controller's name, or the name of a specific apply path like "ci-cd". The set of fields is always in the version that the workflow used when modifying the object.
```jsonnet
{
  withManagedFields(managedFields):: {}
}
```

### `fn spec.template.metadata.withName`
Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names
```jsonnet
{
  withName(name):: {}
}
```

### `fn spec.template.metadata.withNamespace`
Namespace defines the space within each name must be unique. An empty namespace is equivalent to the "default" namespace, but "default" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.

Must be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces
```jsonnet
{
  withNamespace(namespace):: {}
}
```

### `fn spec.template.metadata.withOwnerReferences`
List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller.
```jsonnet
{
  withOwnerReferences(ownerReferences):: {}
}
```

### `fn spec.template.metadata.withResourceVersion`
An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.

Populated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency
```jsonnet
{
  withResourceVersion(resourceVersion):: {}
}
```

### `fn spec.template.metadata.withSelfLink`
SelfLink is a URL representing this object. Populated by the system. Read-only.

DEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release.
```jsonnet
{
  withSelfLink(selfLink):: {}
}
```

### `fn spec.template.metadata.withUid`
UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.

Populated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids
```jsonnet
{
  withUid(uid):: {}
}
```

### `fn spec.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms`
Required. A list of node selector terms. The terms are ORed.
```jsonnet
{
  withNodeSelectorTerms(nodeSelectorTerms):: {}
}
```

### `fn spec.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`
The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding "weight" to the sum if the node matches the corresponding matchExpressions; the node(s) with the highest sum are the most preferred.
```jsonnet
{
  withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution):: {}
}
```

### `fn spec.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`
The scheduler will prefer to schedule pods to nodes that satisfy the affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding "weight" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred.
```jsonnet
{
  withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution):: {}
}
```

### `fn spec.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution`
If the affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied.
```jsonnet
{
  withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution):: {}
}
```

### `fn spec.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution`
The scheduler will prefer to schedule pods to nodes that satisfy the anti-affinity expressions specified by this field, but it may choose a node that violates one or more of the expressions. The node that is most preferred is the one with the greatest sum of weights, i.e. for each node that meets all of the scheduling requirements (resource request, requiredDuringScheduling anti-affinity expressions, etc.), compute a sum by iterating through the elements of this field and adding "weight" to the sum if the node has pods which matches the corresponding podAffinityTerm; the node(s) with the highest sum are the most preferred.
```jsonnet
{
  withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution):: {}
}
```

### `fn spec.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution`
If the anti-affinity requirements specified by this field are not met at scheduling time, the pod will not be scheduled onto the node. If the anti-affinity requirements specified by this field cease to be met at some point during pod execution (e.g. due to a pod label update), the system may or may not try to eventually evict the pod from its node. When there are multiple elements, the lists of nodes corresponding to each podAffinityTerm are intersected, i.e. all terms must be satisfied.
```jsonnet
{
  withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution):: {}
}
```

### `fn spec.template.spec.dnsConfig.withNameservers`
A list of DNS name server IP addresses. This will be appended to the base nameservers generated from DNSPolicy. Duplicated nameservers will be removed.
```jsonnet
{
  withNameservers(nameservers):: {}
}
```

### `fn spec.template.spec.dnsConfig.withOptions`
A list of DNS resolver options. This will be merged with the base options generated from DNSPolicy. Duplicated entries will be removed. Resolution options given in Options will override those that appear in the base DNSPolicy.
```jsonnet
{
  withOptions(options):: {}
}
```

### `fn spec.template.spec.dnsConfig.withSearches`
A list of DNS search domains for host-name lookup. This will be appended to the base search paths generated from DNSPolicy. Duplicated search paths will be removed.
```jsonnet
{
  withSearches(searches):: {}
}
```

### `fn spec.template.spec.securityContext.seLinuxOptions.withLevel`
Level is SELinux level label that applies to the container.
```jsonnet
{
  withLevel(level):: {}
}
```

### `fn spec.template.spec.securityContext.seLinuxOptions.withRole`
Role is a SELinux role label that applies to the container.
```jsonnet
{
  withRole(role):: {}
}
```

### `fn spec.template.spec.securityContext.seLinuxOptions.withType`
Type is a SELinux type label that applies to the container.
```jsonnet
{
  withType(type):: {}
}
```

### `fn spec.template.spec.securityContext.seLinuxOptions.withUser`
User is a SELinux user label that applies to the container.
```jsonnet
{
  withUser(user):: {}
}
```

### `fn spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpec`
GMSACredentialSpec is where the GMSA admission webhook (https://github.com/kubernetes-sigs/windows-gmsa) inlines the contents of the GMSA credential spec named by the GMSACredentialSpecName field. This field is alpha-level and is only honored by servers that enable the WindowsGMSA feature flag.
```jsonnet
{
  withGmsaCredentialSpec(gmsaCredentialSpec):: {}
}
```

### `fn spec.template.spec.securityContext.windowsOptions.withGmsaCredentialSpecName`
GMSACredentialSpecName is the name of the GMSA credential spec to use. This field is alpha-level and is only honored by servers that enable the WindowsGMSA feature flag.
```jsonnet
{
  withGmsaCredentialSpecName(gmsaCredentialSpecName):: {}
}
```

### `fn spec.template.spec.securityContext.windowsOptions.withRunAsUserName`
The UserName in Windows to run the entrypoint of the container process. Defaults to the user specified in image metadata if unspecified. May also be set in PodSecurityContext. If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence. This field is alpha-level and it is only honored by servers that enable the WindowsRunAsUserName feature flag.
```jsonnet
{
  withRunAsUserName(runAsUserName):: {}
}
```

### `fn spec.template.spec.securityContext.withFsGroup`
A special supplemental group that applies to all containers in a pod. Some volume types allow the Kubelet to change the ownership of that volume to be owned by the pod:

1. The owning GID will be the FSGroup 2. The setgid bit is set (new files created in the volume will be owned by FSGroup) 3. The permission bits are OR'd with rw-rw----

If unset, the Kubelet will not modify the ownership and permissions of any volume.
```jsonnet
{
  withFsGroup(fsGroup):: {}
}
```

### `fn spec.template.spec.securityContext.withRunAsGroup`
The GID to run the entrypoint of the container process. Uses runtime default if unset. May also be set in SecurityContext.  If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence for that container.
```jsonnet
{
  withRunAsGroup(runAsGroup):: {}
}
```

### `fn spec.template.spec.securityContext.withRunAsNonRoot`
Indicates that the container must run as a non-root user. If true, the Kubelet will validate the image at runtime to ensure that it does not run as UID 0 (root) and fail to start the container if it does. If unset or false, no such validation will be performed. May also be set in SecurityContext.  If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.
```jsonnet
{
  withRunAsNonRoot(runAsNonRoot):: {}
}
```

### `fn spec.template.spec.securityContext.withRunAsUser`
The UID to run the entrypoint of the container process. Defaults to user specified in image metadata if unspecified. May also be set in SecurityContext.  If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence for that container.
```jsonnet
{
  withRunAsUser(runAsUser):: {}
}
```

### `fn spec.template.spec.securityContext.withSupplementalGroups`
A list of groups applied to the first process run in each container, in addition to the container's primary GID.  If unspecified, no groups will be added to any container.
```jsonnet
{
  withSupplementalGroups(supplementalGroups):: {}
}
```

### `fn spec.template.spec.securityContext.withSysctls`
Sysctls hold a list of namespaced sysctls used for the pod. Pods with unsupported sysctls (by the container runtime) might fail to launch.
```jsonnet
{
  withSysctls(sysctls):: {}
}
```

### `fn spec.template.spec.withActiveDeadlineSeconds`
Optional duration in seconds the pod may be active on the node relative to StartTime before the system will actively try to mark it failed and kill associated containers. Value must be a positive integer.
```jsonnet
{
  withActiveDeadlineSeconds(activeDeadlineSeconds):: {}
}
```

### `fn spec.template.spec.withAutomountServiceAccountToken`
AutomountServiceAccountToken indicates whether a service account token should be automatically mounted.
```jsonnet
{
  withAutomountServiceAccountToken(automountServiceAccountToken):: {}
}
```

### `fn spec.template.spec.withContainers`
List of containers belonging to the pod. Containers cannot currently be added or removed. There must be at least one container in a Pod. Cannot be updated.
```jsonnet
{
  withContainers(containers):: {}
}
```

### `fn spec.template.spec.withDnsPolicy`
Set DNS policy for the pod. Defaults to "ClusterFirst". Valid values are 'ClusterFirstWithHostNet', 'ClusterFirst', 'Default' or 'None'. DNS parameters given in DNSConfig will be merged with the policy selected with DNSPolicy. To have DNS options set along with hostNetwork, you have to specify DNS policy explicitly to 'ClusterFirstWithHostNet'.
```jsonnet
{
  withDnsPolicy(dnsPolicy):: {}
}
```

### `fn spec.template.spec.withEnableServiceLinks`
EnableServiceLinks indicates whether information about services should be injected into pod's environment variables, matching the syntax of Docker links. Optional: Defaults to true.
```jsonnet
{
  withEnableServiceLinks(enableServiceLinks):: {}
}
```

### `fn spec.template.spec.withEphemeralContainers`
List of ephemeral containers run in this pod. Ephemeral containers may be run in an existing pod to perform user-initiated actions such as debugging. This list cannot be specified when creating a pod, and it cannot be modified by updating the pod spec. In order to add an ephemeral container to an existing pod, use the pod's ephemeralcontainers subresource. This field is alpha-level and is only honored by servers that enable the EphemeralContainers feature.
```jsonnet
{
  withEphemeralContainers(ephemeralContainers):: {}
}
```

### `fn spec.template.spec.withHostAliases`
HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts file if specified. This is only valid for non-hostNetwork pods.
```jsonnet
{
  withHostAliases(hostAliases):: {}
}
```

### `fn spec.template.spec.withHostIPC`
Use the host's ipc namespace. Optional: Default to false.
```jsonnet
{
  withHostIPC(hostIPC):: {}
}
```

### `fn spec.template.spec.withHostNetwork`
Host networking requested for this pod. Use the host's network namespace. If this option is set, the ports that will be used must be specified. Default to false.
```jsonnet
{
  withHostNetwork(hostNetwork):: {}
}
```

### `fn spec.template.spec.withHostPID`
Use the host's pid namespace. Optional: Default to false.
```jsonnet
{
  withHostPID(hostPID):: {}
}
```

### `fn spec.template.spec.withHostname`
Specifies the hostname of the Pod If not specified, the pod's hostname will be set to a system-defined value.
```jsonnet
{
  withHostname(hostname):: {}
}
```

### `fn spec.template.spec.withImagePullSecrets`
ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec. If specified, these secrets will be passed to individual puller implementations for them to use. For example, in the case of docker, only DockerConfig type secrets are honored. More info: https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod
```jsonnet
{
  withImagePullSecrets(imagePullSecrets):: {}
}
```

### `fn spec.template.spec.withInitContainers`
List of initialization containers belonging to the pod. Init containers are executed in order prior to containers being started. If any init container fails, the pod is considered to have failed and is handled according to its restartPolicy. The name for an init container or normal container must be unique among all containers. Init containers may not have Lifecycle actions, Readiness probes, Liveness probes, or Startup probes. The resourceRequirements of an init container are taken into account during scheduling by finding the highest request/limit for each resource type, and then using the max of of that value or the sum of the normal containers. Limits are applied to init containers in a similar fashion. Init containers cannot currently be added or removed. Cannot be updated. More info: https://kubernetes.io/docs/concepts/workloads/pods/init-containers/
```jsonnet
{
  withInitContainers(initContainers):: {}
}
```

### `fn spec.template.spec.withNodeName`
NodeName is a request to schedule this pod onto a specific node. If it is non-empty, the scheduler simply schedules this pod onto that node, assuming that it fits resource requirements.
```jsonnet
{
  withNodeName(nodeName):: {}
}
```

### `fn spec.template.spec.withNodeSelector`
NodeSelector is a selector which must be true for the pod to fit on a node. Selector which must match a node's labels for the pod to be scheduled on that node. More info: https://kubernetes.io/docs/concepts/configuration/assign-pod-node/
```jsonnet
{
  withNodeSelector(nodeSelector):: {}
}
```

### `fn spec.template.spec.withOverhead`
Overhead represents the resource overhead associated with running a pod for a given RuntimeClass. This field will be autopopulated at admission time by the RuntimeClass admission controller. If the RuntimeClass admission controller is enabled, overhead must not be set in Pod create requests. The RuntimeClass admission controller will reject Pod create requests which have the overhead already set. If RuntimeClass is configured and selected in the PodSpec, Overhead will be set to the value defined in the corresponding RuntimeClass, otherwise it will remain unset and treated as zero. More info: https://git.k8s.io/enhancements/keps/sig-node/20190226-pod-overhead.md This field is alpha-level as of Kubernetes v1.16, and is only honored by servers that enable the PodOverhead feature.
```jsonnet
{
  withOverhead(overhead):: {}
}
```

### `fn spec.template.spec.withPreemptionPolicy`
PreemptionPolicy is the Policy for preempting pods with lower priority. One of Never, PreemptLowerPriority. Defaults to PreemptLowerPriority if unset. This field is alpha-level and is only honored by servers that enable the NonPreemptingPriority feature.
```jsonnet
{
  withPreemptionPolicy(preemptionPolicy):: {}
}
```

### `fn spec.template.spec.withPriority`
The priority value. Various system components use this field to find the priority of the pod. When Priority Admission Controller is enabled, it prevents users from setting this field. The admission controller populates this field from PriorityClassName. The higher the value, the higher the priority.
```jsonnet
{
  withPriority(priority):: {}
}
```

### `fn spec.template.spec.withPriorityClassName`
If specified, indicates the pod's priority. "system-node-critical" and "system-cluster-critical" are two special keywords which indicate the highest priorities with the former being the highest priority. Any other name must be defined by creating a PriorityClass object with that name. If not specified, the pod priority will be default or zero if there is no default.
```jsonnet
{
  withPriorityClassName(priorityClassName):: {}
}
```

### `fn spec.template.spec.withReadinessGates`
If specified, all readiness gates will be evaluated for pod readiness. A pod is ready when all its containers are ready AND all conditions specified in the readiness gates have status equal to "True" More info: https://git.k8s.io/enhancements/keps/sig-network/0007-pod-ready%2B%2B.md
```jsonnet
{
  withReadinessGates(readinessGates):: {}
}
```

### `fn spec.template.spec.withRestartPolicy`
Restart policy for all containers within the pod. One of Always, OnFailure, Never. Default to Always. More info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#restart-policy
```jsonnet
{
  withRestartPolicy(restartPolicy):: {}
}
```

### `fn spec.template.spec.withRuntimeClassName`
RuntimeClassName refers to a RuntimeClass object in the node.k8s.io group, which should be used to run this pod.  If no RuntimeClass resource matches the named class, the pod will not be run. If unset or empty, the "legacy" RuntimeClass will be used, which is an implicit class with an empty definition that uses the default runtime handler. More info: https://git.k8s.io/enhancements/keps/sig-node/runtime-class.md This is a beta feature as of Kubernetes v1.14.
```jsonnet
{
  withRuntimeClassName(runtimeClassName):: {}
}
```

### `fn spec.template.spec.withSchedulerName`
If specified, the pod will be dispatched by specified scheduler. If not specified, the pod will be dispatched by default scheduler.
```jsonnet
{
  withSchedulerName(schedulerName):: {}
}
```

### `fn spec.template.spec.withServiceAccount`
DeprecatedServiceAccount is a depreciated alias for ServiceAccountName. Deprecated: Use serviceAccountName instead.
```jsonnet
{
  withServiceAccount(serviceAccount):: {}
}
```

### `fn spec.template.spec.withServiceAccountName`
ServiceAccountName is the name of the ServiceAccount to use to run this pod. More info: https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/
```jsonnet
{
  withServiceAccountName(serviceAccountName):: {}
}
```

### `fn spec.template.spec.withShareProcessNamespace`
Share a single process namespace between all of the containers in a pod. When this is set containers will be able to view and signal processes from other containers in the same pod, and the first process in each container will not be assigned PID 1. HostPID and ShareProcessNamespace cannot both be set. Optional: Default to false. This field is beta-level and may be disabled with the PodShareProcessNamespace feature.
```jsonnet
{
  withShareProcessNamespace(shareProcessNamespace):: {}
}
```

### `fn spec.template.spec.withSubdomain`
If specified, the fully qualified Pod hostname will be "<hostname>.<subdomain>.<pod namespace>.svc.<cluster domain>". If not specified, the pod will not have a domainname at all.
```jsonnet
{
  withSubdomain(subdomain):: {}
}
```

### `fn spec.template.spec.withTerminationGracePeriodSeconds`
Optional duration in seconds the pod needs to terminate gracefully. May be decreased in delete request. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period will be used instead. The grace period is the duration in seconds after the processes running in the pod are sent a termination signal and the time when the processes are forcibly halted with a kill signal. Set this value longer than the expected cleanup time for your process. Defaults to 30 seconds.
```jsonnet
{
  withTerminationGracePeriodSeconds(terminationGracePeriodSeconds):: {}
}
```

### `fn spec.template.spec.withTolerations`
If specified, the pod's tolerations.
```jsonnet
{
  withTolerations(tolerations):: {}
}
```

### `fn spec.template.spec.withTopologySpreadConstraints`
TopologySpreadConstraints describes how a group of pods ought to spread across topology domains. Scheduler will schedule pods in a way which abides by the constraints. This field is alpha-level and is only honored by clusters that enables the EvenPodsSpread feature. All topologySpreadConstraints are ANDed.
```jsonnet
{
  withTopologySpreadConstraints(topologySpreadConstraints):: {}
}
```

### `fn spec.template.spec.withVolumes`
List of volumes that can be mounted by containers belonging to the pod. More info: https://kubernetes.io/docs/concepts/storage/volumes
```jsonnet
{
  withVolumes(volumes):: {}
}
```

### `fn spec.withMinReadySeconds`
Minimum number of seconds for which a newly created pod should be ready without any of its container crashing, for it to be considered available. Defaults to 0 (pod will be considered available as soon as it is ready)
```jsonnet
{
  withMinReadySeconds(minReadySeconds):: {}
}
```

### `fn spec.withPaused`
Indicates that the deployment is paused.
```jsonnet
{
  withPaused(paused):: {}
}
```

### `fn spec.withProgressDeadlineSeconds`
The maximum time in seconds for a deployment to make progress before it is considered to be failed. The deployment controller will continue to process failed deployments and a condition with a ProgressDeadlineExceeded reason will be surfaced in the deployment status. Note that progress will not be estimated during the time a deployment is paused. Defaults to 600s.
```jsonnet
{
  withProgressDeadlineSeconds(progressDeadlineSeconds):: {}
}
```

### `fn spec.withReplicas`
Number of desired pods. This is a pointer to distinguish between explicit zero and not specified. Defaults to 1.
```jsonnet
{
  withReplicas(replicas):: {}
}
```

### `fn spec.withRevisionHistoryLimit`
The number of old ReplicaSets to retain to allow rollback. This is a pointer to distinguish between explicit zero and not specified. Defaults to 10.
```jsonnet
{
  withRevisionHistoryLimit(revisionHistoryLimit):: {}
}
```
