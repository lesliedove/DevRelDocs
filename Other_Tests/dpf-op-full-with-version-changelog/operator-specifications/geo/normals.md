---
category: geo
plugin: core
license: any_dpf_supported_increments
Version: 0.0.0
---

# geo:scoping normals

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

compute the normals at the given nodes or element scoping based on the given mesh (first version, the element normal is only handled on the shell elements)


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong>|  mesh |[`abstract_meshed_region`](../../getting-started/using-data-containers.md#abstract-meshed-region) |  |
| <strong>Pin 1</strong>|  mesh_scoping |[`scoping`](../../getting-started/using-data-containers.md#scoping) |  |
| <strong>Pin 3</strong>|  field |[`field`](../../getting-started/using-data-containers.md#field) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| field |[`field`](../../getting-started/using-data-containers.md#field) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: geo

 **Plugin**: core

 **Scripting name**: normals

 **Full name**: geo.normals

 **Internal name**: normals_provider

 **License**: any_dpf_supported_increments
 
