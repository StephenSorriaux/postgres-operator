---
title: "pgo_delete_cluster"
---
## pgo delete cluster

Delete a PostgreSQL cluster

### Synopsis

Delete a PostgreSQL cluster. For example:

    pgo delete cluster --all
    pgo delete cluster mycluster

```
pgo delete cluster [flags]
```

### Options

```
      --all               all clusters. Backups and data subject to --delete-backups and --delete-data flags, respectively.
  -b, --delete-backups    Causes the backups for specified cluster to be removed permanently.
  -d, --delete-data       Causes the data for specified cluster to be removed permanently.
  -h, --help              help for cluster
      --no-prompt         No command line confirmation.
  -s, --selector string   The selector to use for cluster filtering.
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo delete](/operatorcli/cli/pgo_delete/)	 - Delete an Operator resource

###### Auto generated by spf13/cobra on 4-Oct-2019
