---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "vercel Provider"
subcategory: ""
description: |-
  
---

# vercel Provider



## Example Usage

```terraform
terraform {
  required_providers {
    vercel = {
      source  = "hashicorp.com/chronark/vercel"
      version = "9000.1"
    }
  }
}

provider "vercel" {
  token = "<YOUR_TOKEN>"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **token** (String, Sensitive)
