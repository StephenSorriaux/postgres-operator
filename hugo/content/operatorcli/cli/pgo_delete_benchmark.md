---
title: "pgo_delete_benchmark"
---
## pgo delete benchmark

Delete benchmarks for a cluster

### Synopsis

Delete benchmarks for a cluster. For example:

    pgo delete benchmark mycluster
    pgo delete benchmark --selector=env=test

```
pgo delete benchmark [flags]
```

### Options

```
  -h, --help              help for benchmark
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
