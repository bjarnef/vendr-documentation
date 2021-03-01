---
title: ValidateProductAttributeValueNameChange
description: API reference for ValidateProductAttributeValueNameChange in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateProductAttributeValueNameChange

```csharp
public class ValidateProductAttributeValueNameChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateProductAttributeValueNameChange

```csharp
public ValidateProductAttributeValueNameChange(ProductAttributeReadOnly productAttribute, 
    ProductAttributeValueReadOnly value, int index, 
    ChangingValue<ReadOnlyTranslatedValue<string>> name)
```


### Properties

#### Index

```csharp
public int Index { get; }
```


---

#### Name

```csharp
public ChangingValue<ReadOnlyTranslatedValue<string>> Name { get; }
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