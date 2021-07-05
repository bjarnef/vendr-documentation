---
title: SortSpecificationBase<T>
description: API reference for SortSpecificationBase<T> in Vendr, the eCommerce solution for Umbraco v8+
---
## SortSpecificationBase&lt;T&gt;

```csharp
public abstract class SortSpecificationBase<T> : ISortSpecification<T>
```

**Inheritance**

* interface [ISortSpecification&lt;T&gt;](../isortspecification-1/)

**Namespace**
* [Vendr.Core.Specifications](../)

### Properties

#### Sort

```csharp
public Sort Sort { get; }
```


### Methods

#### Accept

```csharp
public abstract void Accept(IVisitor visitor, IVisitContext context)
```


---

#### InvokeSort (1 of 2)

```csharp
public abstract IOrderedEnumerable<T> InvokeSort(IEnumerable<T> collection)
```

---

#### InvokeSort (2 of 2)

```csharp
public abstract IOrderedEnumerable<T> InvokeSort(IOrderedEnumerable<T> collection)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->