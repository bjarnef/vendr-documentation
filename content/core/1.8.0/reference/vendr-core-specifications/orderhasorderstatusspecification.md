---
title: OrderHasOrderStatusSpecification
description: API reference for OrderHasOrderStatusSpecification in Vendr, the eCommerce solution for Umbraco v8+
---
## OrderHasOrderStatusSpecification

```csharp
public class OrderHasOrderStatusSpecification : IQuerySpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.Order.Implement](../)

### Constructors

#### OrderHasOrderStatusSpecification (1 of 2)

```csharp
public OrderHasOrderStatusSpecification(Guid orderStatusId)
```

---

#### OrderHasOrderStatusSpecification (2 of 2)

```csharp
public OrderHasOrderStatusSpecification(IEnumerable<Guid> orderStatusIds)
```


### Properties

#### OrderStatusIds

```csharp
public IEnumerable<Guid> OrderStatusIds { get; }
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
