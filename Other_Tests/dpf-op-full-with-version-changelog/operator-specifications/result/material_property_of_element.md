---
category: result
plugin: core
license: None
Version: 0.0.0
---

# result:material property of element

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Loads the appropriate operator based on the data sources and retrieves material properties.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 3</strong>|  streams_container |[`streams_container`](../../getting-started/using-data-containers.md#streams-container) |  |
| <strong>Pin 4</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  data_sources |[`data_sources`](../../getting-started/using-data-containers.md#data-sources) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| material_properties |[`field`](../../getting-started/using-data-containers.md#field) | material properties |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: result

 **Plugin**: core

 **Scripting name**: material_property_of_element

 **Full name**: result.material_property_of_element

 **Internal name**: MaterialPropertyOfElement

 **License**: None
 
