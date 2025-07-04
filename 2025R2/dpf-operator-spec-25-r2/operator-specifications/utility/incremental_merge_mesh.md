---
category: utility
plugin: core
license: None
Version: 0.0.0
---

# utility:incremental mesh

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Incrementaly merge the input.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  input |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| incremented_result | |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: utility

 **Plugin**: core

 **Scripting name**: incremental::merge::mesh

 **Full name**: utility.incremental::merge::mesh

 **Internal name**: incremental::merge::mesh

 **License**: None
 
