---
category: mesh
plugin: core
license: None
Version: 0.0.0
---

# mesh:mesh_to_graphics_edges

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Generate edges of surface elements for input mesh


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 1</strong>|  mesh_scoping |[`scoping`](./../../getting-started/using-data-containers.md#scoping) |  |
| <strong>Pin 6</strong>|  include_mid_nodes |[`bool`](./../../getting-started/using-data-containers.md#bool) |  |
| <strong>Pin 7</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  mesh |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| nodes |[`field`](./../../getting-started/using-data-containers.md#field) | node coordinates |
|  **Pin 2**| connectivity |[`property_field`](./../../getting-started/using-data-containers.md#property-field) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: mesh

 **Plugin**: core

 **Scripting name**: mesh_to_graphics_edges

 **Full name**: mesh.mesh_to_graphics_edges

 **Internal name**: mesh_to_graphics_edges

 **License**: None
 
