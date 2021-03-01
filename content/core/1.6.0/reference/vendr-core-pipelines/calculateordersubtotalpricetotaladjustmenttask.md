---
title: CalculateOrderSubtotalPriceTotalAdjustmentTask
description: API reference for CalculateOrderSubtotalPriceTotalAdjustmentTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CalculateOrderSubtotalPriceTotalAdjustmentTask

```csharp
public class CalculateOrderSubtotalPriceTotalAdjustmentTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Order.Tasks](../)

### Constructors

#### CalculateOrderSubtotalPriceTotalAdjustmentTask

The default constructor.

```csharp
public CalculateOrderSubtotalPriceTotalAdjustmentTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->