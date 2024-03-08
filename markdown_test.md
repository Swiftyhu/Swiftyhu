# HCL

```hcl
provider "github" {
  owner = "sevdesk"
    app_auth {
      id              = var.app_id
      installation_id = var.app_installation_id
      pem_file        = file("private.key")
      }
  }
```

# TF

```tf
provider "github" {
  owner = "sevdesk"
    app_auth {
      id              = var.app_id
      installation_id = var.app_installation_id
      pem_file        = file("private.key")
      }
  }
```

# TERRAFORM

```terraforrm
provider "github" {
  owner = "sevdesk"
    app_auth {
      id              = var.app_id
      installation_id = var.app_installation_id
      pem_file        = file("private.key")
      }
  }
```
