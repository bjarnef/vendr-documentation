---
title: VariantsEditorValueConverter
description: API reference for VariantsEditorValueConverter in Vendr, the eCommerce solution for Umbraco v8+
---
## VariantsEditorValueConverter

```csharp
public class VariantsEditorValueConverter : PropertyValueConverterBase
```

**Namespace**
* [Vendr.Web.Converters](../)

### Constructors

#### VariantsEditorValueConverter

```csharp
public VariantsEditorValueConverter(IVariationContextAccessor variationContextAccessor, 
    IProfilingLogger proflog, BlockEditorConverter blockConverter)
```


### Methods

#### ConvertIntermediateToObject

```csharp
public override object ConvertIntermediateToObject(IPublishedElement owner, 
    IPublishedPropertyType propertyType, PropertyCacheLevel referenceCacheLevel, object source, 
    bool preview)
```


---

#### ConvertSourceToIntermediate

```csharp
public override object ConvertSourceToIntermediate(IPublishedElement owner, 
    IPublishedPropertyType propertyType, object source, bool preview)
```


---

#### GetPropertyCacheLevel

```csharp
public override PropertyCacheLevel GetPropertyCacheLevel(IPublishedPropertyType propertyType)
```


---

#### GetPropertyValueType

```csharp
public override Type GetPropertyValueType(IPublishedPropertyType propertyType)
```


---

#### IsConverter

```csharp
public override bool IsConverter(IPublishedPropertyType propertyType)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->
