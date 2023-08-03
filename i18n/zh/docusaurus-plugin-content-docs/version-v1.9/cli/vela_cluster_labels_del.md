---
title: vela cluster labels del
---

Delete labels for managed cluster.

### Synopsis

Delete labels for managed cluster.

```
vela cluster labels del CLUSTER_NAME LABELS [flags]
```

### Examples

```
vela cluster labels del my-cluster project,owner
```

### Options

```
  -h, --help   help for del
```

### Options inherited from parent commands

```
  -V, --verbosity Level   number for the log level verbosity
  -y, --yes               Assume yes for all user prompts
```

### SEE ALSO

* [vela cluster labels](vela_cluster_labels.md)	 - Manage Kubernetes Cluster Labels.

#### Go Back to [CLI Commands](vela.md) Homepage.


###### Auto generated by [spf13/cobra script in KubeVela](https://github.com/kubevela/kubevela/tree/master/hack/docgen).