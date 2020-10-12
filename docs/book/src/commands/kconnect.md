## kconnect

The Kubernetes Connection Manager CLI

### Synopsis

The Kubernetes Connection Manager CLI

```
kconnect [flags]
```

### Options

```
      --config string     Configuration file for application defaults (default "/home/richard/.kconnect/config.yaml")
  -h, --help              help for kconnect
      --non-interactive   Run without interactive flag resolution
  -v, --verbosity int     sets the logging verbosity
```

### SEE ALSO

* [kconnect configure](kconnect_configure.md)	 - Set and view your default kconnect configuration. If no flags are supplied your config is displayed.
* [kconnect ls](kconnect_ls.md)	 - Query your connection history
* [kconnect renew](kconnect_renew.md)	 - Reconnect to last cluster
* [kconnect to](kconnect_to.md)	 - Re-connect to a previously connected cluster using your history
* [kconnect use](kconnect_use.md)	 - Connect to a target environment and discover clusters for use
* [kconnect version](kconnect_version.md)	 - Display version & build information

###### Auto generated by spf13/cobra on 9-Oct-2020