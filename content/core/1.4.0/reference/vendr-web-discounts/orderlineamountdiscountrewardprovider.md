---
title: OrderLineAmountDiscountRewardProvider
description: API reference for OrderLineAmountDiscountRewardProvider in Vendr, the eCommerce solution for Umbraco v8+
---
## OrderLineAmountDiscountRewardProvider

```csharp
public class OrderLineAmountDiscountRewardProvider : 
    OrderLineAmountDiscountRewardProviderBase<OrderLineAmountDiscountRewardProviderSettings>
```

**Inheritance**

* class [OrderLineAmountDiscountRewardProviderBase&lt;TSettings&gt;](../orderlineamountdiscountrewardproviderbase-1/)

**Namespace**
* [Vendr.Web.Discounts.Rewards](../)

### Constructors

#### OrderLineAmountDiscountRewardProvider

The default constructor.

```csharp
public OrderLineAmountDiscountRewardProvider()
```


### Methods

#### FilterOrderLines

```csharp
public override IEnumerable<OrderLineReadOnly> FilterOrderLines(DiscountRewardContext ctx, 
    OrderLineAmountDiscountRewardProviderSettings settings)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->