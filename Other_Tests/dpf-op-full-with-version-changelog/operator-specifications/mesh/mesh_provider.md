---
category: mesh
plugin: core
license: None
Version: 0.0.0
---

# mesh:mesh provider

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Reads a mesh from result files.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong>|  time_scoping |[`int32`](../../getting-started/using-data-containers.md#int32) | Optional time/frequency set ID of the mesh, supported for adaptative meshes. |
| <strong>Pin 3</strong>|  streams_container |[`streams_container`](../../getting-started/using-data-containers.md#streams-container) | result file container allowed to be kept open to cache data |
| <strong>Pin 4</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  data_sources |[`data_sources`](../../getting-started/using-data-containers.md#data-sources) | result file path container, used if no streams are set |
| <strong>Pin 14</strong>|  read_cyclic |[`enum dataProcessing::ECyclicReading`](../../getting-started/using-data-containers.md#enum-dataprocessing::ecyclicreading), [`int32`](../../getting-started/using-data-containers.md#int32) | If 1, cyclic symmetry is ignored. If 2, cyclic expansion is done (default is 1). |
| <strong>Pin 25</strong>|  region_scoping |[`scoping`](../../getting-started/using-data-containers.md#scoping), [`int32`](../../getting-started/using-data-containers.md#int32), [`vector<int32>`](../../getting-started/using-data-containers.md#vector<int32>) | region id (integer) or vector of region ids with one entity (vector) or region scoping with one id (scoping) (region corresponds to zone for Fluid results or part for LSDyna results). |
| <strong>Pin 200</strong>|  laziness |[`abstract_data_tree`](../../getting-started/using-data-containers.md#abstract-data-tree) | configurate whether lazy evaluation can be performed and to what extent. Supported attributes are: 
- "num_named_selections"->num named selection to read (-1 is all, int32, default si -1), careful: the other named selections will not be available, use mesh_property_provider Operator to read them.
- all mesh property fields "mat", "named_selection", "apdl_element_type", "section"-> if set to 1 these properties will not be read and a workflow will be bounded to the properties to be evaluated on demand, with 0 they are read (default is 0).
- "all_available_properties" option set to 0 will return all possible properties |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| mesh |[`abstract_meshed_region`](../../getting-started/using-data-containers.md#abstract-meshed-region) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |
| **num_threads** |[`int32`](../../getting-started/using-data-containers.md#int32) | 0 | Number of threads to use to run in parallel |
| **permissive** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, warning checks (like unit or data sizes) won't be done. |
| **run_in_parallel** |[`bool`](../../getting-started/using-data-containers.md#bool) | true | Loops are allowed to run in parallel if the value of this config is set to true. |

## Scripting

 **Category**: mesh

 **Plugin**: core

 **Scripting name**: mesh_provider

 **Full name**: mesh.mesh_provider

 **Internal name**: mesh_provider

 **License**: None
 
