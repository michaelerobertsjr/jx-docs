---
title: jx secret vault shell
linktitle: shell
type: docs
description: 
aliases:
  - jx-secret_vault_shell
---

## jx-secret vault shell

Runs a shell so you can access the vault in a kubernetes cluster

***Aliases**: sh*

### Usage

```
jx-secret vault shell
```

### Synopsis

Runs a shell so you can access the vault in a kubernetes cluster

### Examples

  jx-secret vault shell

### Options

```
      --args stringArray    the arguments to pass to the shell command
  -d, --duration duration   the maximum time period to wait for vault to be ready (default 5m0s)
  -h, --help                help for shell
  -n, --ns string           the namespace where vault is running (default "jx-vault")
  -p, --pod string          the name of the vault pod which needs to be running before the port forward can take place (default "vault-0")
      --poll duration       the polling period to check if the secrets are valid (default 2s)
  -s, --shell string        the command line shell to execute (default "bash")
```

### SEE ALSO

* [jx-secret vault](..)	 - Commands for working with Vault

###### Auto generated by spf13/cobra on 25-Feb-2021