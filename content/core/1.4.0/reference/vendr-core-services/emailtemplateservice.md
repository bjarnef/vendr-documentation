---
title: EmailTemplateService
description: API reference for EmailTemplateService in Vendr, the eCommerce solution for Umbraco v8+
---
## EmailTemplateService

```csharp
public class EmailTemplateService : EntityServiceBase, IEmailTemplateService
```

**Inheritance**

* class [EntityServiceBase](../entityservicebase/)
* interface [IEmailTemplateService](../iemailtemplateservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### EmailTemplateService

```csharp
public EmailTemplateService(ILicensingService licensingService, 
    IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, ILogger logger, 
    ICache cache, IEntityStateCacheAccessor entityStateCacheAccessor)
```


### Methods

#### DeleteEmailTemplate (1 of 2)

```csharp
public void DeleteEmailTemplate(Guid id)
```

---

#### DeleteEmailTemplate (2 of 2)

```csharp
public void DeleteEmailTemplate(EmailTemplate entity)
```


---

#### EmailTemplateExists

```csharp
public bool EmailTemplateExists(Guid storeId, string alias)
```


---

#### GetEmailTemplate (1 of 2)

```csharp
public EmailTemplateReadOnly GetEmailTemplate(Guid id)
```

---

#### GetEmailTemplate (2 of 2)

```csharp
public EmailTemplateReadOnly GetEmailTemplate(Guid storeId, string alias)
```


---

#### GetEmailTemplates

```csharp
public IEnumerable<EmailTemplateReadOnly> GetEmailTemplates(Guid storeId)
```


---

#### SaveEmailTemplate

```csharp
public void SaveEmailTemplate(EmailTemplate entity)
```


---

#### SendEmail

```csharp
public bool SendEmail(EmailTemplateReadOnly emailTemplate, OrderReadOnly order)
```


---

#### SendEmail&lt;TModel&gt;

```csharp
public bool SendEmail<TModel>(EmailTemplateReadOnly emailTemplate, TModel model, 
    string toEmailAddress, string languageIsoCode)
```


---

#### SortEmailTemplates

```csharp
public void SortEmailTemplates(Guid[] sortedIds)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
