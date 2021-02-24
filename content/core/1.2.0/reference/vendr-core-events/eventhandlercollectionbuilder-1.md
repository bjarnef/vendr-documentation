---
title: EventHandlerCollectionBuilder<TEvent>
description: API reference for EventHandlerCollectionBuilder<TEvent> in Vendr, the eCommerce solution for Umbraco v8+
---
## EventHandlerCollectionBuilder&lt;TEvent&gt;

```csharp
public class EventHandlerCollectionBuilder<TEvent> : 
    OrderedCollectionBuilderBase<EventHandlerCollectionBuilder, EventHandlerCollection<TEvent>, IEventHandlerFor<TEvent>>
    where TEvent : IEvent
```

**Namespace**
* [Vendr.Core.Events](../)

### Constructors

#### EventHandlerCollectionBuilder&lt;TEvent&gt;

The default constructor.

```csharp
public EventHandlerCollectionBuilder()
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->