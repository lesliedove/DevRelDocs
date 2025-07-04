---
category: utility
plugin: core
license: None
Version: 0.0.0
---

# utility:merge scopings

## Version

0.0.0

## Changelog

- Version 0.0.0: Initial release.

## Description

Assembles a set of scopings into a unique one.


## Inputs

| Input | Name | Expected type(s) | Description |
|-------|-------|------------------|-------------|
| <strong>Pin 0</strong> <br><span style="background-color:#d93025; color:white; padding:2px 6px; border-radius:3px; font-size:0.75em;">Required</span>|  scopings |[`scoping`](../../getting-started/using-data-containers.md#scoping), [`scopings_container`](../../getting-started/using-data-containers.md#scopings-container), [`vector<shared_ptr<scoping>>`](../../getting-started/using-data-containers.md#vector<shared-ptr<scoping>>) | Either a scopings container, a vector of scopings to merge, or scopings from pin 0 to ... |


## Outputs

| Output |  Name | Expected type(s) | Description |
|-------|------|------------------|-------------|
|  **Pin 0**| merged_scoping |[`scoping`](../../getting-started/using-data-containers.md#scoping) |  |

## Configurations

| Name| Expected type(s) | Default value | Description |
|-----|------|----------|-------------|
| **mutex** |[`bool`](../../getting-started/using-data-containers.md#bool) | false | If this option is set to true, the shared memory is prevented from being simultaneously accessed by multiple threads. |

## Scripting

 **Category**: utility

 **Plugin**: core

 **Scripting name**: merge_scopings

 **Full name**: utility.merge_scopings

 **Internal name**: merge::scoping

 **License**: None
 
