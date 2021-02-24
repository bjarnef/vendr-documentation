---
title: CountryCacheRefresher
description: API reference for CountryCacheRefresher in Vendr, the eCommerce solution for Umbraco v8+
---
## CountryCacheRefresher

```csharp
public class CountryCacheRefresher : 
    VendrEntityStateCacheRefresherBase<CountryCacheRefresher, ICountryService, CountryReadOnly>
```

**Inheritance**

* class [VendrEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](../vendrentitystatecacherefresherbase-3/)

**Namespace**
* [Vendr.Web.Cache](../)

### Constructors

#### CountryCacheRefresher

```csharp
public CountryCacheRefresher(AppCaches appCaches, ICountryService entityService)
```


### Properties

#### CacheKey

```csharp
public override string CacheKey { get; }
```


---

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