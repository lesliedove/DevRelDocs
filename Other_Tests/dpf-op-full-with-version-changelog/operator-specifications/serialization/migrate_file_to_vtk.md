---
category: serialization
plugin: vtk
license: None
Version: 0.0.0
---

# serialization:migrate to vtk

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Take an input data sources or streams and convert as much data as possible to vtk.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong>|  output_filename |[`string`](../../getting-started/using-data-containers.md#string) |  |
| <strong>Pin 3</strong>|  streams_container |[`streams_container`](../../getting-started/using-data-containers.md#streams-container) |  |
| <strong>Pin 4</strong>|  data_sources |[`data_sources`](../../getting-started/using-data-containers.md#data-sources) |  |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| data_sources |[`data_sources`](../../getting-started/using-data-containers.md#data-sources) | Generated output vtk file |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: serialization

 **Plugin**: vtk

 **Scripting name**: migrate_file_to_vtk

 **Full name**: serialization.migrate_file_to_vtk

 **Internal name**: vtk::migrate_file

 **License**: None
 
