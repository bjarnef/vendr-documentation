---
title: OrderIsFinalizedSpecification
description: API reference for OrderIsFinalizedSpecification in Vendr, the eCommerce solution for Umbraco v8+
---
## OrderIsFinalizedSpecification

```csharp
public class OrderIsFinalizedSpecification : IQuerySpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.Order.Implement](../)

### Constructors

#### OrderIsFinalizedSpecification

The default constructor.

```csharp
public OrderIsFinalizedSpecification()
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor, IVisitContext context)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(OrderReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->