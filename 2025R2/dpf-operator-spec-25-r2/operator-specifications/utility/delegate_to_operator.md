---
category: utility
plugin: core
license: None
Version: 0.0.0
---

# utility:delegate to operator

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Delegate the run to an Operator instantiated by the name in input (forwards all the input of this Operator to the sub Operator).


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin -1</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  operator_name |[`string`](./../../getting-started/using-data-containers.md#string) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| any |[`any`](./../../getting-started/using-data-containers.md#any) | inputs |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: utility

 **Plugin**: core

 **Scripting name**: delegate_to_operator

 **Full name**: utility.delegate_to_operator

 **Internal name**: delegate_to_operator

 **License**: None
 
