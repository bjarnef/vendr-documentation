---
title: VendrEventHandlerComposer<TEvent,TInterface>
description: API reference for VendrEventHandlerComposer<TEvent,TInterface> in Vendr, the eCommerce solution for Umbraco v8+
---
## VendrEventHandlerComposer&lt;TEvent,TInterface&gt;

```csharp
public class VendrEventHandlerComposer<TEvent, TInterface>
    where TEvent : TInterface
    where TInterface : IEvent
```

**Namespace**
* [Vendr.Core.Composing](../)

### Methods

#### RegisterHandler&lt;THandler&gt;

```csharp
public VendrEventHandlerComposer RegisterHandler<THandler>()
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RegisterHandlerAfter&lt;TAfterHandler,THandler&gt;

```csharp
public VendrEventHandlerComposer RegisterHandlerAfter<TAfterHandler, THandler>()
    where TAfterHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RegisterHandlerBefore&lt;TBeforeHandler,THandler&gt;

```csharp
public VendrEventHandlerComposer RegisterHandlerBefore<TBeforeHandler, THandler>()
    where TBeforeHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


---

#### RemoveHandler&lt;THandler&gt;

```csharp
public VendrEventHandlerComposer RemoveHandler<THandler>()
    where THandler : IEventHandlerFor<TEvent>
```


---

#### ReplaceHandler&lt;TReplacedHandler,THandler&gt;

```csharp
public VendrEventHandlerComposer ReplaceHandler<TReplacedHandler, THandler>()
    where TReplacedHandler : IEventHandlerFor<TEvent>
    where THandler : IEventHandlerFor<TEvent>
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->