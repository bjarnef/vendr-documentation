---
title: PrintTemplateService
description: API reference for PrintTemplateService in Vendr, the eCommerce solution for Umbraco v8+
---
## PrintTemplateService

```csharp
public class PrintTemplateService : ServiceBase, IPrintTemplateService
```

**Inheritance**

* class [ServiceBase](../servicebase/)
* interface [IPrintTemplateService](../iprinttemplateservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### PrintTemplateService

```csharp
public PrintTemplateService(ILicensingService licensingService, 
    IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, ILogger logger, 
    ICacheAccessor cacheAccessor)
```


### Methods

#### DeletePrintTemplate (1 of 2)

```csharp
public void DeletePrintTemplate(Guid id)
```

---

#### DeletePrintTemplate (2 of 2)

```csharp
public void DeletePrintTemplate(PrintTemplate entity)
```


---

#### GetPrintTemplate (1 of 2)

```csharp
public PrintTemplateReadOnly GetPrintTemplate(Guid id)
```

---

#### GetPrintTemplate (2 of 2)

```csharp
public PrintTemplateReadOnly GetPrintTemplate(Guid storeId, string alias)
```


---

#### GetPrintTemplates (1 of 2)

```csharp
public IEnumerable<PrintTemplateReadOnly> GetPrintTemplates(Guid storeId)
```

---

#### GetPrintTemplates (2 of 2)

```csharp
public IEnumerable<PrintTemplateReadOnly> GetPrintTemplates(Guid[] ids)
```


---

#### PrintTemplateExists

```csharp
public bool PrintTemplateExists(Guid storeId, string alias)
```


---

#### SavePrintTemplate

```csharp
public void SavePrintTemplate(PrintTemplate entity)
```


---

#### SortPrintTemplates

```csharp
public void SortPrintTemplates(Guid[] sortedIds)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->