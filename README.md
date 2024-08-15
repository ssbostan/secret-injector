# secret-injector

A helm chart to deploy Sealed-Secrets and External-Secrets resources.

It can create:

  - ServiceAccount for IRSA and Workload Identity.
  - SealedSecret for Access/Secret keys or service principal.
  - SecretStore to point to AWS ASM, HashiCorp Vault, Azure Key Vault.
  - ExternalSecret to fetch secrets from secret stores.

Copyright &copy; 2024 Saeid Bostandoust <ssbostan@yahoo.com>
