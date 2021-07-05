---
title: PublishedContentExtensions
description: API reference for PublishedContentExtensions in Vendr, the eCommerce solution for Umbraco v8+
---
## PublishedContentExtensions

```csharp
public static class PublishedContentExtensions
```

**Namespace**
* [Vendr.Web](../)

### Methods

#### GetProductSourceNode

Gets a product nodes source if one exists. Only to be used if using Umbraco nodes as product information data source.

```csharp
public static IPublishedContent GetProductSourceNode(this IPublishedContent productNode, 
    bool recursive = true)
```

**Parameters**

| Parameter | Description |
| --- | --- |
| productNode | The product node that is linked to the product source node. |
| recursive | Whether to search recursively for the source relation. |


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->