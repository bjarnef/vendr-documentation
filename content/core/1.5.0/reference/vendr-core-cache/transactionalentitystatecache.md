---
title: TransactionalEntityStateCache
description: API reference for TransactionalEntityStateCache in Vendr, the eCommerce solution for Umbraco v8+
---
## TransactionalEntityStateCache

```csharp
public class TransactionalEntityStateCache : IDisposable, IEntityStateCache
```

**Inheritance**

* interface [IEntityStateCache](../ientitystatecache/)

**Namespace**
* [Vendr.Core.Cache](../)

### Constructors

#### TransactionalEntityStateCache

```csharp
public TransactionalEntityStateCache(ICache systemCache, ICacheFactory inMemoryCacheFactory, 
    ILogger logger)
```


### Methods

#### ClearStateCache&lt;T&gt;

```csharp
public void ClearStateCache<T>(string cacheKey)
    where T : EntityStateBase
```


---

#### CommitTransaction

```csharp
public void CommitTransaction()
```


---

#### Dispose

```csharp
public void Dispose()
```


---

#### GetStateCache&lt;T&gt; (1 of 2)

```csharp
public IConcurrentDictionary<Guid, Lazy<T>> GetStateCache<T>(string cacheKey)
    where T : EntityStateBase
```

---

#### GetStateCache&lt;T&gt; (2 of 2)

```csharp
public IConcurrentDictionary<Guid, Lazy<T>> GetStateCache<T>(string cacheKey, 
    Func<IConcurrentDictionary<Guid, Lazy<T>>> factory)
    where T : EntityStateBase
```


---

#### RollbackTransaction

```csharp
public void RollbackTransaction()
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
