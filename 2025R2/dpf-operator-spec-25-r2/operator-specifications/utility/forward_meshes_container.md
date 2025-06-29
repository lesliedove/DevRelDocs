---
category: utility
plugin: core
license: None
Version: 0.0.0
---

# utility:forward meshes container

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Returns the input mesh or meshes container into a meshes container.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  meshes |[`meshes_container`](./../../getting-started/using-data-containers.md#meshes-container), [`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) |  |
| <strong>Pin 1</strong>|  default_label |[`string`](./../../getting-started/using-data-containers.md#string) | this default label is used if a new meshes container needs to be created (default is unknown) |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| meshes_container |[`meshes_container`](./../../getting-started/using-data-containers.md#meshes-container) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: utility

 **Plugin**: core

 **Scripting name**: forward_meshes_container

 **Full name**: utility.forward_meshes_container

 **Internal name**: forward_meshes_container

 **License**: None
 
