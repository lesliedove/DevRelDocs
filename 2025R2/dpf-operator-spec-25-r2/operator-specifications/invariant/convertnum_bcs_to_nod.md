---
category: invariant
plugin: mapdl
license: None
Version: 0.0.0
---

# invariant:convertnum bcs to nod

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Converts a fields container from BCS to NOD ordering.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 2</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_container |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) | fields_container |
| <strong>Pin 4</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  data_sources |[`data_sources`](./../../getting-started/using-data-containers.md#data-sources) | Data_sources (must contain the full file). |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| fields_container |[`fields_container`](./../../getting-started/using-data-containers.md#fields-container) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](./../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: invariant

 **Plugin**: mapdl

 **Scripting name**: convertnum_bcs_to_nod

 **Full name**: invariant.convertnum_bcs_to_nod

 **Internal name**: convertnum_bcs_to_nod

 **License**: None
 
