# Templates for Terraform

Templates for development Terraform, Packer code.

## Terraform plugin cache

Put `.terraformrc` file in your $HOME and make dir:

```bash
mkdir -p $HOME/.terraform.d/plugin-cache
```

## Git pre-commit hooks

Setup [pre-commit](https://pre-commit.com/), tflint, shellcheck and other you need and modify `.pre-commit-config.yaml` file in repo:

```bash
brew install pre-commit tflint shellcheck terraform-docs infracost jq
```
