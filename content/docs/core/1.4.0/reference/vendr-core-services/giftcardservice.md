---
title: GiftCardService
description: API reference for GiftCardService in Vendr, the eCommerce solution for Umbraco v8+
---
## GiftCardService

```csharp
public class GiftCardService : EntityServiceBase, IGiftCardService
```

**Inheritance**

* class [EntityServiceBase](../entityservicebase/)
* interface [IGiftCardService](../igiftcardservice/)

**Namespace**
* [Vendr.Core.Services](../)

### Constructors

#### GiftCardService

```csharp
public GiftCardService(ILicensingService licensingService, IRepositoryFactory repositoryFactory, 
    IUnitOfWorkProvider uowProvider, ILogger logger, ICache cache, 
    IEntityStateCacheAccessor entityStateCacheAccessor, 
    IGiftCardCodeGenerator giftCardCodeGenerator)
```


### Methods

#### DeleteGiftCard (1 of 2)

```csharp
public void DeleteGiftCard(Guid id)
```

---

#### DeleteGiftCard (2 of 2)

```csharp
public void DeleteGiftCard(GiftCard entity)
```


---

#### GenerateGiftCardCode

```csharp
public string GenerateGiftCardCode(Guid storeId)
```


---

#### GetActiveGiftCards

```csharp
public IEnumerable<GiftCardReadOnly> GetActiveGiftCards(Guid storeId)
```


---

#### GetGiftCard (1 of 2)

```csharp
public GiftCardReadOnly GetGiftCard(Guid id)
```

---

#### GetGiftCard (2 of 2)

```csharp
public GiftCardReadOnly GetGiftCard(Guid storeId, string code)
```


---

#### GetGiftCards

```csharp
public IEnumerable<GiftCardReadOnly> GetGiftCards(Guid storeId)
```


---

#### GetGiftCardsByOrder

```csharp
public IEnumerable<GiftCardReadOnly> GetGiftCardsByOrder(Guid orderId)
```


---

#### GiftCardExists

```csharp
public bool GiftCardExists(Guid storeId, string code)
```


---

#### InvalidateEntityCache

```csharp
public void InvalidateEntityCache(Guid entityId)
```


---

#### SaveGiftCard

```csharp
public void SaveGiftCard(GiftCard entity)
```


---

#### SearchGiftCards

```csharp
public PagedResult<GiftCardReadOnly> SearchGiftCards(Guid storeId, string searchTerm = null, 
    string code = null, string cartOrOrderNumber = null, Guid? currencyId = default(Guid?), 
    DateTime? fromDate = default(DateTime?), DateTime? toDate = default(DateTime?), 
    long currentPage = 1, long itemsPerPage = 50)
```


---

#### ValidateGiftCard

```csharp
public bool ValidateGiftCard(Guid storeId, string code, Guid currencyId)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->