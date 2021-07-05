---
title: OrderIsDiscountedSpecification
description: API reference for OrderIsDiscountedSpecification in Vendr, the eCommerce solution for Umbraco v8+
---
## OrderIsDiscountedSpecification

```csharp
public class OrderIsDiscountedSpecification : IQuerySpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.Order.Implement](../)

### Constructors

#### OrderIsDiscountedSpecification (1 of 2)

```csharp
public OrderIsDiscountedSpecification(Guid discountId)
```

---

#### OrderIsDiscountedSpecification (2 of 2)

```csharp
public OrderIsDiscountedSpecification(IEnumerable<Guid> discountIds)
```


### Properties

#### DiscountIds

```csharp
public IEnumerable<Guid> DiscountIds { get; }
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