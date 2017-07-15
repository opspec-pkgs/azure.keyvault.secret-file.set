# Problem statement
sets a secret file in azure keyvault (if it's not already set)

# Example usage

> note: in examples, VERSION represents a version of the azure.keyvault.secret-file.set pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.keyvault.secret-file.set#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.keyvault.secret-file.set#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/azure.keyvault.secret-file.set#VERSION }
  inputs:
    subscriptionId:
    loginId:
    loginSecret:
    name:
    value:
    vault:
    # end optional args
    description:
    disabled:
    encoding:
    expires:
    loginTenantId:
    loginType:
    # end optional args
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.keyvault.secret-file.set/issues)
