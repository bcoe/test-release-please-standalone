# Demonstrating Release Please Functionality

release-please allows you to automate the GitHub releases based on conventional
commit messages.

```hcl
module "vpc" {
    source  = "bcoe/test-release-please-standalone"
    version = "~> 0.0.0"
}
```

