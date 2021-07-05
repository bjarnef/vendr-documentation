---
title: ExportTemplateService
description: API reference for ExportTemplateService in Vendr, the eCommerce solution for Umbraco v8+
---
## ExportTemplateService

```csharp
public class ExportTemplateService : ServiceBase, IExportTemplateService
```

**Inheritance**

* class [ServiceBase](../servicebase/)
* interface [IExportTemplateService](../iexporttemplateservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### ExportTemplateService

```csharp
public ExportTemplateService(ILicensingService licensingService, 
    IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, ILogger logger, 
    ICacheAccessor cacheAccessor)
```


### Methods

#### DeleteExportTemplate (1 of 2)

```csharp
public void DeleteExportTemplate(Guid id)
```

---

#### DeleteExportTemplate (2 of 2)

```csharp
public void DeleteExportTemplate(ExportTemplate entity)
```


---

#### ExportTemplateExists

```csharp
public bool ExportTemplateExists(Guid storeId, string alias)
```


---

#### GetExportTemplate (1 of 2)

```csharp
public ExportTemplateReadOnly GetExportTemplate(Guid id)
```

---

#### GetExportTemplate (2 of 2)

```csharp
public ExportTemplateReadOnly GetExportTemplate(Guid storeId, string alias)
```


---

#### GetExportTemplates (1 of 2)

```csharp
public IEnumerable<ExportTemplateReadOnly> GetExportTemplates(Guid storeId)
```

---

#### GetExportTemplates (2 of 2)

```csharp
public IEnumerable<ExportTemplateReadOnly> GetExportTemplates(Guid[] ids)
```


---

#### SaveExportTemplate

```csharp
public void SaveExportTemplate(ExportTemplate entity)
```


---

#### SortExportTemplates

```csharp
public void SortExportTemplates(Guid[] sortedIds)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->