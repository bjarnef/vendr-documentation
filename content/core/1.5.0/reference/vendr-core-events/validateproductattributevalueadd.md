---
title: ValidateProductAttributeValueAdd
description: API reference for ValidateProductAttributeValueAdd in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateProductAttributeValueAdd

```csharp
public class ValidateProductAttributeValueAdd : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateProductAttributeValueAdd

```csharp
public ValidateProductAttributeValueAdd(ProductAttributeReadOnly productAttribute, 
    ProductAttributeValueReadOnly value, int index)
```


### Properties

#### Index

```csharp
public int Index { get; }
```


---

#### ProductAttribute

```csharp
public ProductAttributeReadOnly ProductAttribute { get; }
```


---

#### Value

```csharp
public ProductAttributeValueReadOnly Value { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
