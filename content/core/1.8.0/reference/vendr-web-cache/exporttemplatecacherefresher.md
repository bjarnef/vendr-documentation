---
title: ExportTemplateCacheRefresher
description: API reference for ExportTemplateCacheRefresher in Vendr, the eCommerce solution for Umbraco v8+
---
## ExportTemplateCacheRefresher

```csharp
public class ExportTemplateCacheRefresher : 
    VendrEntityStateCacheRefresherBase<ExportTemplateCacheRefresher, IExportTemplateService, ExportTemplateReadOnly>
```

**Inheritance**

* class [VendrEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](../vendrentitystatecacherefresherbase-3/)

**Namespace**
* [Vendr.Web.Cache](../)

### Constructors

#### ExportTemplateCacheRefresher

```csharp
public ExportTemplateCacheRefresher(AppCaches appCaches, 
    Lazy<IExportTemplateService> entityService, Lazy<ILogger> logger)
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
