# Iac-dev-environment

Within this repo, you will find a custom built Infrastructure-as-Code dev environment made with Terraform in VSCode.

The code preview here shows the bgeinning phase of connecting with Hashicorp & Azure, and the end phase of entering your linux vm.
<pre>terraform {
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
}<code>

# Starting

# Ending
