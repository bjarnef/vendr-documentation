---
title: PriceAdjusterArgs
description: API reference for PriceAdjusterArgs in Vendr, the eCommerce solution for Umbraco v8+
---
## PriceAdjusterArgs

```csharp
public class PriceAdjusterArgs : AdjusterArgsBase
```

**Inheritance**

* class [AdjusterArgsBase](../adjusterargsbase/)

**Namespace**
* [Vendr.Core.Adjusters](../)

### Properties

#### OrderLines

```csharp
public DictionaryAccessor<Guid, OrderLinePriceAdjustments> OrderLines { get; }
```


---

#### PaymentTotalPriceAdjustments

```csharp
public List<PriceAdjustment> PaymentTotalPriceAdjustments { get; }
```


---

#### ShippingTotalPriceAdjustments

```csharp
public List<PriceAdjustment> ShippingTotalPriceAdjustments { get; }
```


---

#### SubtotalPriceAdjustments

```csharp
public List<PriceAdjustment> SubtotalPriceAdjustments { get; }
```


---

#### TotalPriceAdjustments

```csharp
public List<PriceAdjustment> TotalPriceAdjustments { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->