---
category: result
plugin: core
license: any_dpf_supported_increments
Version: 0.0.0
---

# result:poynting vector surface

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Compute the Poynting Vector surface integral


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_containerA |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |
| <strong>Pin 1</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_containerB |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |
| <strong>Pin 2</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_containerC |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |
| <strong>Pin 3</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_containerD |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |
| <strong>Pin 4</strong>|  abstract_meshed_region |[`abstract_meshed_region`](./../../getting-started/using-data-containers.md#abstract-meshed-region) | the mesh region in this pin have to be boundary or skin mesh |
| <strong>Pin 5</strong>|  int32 |[`int32`](./../../getting-started/using-data-containers.md#int32) | load step number, if it's specified, the Poynting Vector is computed only on the substeps of this step |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| fields_container |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: result

 **Plugin**: core

 **Scripting name**: poynting_vector_surface

 **Full name**: result.poynting_vector_surface

 **Internal name**: PoyntingVectorSurface

 **License**: any_dpf_supported_increments
 
