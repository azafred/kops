## kops get instancegroups

Get one or many instancegroups

### Synopsis


Display one or many instancegroup resources.

```
kops get instancegroups
```

### Examples

```
  # Get all instancegroups in a state store
  kops get ig
  
  # Get a cluster
  kops get ig --name k8s-cluster.example.com nodes
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --config string                    config file (default is $HOME/.kops.yaml)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default false)
      --name string                      Name of cluster
  -o, --output string                    output format.  One of: table, yaml, json (default "table")
      --state string                     Location of state storage
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [kops get](kops_get.md)	 - Get one or many resources.

