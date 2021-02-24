---
title: CreateDefaultOrderStatusesTask
description: API reference for CreateDefaultOrderStatusesTask in Vendr, the eCommerce solution for Umbraco v8+
---
## CreateDefaultOrderStatusesTask

```csharp
public class CreateDefaultOrderStatusesTask : 
    PipelineTaskWithTypedArgsBase<InitStorePipelineArgs, Store>
```

**Inheritance**

* class [PipelineTaskWithTypedArgsBase&lt;TArgs,T&gt;](../pipelinetaskwithtypedargsbase-2/)

**Namespace**
* [Vendr.Core.Pipelines.Store.Tasks](../)

### Constructors

#### CreateDefaultOrderStatusesTask

```csharp
public CreateDefaultOrderStatusesTask(IOrderStatusService orderStatusService)
```


### Methods

#### Execute

```csharp
public override PipelineResult<Store> Execute(InitStorePipelineArgs args)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->