---
title: RegionCacheRefresher
description: API reference for RegionCacheRefresher in Vendr, the eCommerce solution for Umbraco v8+
---
## RegionCacheRefresher

```csharp
public class RegionCacheRefresher : 
    VendrEntityStateCacheRefresherBase<RegionCacheRefresher, ICountryService, RegionReadOnly>
```

**Inheritance**

* class [VendrEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](../vendrentitystatecacherefresherbase-3/)

**Namespace**
* [Vendr.Web.Cache](../)

### Constructors

#### RegionCacheRefresher

```csharp
public RegionCacheRefresher(AppCaches appCaches, Lazy<ICountryService> entityService, 
    Lazy<ILogger> logger)
```


### Properties

#### Name

```csharp
public override string Name { get; }
```


---

#### RefresherUniqueId

```csharp
public override Guid RefresherUniqueId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->
