# Serial Console
> see https://aka.ms/autorest

This is the AutoRest configuration file for Serial Console.

## Getting Started
To build the SDKs for Serial Console, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:
> `autorest readme.md`

To see additional help and options, run:
> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information
These are the global settings for the Serial Console API.

``` yaml
openapi-type: arm
azure-arm: true
tag: package-2018-05
input-file:
- Microsoft.SerialConsole/stable/2018-05-01/serialconsole.json
output-folder: ./Generated
```


---
# Code Generation

## C#

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  azure-arm: true
  output-folder: ./Generated
  clear-output-folder: true
```

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python
```
