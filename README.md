# Iac-dev-environment

Within this repo, you will find a custom built Infrastructure-as-Code dev environment made with Terraform in VSCode.

# Starting
To start off, you first need to connect with Azure through Terraform. Access that here: https://registry.terraform.io/providers/hashicorp/azurerm/latest

That should look something like this:
<pre><code>terraform {
  required_providers {
    azurerm = {
      source  = "hashicorp/azurerm"
      version = "3.29.1"
    }
  }
}

provider "azurerm" {
  features {

  }
}</code></pre>
You can either add that in your main file you will be working with in VScode or create a provider file just for that. Either way, your code will be pushed together if ran in the same folder.

