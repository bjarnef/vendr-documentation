---
title: ValidatePrintTemplateAliasChange
description: API reference for ValidatePrintTemplateAliasChange in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidatePrintTemplateAliasChange

```csharp
public class ValidatePrintTemplateAliasChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidatePrintTemplateAliasChange

```csharp
public ValidatePrintTemplateAliasChange(PrintTemplateReadOnly printTemplate, 
    ChangingValue<string> alias)
```


### Properties

#### Alias

```csharp
public ChangingValue<string> Alias { get; }
```


---

#### PrintTemplate

```csharp
public PrintTemplateReadOnly PrintTemplate { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
