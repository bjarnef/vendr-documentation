---
title: ValidateLicenseMaxActiveGiftCards
description: API reference for ValidateLicenseMaxActiveGiftCards in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateLicenseMaxActiveGiftCards

```csharp
public class ValidateLicenseMaxActiveGiftCards : ValidationEventHandlerBase<ValidateGiftCardSave>
```

**Inheritance**

* class [ValidationEventHandlerBase&lt;TValidationEvent&gt;](../validationeventhandlerbase-1/)

**Namespace**
* [Vendr.Core.Events.Validation.Handlers.GiftCard](../)

### Constructors

#### ValidateLicenseMaxActiveGiftCards

```csharp
public ValidateLicenseMaxActiveGiftCards(ILicensingService licensingService, 
    IGiftCardService giftCardService)
```


### Methods

#### Validate

```csharp
public override void Validate(ValidateGiftCardSave evt)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
