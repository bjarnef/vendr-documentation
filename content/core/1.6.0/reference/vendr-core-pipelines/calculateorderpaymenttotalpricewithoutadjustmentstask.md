---
title: CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask
description: API reference for CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask

```csharp
public class CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask : 
    PipelineTaskWithTypedArgsBase<OrderCalculationPipelineArgs, OrderCalculation>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Order.Tasks](../)

### Constructors

#### CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask

```csharp
public CalculateOrderPaymentTotalPriceWithoutAdjustmentsTask(IPaymentCalculator paymentCalculator)
```


### Methods

#### Execute

```csharp
public override PipelineResult<OrderCalculation> Execute(OrderCalculationPipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
