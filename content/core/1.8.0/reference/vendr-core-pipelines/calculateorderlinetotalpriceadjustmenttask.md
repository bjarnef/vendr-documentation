---
title: CalculateOrderLineTotalPriceAdjustmentTask
description: API reference for CalculateOrderLineTotalPriceAdjustmentTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CalculateOrderLineTotalPriceAdjustmentTask

```csharp
public class CalculateOrderLineTotalPriceAdjustmentTask : 
    PipelineTaskWithTypedArgsBase<OrderLineCalculationPipelineArgs, OrderLineCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.OrderLine.Tasks](../)

### Constructors

#### CalculateOrderLineTotalPriceAdjustmentTask

The default constructor.

```csharp
public CalculateOrderLineTotalPriceAdjustmentTask()
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderLineCalculation> Execute(OrderLineCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
