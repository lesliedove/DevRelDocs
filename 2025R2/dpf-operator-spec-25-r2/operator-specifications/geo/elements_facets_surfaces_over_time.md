---
category: geo
plugin: core
license: any_dpf_supported_increments
Version: 0.0.0
---

# geo:elements facets surfaces over time

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Calculates for a mesh, the surface of each element's facet over time for each specified time step. The output is a new mesh made with only surface elements.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 1</strong>|  scoping |[`scoping`](./../../getting-started/using-data-containers.md#scoping) |  |
| <strong>Pin 2</strong>|  displacement |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) | Displacement field's container. |
| <strong>Pin 7</strong>|  mesh |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) | Mesh must be defined if the displacement field's container does not contain it, or if there is no displacement. |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| fields_container |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) | Surfaces field. |
|  **Pin 1**| mesh |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) | Mesh made of surface elements only. |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: geo

 **Plugin**: core

 **Scripting name**: elements_facets_surfaces_over_time

 **Full name**: geo.elements_facets_surfaces_over_time

 **Internal name**: surfaces_provider

 **License**: any_dpf_supported_increments
 
