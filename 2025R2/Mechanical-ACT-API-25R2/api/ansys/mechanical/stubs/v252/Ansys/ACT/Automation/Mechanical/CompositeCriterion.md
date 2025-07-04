# `CompositeCriterion`

<a id="ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.CompositeCriterion"></a>

#### *class* Ansys.ACT.Automation.Mechanical.CompositeCriterion

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

Defines a CompositeCriterion.

<!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`Activate`](#CompositeCriterion.Activate)                               | Activate the current object.                                                      |
| [`AddComment`](#CompositeCriterion.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddFigure`](#CompositeCriterion.AddFigure)                             | Creates a new child Figure.                                                       |
| [`AddImage`](#CompositeCriterion.AddImage)                               | Creates a new child Image.                                                        |
| [`ClearGeneratedData`](#CompositeCriterion.ClearGeneratedData)           | Run the ClearGeneratedData action.                                                |
| [`CopyTo`](#CompositeCriterion.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`CreateParameter`](#CompositeCriterion.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`Delete`](#CompositeCriterion.Delete)                                   | Run the Delete action.                                                            |
| [`Duplicate`](#CompositeCriterion.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`EvaluateAllResults`](#CompositeCriterion.EvaluateAllResults)           | Run the EvaluateAllResults action.                                                |
| [`GetChildren`](#CompositeCriterion.GetChildren)                         | Gets the list of children, filtered by type.                                      |
| [`GetDefinition`](#CompositeCriterion.GetDefinition)                     | Gets the Worksheet Definition.                                                    |
| [`GetParameter`](#CompositeCriterion.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`GroupAllSimilarChildren`](#CompositeCriterion.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#CompositeCriterion.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByAPIName`](#CompositeCriterion.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`PropertyByName`](#CompositeCriterion.PropertyByName)                   | Get a property by its unique name.                                                |
| [`RemoveParameter`](#CompositeCriterion.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Description |
|--------------------------------------------------------------------------|---------------------------------------------------------------|
| [`Children`](#CompositeCriterion.Children)                               | Gets the list of children.                                    |
| [`Comments`](#CompositeCriterion.Comments)                               | Gets the list of associated comments.                         |
| [`DataModelObjectCategory`](#CompositeCriterion.DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`Figures`](#CompositeCriterion.Figures)                                 | Gets the list of associated figures.                          |
| [`Images`](#CompositeCriterion.Images)                                   | Gets the list of associated images.                           |
| [`InternalObject`](#CompositeCriterion.InternalObject)                   | Gets the internal object. For advanced usage only.            |
| [`Properties`](#CompositeCriterion.Properties)                           | Gets the list of properties for this object.                  |
| [`ReadOnly`](#CompositeCriterion.ReadOnly)                               | Gets or sets the ReadOnly.                                    |
| [`Suppressed`](#CompositeCriterion.Suppressed)                           | Gets or sets the Suppressed.                                  |
| [`Value`](#CompositeCriterion.Value)                                     | Gets the Value.                                               |
| [`VisibleProperties`](#CompositeCriterion.VisibleProperties)             | Gets the list of properties that are visible for this object. |

<a id="property-detail"></a>

## Property detail

<a id="CompositeCriterion.Children"></a>

### *property* CompositeCriterion.Children *: List[[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject](../../../Mechanical/DataModel/Interfaces/IDataModelObject.md#ansys.mechanical.stubs.v252.Ansys.Mechanical.DataModel.Interfaces.IDataModelObject)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Comments"></a>

### *property* CompositeCriterion.Comments *: Iterable[[Ansys.ACT.Automation.Mechanical.Comment](Comment.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.DataModelObjectCategory"></a>

### *property* CompositeCriterion.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#ansys.mechanical.stubs.v252.Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Figures"></a>

### *property* CompositeCriterion.Figures *: Iterable[[Ansys.ACT.Automation.Mechanical.Figure](Figure.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Images"></a>

### *property* CompositeCriterion.Images *: Iterable[[Ansys.ACT.Automation.Mechanical.Image](Image.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.InternalObject"></a>

### *property* CompositeCriterion.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSTopoCriterionAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Properties"></a>

### *property* CompositeCriterion.Properties *: [tuple](https://docs.python.org/3/library/stdtypes.html#tuple)[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.ReadOnly"></a>

### *property* CompositeCriterion.ReadOnly *: [bool](https://docs.python.org/3/library/functions.html#bool) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ReadOnly.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Suppressed"></a>

### *property* CompositeCriterion.Suppressed *: [bool](https://docs.python.org/3/library/functions.html#bool) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Value"></a>

### *property* CompositeCriterion.Value *: [Ansys.Core.Units.Quantity](../../../Core/Units/Quantity.md#ansys.mechanical.stubs.v252.Ansys.Core.Units.Quantity) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Value.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.VisibleProperties"></a>

### *property* CompositeCriterion.VisibleProperties *: [tuple](https://docs.python.org/3/library/stdtypes.html#tuple)[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="CompositeCriterion.Activate"></a>

### CompositeCriterion.Activate() → [None](https://docs.python.org/3/library/constants.html#None)

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.AddComment"></a>

### CompositeCriterion.AddComment() → [Ansys.ACT.Automation.Mechanical.Comment](Comment.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Comment)

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.AddFigure"></a>

### CompositeCriterion.AddFigure() → [Ansys.ACT.Automation.Mechanical.Figure](Figure.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Figure)

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.AddImage"></a>

### CompositeCriterion.AddImage(filePath: [str](https://docs.python.org/3/library/stdtypes.html#str)) → [Ansys.ACT.Automation.Mechanical.Image](Image.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.Image)

```text
Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.
```

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.ClearGeneratedData"></a>

### CompositeCriterion.ClearGeneratedData() → [None](https://docs.python.org/3/library/constants.html#None)

Run the ClearGeneratedData action.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.CopyTo"></a>

### CompositeCriterion.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject) → [None](https://docs.python.org/3/library/constants.html#None)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.CreateParameter"></a>

### CompositeCriterion.CreateParameter(propName: [str](https://docs.python.org/3/library/stdtypes.html#str)) → Ansys.ACT.Interfaces.Mechanical.IParameter

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Delete"></a>

### CompositeCriterion.Delete() → [None](https://docs.python.org/3/library/constants.html#None)

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.Duplicate"></a>

### CompositeCriterion.Duplicate() → [Ansys.Mechanical.DataModel.Interfaces.IDataModelObject](../../../Mechanical/DataModel/Interfaces/IDataModelObject.md#ansys.mechanical.stubs.v252.Ansys.Mechanical.DataModel.Interfaces.IDataModelObject)

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.EvaluateAllResults"></a>

### CompositeCriterion.EvaluateAllResults() → [None](https://docs.python.org/3/library/constants.html#None)

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.GetChildren"></a>

### CompositeCriterion.GetChildren(recurses: [bool](https://docs.python.org/3/library/functions.html#bool), children: List[ChildrenType]) → List[ChildrenType]

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.GetDefinition"></a>

### CompositeCriterion.GetDefinition() → [Ansys.ACT.Automation.Mechanical.CompositeCriterionDefinition](CompositeCriterionDefinition.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.CompositeCriterionDefinition)

```text
Gets the Worksheet Definition.
This Definition is a list of CompositeCriterionTerms.
```

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.GetParameter"></a>

### CompositeCriterion.GetParameter(propName: [str](https://docs.python.org/3/library/stdtypes.html#str)) → Ansys.ACT.Interfaces.Mechanical.IParameter

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.GroupAllSimilarChildren"></a>

### CompositeCriterion.GroupAllSimilarChildren() → [None](https://docs.python.org/3/library/constants.html#None)

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.GroupSimilarObjects"></a>

### CompositeCriterion.GroupSimilarObjects() → [Ansys.ACT.Automation.Mechanical.TreeGroupingFolder](TreeGroupingFolder.md#ansys.mechanical.stubs.v252.Ansys.ACT.Automation.Mechanical.TreeGroupingFolder)

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.PropertyByAPIName"></a>

### CompositeCriterion.PropertyByAPIName(name: [str](https://docs.python.org/3/library/stdtypes.html#str)) → Ansys.ACT.Automation.Mechanical.Property

```text
Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.
```

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.PropertyByName"></a>

### CompositeCriterion.PropertyByName(name: [str](https://docs.python.org/3/library/stdtypes.html#str)) → Ansys.ACT.Automation.Mechanical.Property

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="CompositeCriterion.RemoveParameter"></a>

### CompositeCriterion.RemoveParameter(propName: [str](https://docs.python.org/3/library/stdtypes.html#str)) → [None](https://docs.python.org/3/library/constants.html#None)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->

