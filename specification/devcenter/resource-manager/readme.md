# devcenter

> see https://aka.ms/autorest

This is the AutoRest configuration file for devcenter.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for devcenter.

``` yaml
openapi-type: arm
openapi-subtype: rpaas
tag: package-preview-2025-07-01-preview
```


### Tag: package-preview-2025-07-01-preview

These settings apply only when `--tag=package-preview-2025-07-01-preview` is specified on the command line.

```yaml $(tag) == 'package-preview-2025-07-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2025-07-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2025-07-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2025-07-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2025-04-01-preview

These settings apply only when `--tag=package-preview-2025-04-01-preview` is specified on the command line.

```yaml $(tag) == 'package-preview-2025-04-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2025-04-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2025-04-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2025-04-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-2025-02-01

These settings apply only when `--tag=package-2025-02-01` is specified on the command line.

```yaml $(tag) == 'package-2025-02-01'
input-file:
  - Microsoft.DevCenter/stable/2025-02-01/commonDefinitions.json
  - Microsoft.DevCenter/stable/2025-02-01/devcenter.json
  - Microsoft.DevCenter/stable/2025-02-01/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2024-10

These settings apply only when `--tag=package-preview-2024-10` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-10'
input-file:
  - Microsoft.DevCenter/preview/2024-10-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2024-10-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2024-10-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2024-08

These settings apply only when `--tag=package-preview-2024-08` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-08'
input-file:
  - Microsoft.DevCenter/preview/2024-08-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2024-08-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2024-08-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2024-07

These settings apply only when `--tag=package-preview-2024-07` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-07'
input-file:
  - Microsoft.DevCenter/preview/2024-07-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2024-07-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2024-07-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2024-06

These settings apply only when `--tag=package-preview-2024-06` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-06'
input-file:
  - Microsoft.DevCenter/preview/2024-06-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2024-06-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2024-06-01-preview/vdi.json
suppressions:
  - code: PatchBodyParametersSchema
    from: vdi.json
    reason: Patch Body comes from common-types v5 Sku object. Keeping here for consistency with existing parts of API to avoid breaking customers.
```

### Tag: package-preview-2024-05

These settings apply only when `--tag=package-preview-2024-05` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-05'
input-file:
  - Microsoft.DevCenter/preview/2024-05-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2024-05-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2024-05-01-preview/vdi.json
```
### Tag: package-2024-02

These settings apply only when `--tag=package-2024-02` is specified on the command line.

``` yaml $(tag) == 'package-2024-02'
input-file:
  - Microsoft.DevCenter/stable/2024-02-01/commonDefinitions.json
  - Microsoft.DevCenter/stable/2024-02-01/devcenter.json
  - Microsoft.DevCenter/stable/2024-02-01/vdi.json
```

### Tag: package-preview-2023-10

These settings apply only when `--tag=package-preview-2023-10` is specified on the command line.

``` yaml $(tag) == 'package-preview-2023-10'
input-file:
  - Microsoft.DevCenter/preview/2023-10-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2023-10-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2023-10-01-preview/vdi.json
```

### Tag: package-preview-2023-08

These settings apply only when `--tag=package-preview-2023-08` is specified on the command line.

``` yaml $(tag) == 'package-preview-2023-08'
input-file:
  - Microsoft.DevCenter/preview/2023-08-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2023-08-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2023-08-01-preview/vdi.json
```

### Tag: package-2023-04

These settings apply only when `--tag=package-2023-04` is specified on the command line.

``` yaml $(tag) == 'package-2023-04'
input-file:
  - Microsoft.DevCenter/stable/2023-04-01/commonDefinitions.json
  - Microsoft.DevCenter/stable/2023-04-01/devcenter.json
  - Microsoft.DevCenter/stable/2023-04-01/vdi.json
```

### Tag: package-preview-2023-01

These settings apply only when `--tag=package-preview-2023-01` is specified on the command line.

``` yaml $(tag) == 'package-preview-2023-01'
input-file:
  - Microsoft.DevCenter/preview/2023-01-01-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2023-01-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2023-01-01-preview/vdi.json
```

### Tag: package-preview-2022-11

These settings apply only when `--tag=package-preview-2022-11` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-11'
input-file:
  - Microsoft.DevCenter/preview/2022-11-11-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2022-11-11-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-11-11-preview/vdi.json
```

### Tag: package-preview-2022-10

These settings apply only when `--tag=package-preview-2022-10` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-10'
input-file:
  - Microsoft.DevCenter/preview/2022-10-12-preview/commonDefinitions.json
  - Microsoft.DevCenter/preview/2022-10-12-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-10-12-preview/vdi.json
```

### Tag: package-2022-08-01-preview

These settings apply only when `--tag=package-2022-08-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-2022-08-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2022-08-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-08-01-preview/vdi.json
```

### Tag: package-2022-09-01-preview

These settings apply only when `--tag=package-2022-09-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-2022-09-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2022-09-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-09-01-preview/vdi.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-js
  - repo: azure-sdk-for-go
  - repo: azure-cli-extensions
```

## Az

See configuration in [readme.az.md](./readme.az.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)

## Go

See configuration in [readme.go.md](./readme.go.md)
