---
title: OrSpecification<T>
description: API reference for OrSpecification<T> in Vendr, the eCommerce solution for Umbraco v8+
---
## OrSpecification&lt;T&gt;

```csharp
public class OrSpecification<T> : IQuerySpecification<T>
```

**Inheritance**

* interface [IQuerySpecification&lt;T&gt;](../iqueryspecification-1/)

**Namespace**
* [Vendr.Core.Specifications.Common.Implement](../)

### Constructors

#### OrSpecification&lt;T&gt;

```csharp
public OrSpecification(IQuerySpecification<T> left, IQuerySpecification<T> right)
```


### Properties

#### Left

```csharp
public IQuerySpecification<T> Left { get; set; }
```


---

#### Right

```csharp
public IQuerySpecification<T> Right { get; set; }
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor, IVisitContext context)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(T item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
