---
title: "Arcus - Security"
layout: default
slug: /
sidebar_label: Welcome
---

[![NuGet Badge](https://buildstats.info/nuget/Arcus.Security.Secrets.AzureKeyVault?packageVersion=0.4.0)](https://www.nuget.org/packages/Arcus.Security.Secrets.AzureKeyVault/0.4.0)

# Installation

We provide a NuGet package per provider and area.

Here is how you install all Arcus Security packages
```shell
PM > Install-Package Arcus.Security.All --Version 0.4.0
```

Here is how you consume secrets for Azure Key Vault:
```shell
PM > Install-Package Arcus.Security.Providers.AzureKeyVault
```

# Features
- **Interacting with Secrets**
    - [General](features/secrets/general)
    - [Consume from Azure Key Vault](features/secrets/consume-from-key-vault)
        - [Integrate with IConfiguration](features/key-vault/extensions/iconfiguration-integration)
- **Authentication**
    - [Azure Key Vault](features/auth/azure-key-vault)

# License
This is licensed under The MIT License (MIT). Which means that you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the web application. But you always need to state that Codit is the original author of this web application.

*[Full license here](https://github.com/arcus-azure/arcus.security/blob/master/LICENSE)*
