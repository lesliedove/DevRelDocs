---
category: geo
plugin: core
license: any_dpf_supported_increments
Version: 0.0.0
---

# geo:faces area

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Compute the measure of the Faces (surface for 2D faces of a 3D model or length for 1D faces of a 2D model) using default shape functions, except for polygons.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  mesh |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) |  |
| <strong>Pin 1</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  mesh_scoping |[`scoping`](./../../getting-started/using-data-containers.md#scoping) | If not provided, the measure of all Faces in the mesh is computed. If provided, the Scoping needs to have "Faces" location. |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| field |[`field`](./../../getting-started/using-data-containers.md#field) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: geo

 **Plugin**: core

 **Scripting name**: faces_area

 **Full name**: geo.faces_area

 **Internal name**: face::area

 **License**: any_dpf_supported_increments
 
