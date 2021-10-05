# Favorite az cli Commands

## General
Set Subscription: 
```bash
az account set --subscription "My Subscription Name"
```

## Keyvault
Set Access Policy permissions for Secrets for a user:
```bash
az keyvault set-policy --subscription <sub> --name <kvname> --secret-permissions get list delete --upn <user>
```

# Docs
https://docs.microsoft.com/en-us/cli/azure/
