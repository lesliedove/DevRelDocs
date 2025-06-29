---
category: logic
plugin: core
license: None
Version: 0.0.0
---

# logic:component transformer (fields container)

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Takes the input field and creates a field with overriden value on given components.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  fields_container |[`fields_container`](../../getting-started/using-data-containers.md#fields-container) |  |
| <strong>Pin 1</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  component_number |[`int32`](../../getting-started/using-data-containers.md#int32), [`vector<int32>`](../../getting-started/using-data-containers.md#vector<int32>) | One or several component index that will be modified from the initial field. |
| <strong>Pin 2</strong>|  default_value |[`double`](../../getting-started/using-data-containers.md#double) | Set a default value for components selected. |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| fields_container |[`fields_container`](../../getting-started/using-data-containers.md#fields-container) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: logic

 **Plugin**: core

 **Scripting name**: component_transformer_fc

 **Full name**: logic.component_transformer_fc

 **Internal name**: component_transformer_fc

 **License**: None
 
