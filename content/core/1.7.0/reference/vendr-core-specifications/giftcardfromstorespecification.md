---
title: GiftCardFromStoreSpecification
description: API reference for GiftCardFromStoreSpecification in Vendr, the eCommerce solution for Umbraco v8+
---
## GiftCardFromStoreSpecification

```csharp
public class GiftCardFromStoreSpecification : IQuerySpecification<GiftCardReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.GiftCard.Implement](../)

### Constructors

#### GiftCardFromStoreSpecification

```csharp
public GiftCardFromStoreSpecification(Guid storeId)
```


### Properties

#### StoreId

```csharp
public Guid StoreId { get; }
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor, IVisitContext context)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(GiftCardReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->