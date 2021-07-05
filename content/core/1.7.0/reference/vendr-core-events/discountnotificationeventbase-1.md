---
title: DiscountNotificationEventBase<TEntity>
description: API reference for DiscountNotificationEventBase<TEntity> in Vendr, the eCommerce solution for Umbraco v8+
---
## DiscountNotificationEventBase&lt;TEntity&gt;

```csharp
public abstract class DiscountNotificationEventBase<TEntity> : NotificationEventBase
    where TEntity : DiscountReadOnly
```

**Inheritance**

* class [NotificationEventBase](../notificationeventbase/)

**Namespace**
* [Vendr.Core.Events.Notification](../)

### Constructors

#### DiscountNotificationEventBase&lt;TEntity&gt;

```csharp
public DiscountNotificationEventBase(TEntity discount)
```


### Properties

#### Discount

```csharp
public TEntity Discount { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->