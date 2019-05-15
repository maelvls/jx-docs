---
date: 2019-05-13T20:44:05Z
title: "jx delete vault"
slug: jx_delete_vault
url: /commands/jx_delete_vault/
---
## jx delete vault

Deletes a Vault

### Synopsis

Deletes a Vault

```
jx delete vault [flags]
```

### Examples

```
  # Deletes a Vault from namespace my-namespace
  jx delete vault --namespace my-namespace my-vault
```

### Options

```
      --gke-project-id string    Google Project ID to use for Vault backend
      --gke-zone string          The zone (e.g. us-central1-a) where Vault will store the encrypted data
  -h, --help                     help for vault
  -n, --namespace string         Namespace from where to delete the vault
  -r, --remove-cloud-resources   Remove all cloud resource allocated for the Vault
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx delete](/commands/jx_delete/)	 - Deletes one or more resources

###### Auto generated by spf13/cobra on 13-May-2019