---
title: IProductAdapter
description: API reference for IProductAdapter in Vendr, the eCommerce solution for Umbraco v8+
---
## IProductAdapter

```csharp
public interface IProductAdapter
```

**Namespace**
* [Vendr.Core.Adapters](../)

### Methods

#### GetProductReference

Get a product reference for the product in the given store with a given SKU.

```csharp
public string GetProductReference(Guid storeId, string sku)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| storeId | The store id of the store |
| sku | The SKU of the product |


---

#### GetProductSnapshot

Get a product snapshot for the supplied product reference in the given culture.

```csharp
public IProductSnapshot GetProductSnapshot(string productReference, string languageIsoCode)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| productReference | The product reference of the product |
| languageIsoCode | The language ISO code of the culture |


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->