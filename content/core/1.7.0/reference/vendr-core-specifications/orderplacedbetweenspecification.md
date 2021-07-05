---
title: OrderPlacedBetweenSpecification
description: API reference for OrderPlacedBetweenSpecification in Vendr, the eCommerce solution for Umbraco v8+
---
## OrderPlacedBetweenSpecification

```csharp
public class OrderPlacedBetweenSpecification : IQuerySpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.Order.Implement](../)

### Constructors

#### OrderPlacedBetweenSpecification

```csharp
public OrderPlacedBetweenSpecification(DateTime? fromDate, DateTime? toDate)
```


### Fields

#### FromDate

```csharp
public DateTime? FromDate;
```


---

#### ToDate

```csharp
public DateTime? ToDate;
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