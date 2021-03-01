---
title: Vendr.Core.Events
description: API reference for Vendr.Core.Events in Vendr, the eCommerce solution for Umbraco v8+
---
## Vendr.Core.Events namespace

| Public Type | Description |
| --- | --- |
| static class [EventBus](eventbus/) |  |
| class [EventHandlerCollection&lt;TEvent&gt;](eventhandlercollection-1/) |  |
| class [EventHandlerCollectionBuilder&lt;TEvent&gt;](eventhandlercollectionbuilder-1/) |  |
| class [EventHandlerFactory](eventhandlerfactory/) |  |
| class [EventHub](eventhub/) |  |
| interface [IEvent](ievent/) |  |
| interface [IEventDispatcher](ieventdispatcher/) |  |
| interface [IEventHandler](ieventhandler/) |  |
| interface [IEventHandlerFactory](ieventhandlerfactory/) |  |
| interface [IEventHandlerFor&lt;T&gt;](ieventhandlerfor-1/) |  |
| interface [IHasEventKey](ihaseventkey/) |  |
| class [InProcEventDispatcher](inproceventdispatcher/) |  |
| abstract class [PipelineEventBase](pipelineeventbase/) |  |

## Vendr.Core.Events.Notification namespace

| Public Type | Description |
| --- | --- |
| class [CountryCreatedNotification](countrycreatednotification/) |  |
| class [CountryCreatingNotification](countrycreatingnotification/) |  |
| class [CountryDeletedNotification](countrydeletednotification/) |  |
| class [CountryDeletingNotification](countrydeletingnotification/) |  |
| abstract class [CountryNotificationEventBase&lt;TEntity&gt;](countrynotificationeventbase-1/) |  |
| class [CountrySavedNotification](countrysavednotification/) |  |
| class [CountrySavingNotification](countrysavingnotification/) |  |
| class [CountryUpdatedNotification](countryupdatednotification/) |  |
| class [CountryUpdatingNotification](countryupdatingnotification/) |  |
| class [CurrencyCreatedNotification](currencycreatednotification/) |  |
| class [CurrencyCreatingNotification](currencycreatingnotification/) |  |
| class [CurrencyDeletedNotification](currencydeletednotification/) |  |
| class [CurrencyDeletingNotification](currencydeletingnotification/) |  |
| abstract class [CurrencyNotificationEventBase&lt;TEntity&gt;](currencynotificationeventbase-1/) |  |
| class [CurrencySavedNotification](currencysavednotification/) |  |
| class [CurrencySavingNotification](currencysavingnotification/) |  |
| class [CurrencyUpdatedNotification](currencyupdatednotification/) |  |
| class [CurrencyUpdatingNotification](currencyupdatingnotification/) |  |
| class [DiscountCreatedNotification](discountcreatednotification/) |  |
| class [DiscountCreatingNotification](discountcreatingnotification/) |  |
| class [DiscountDeletedNotification](discountdeletednotification/) |  |
| class [DiscountDeletingNotification](discountdeletingnotification/) |  |
| abstract class [DiscountNotificationEventBase&lt;TEntity&gt;](discountnotificationeventbase-1/) |  |
| class [DiscountSavedNotification](discountsavednotification/) |  |
| class [DiscountSavingNotification](discountsavingnotification/) |  |
| class [DiscountUpdatedNotification](discountupdatednotification/) |  |
| class [DiscountUpdatingNotification](discountupdatingnotification/) |  |
| class [EmailFailedNotification](emailfailednotification/) |  |
| class [EmailSendingNotification](emailsendingnotification/) |  |
| class [EmailSentNotification](emailsentnotification/) |  |
| class [EmailTemplateCreatedNotification](emailtemplatecreatednotification/) |  |
| class [EmailTemplateCreatingNotification](emailtemplatecreatingnotification/) |  |
| class [EmailTemplateDeletedNotification](emailtemplatedeletednotification/) |  |
| class [EmailTemplateDeletingNotification](emailtemplatedeletingnotification/) |  |
| abstract class [EmailTemplateNotificationEventBase&lt;TEntity&gt;](emailtemplatenotificationeventbase-1/) |  |
| class [EmailTemplateSavedNotification](emailtemplatesavednotification/) |  |
| class [EmailTemplateSavingNotification](emailtemplatesavingnotification/) |  |
| class [EmailTemplateUpdatedNotification](emailtemplateupdatednotification/) |  |
| class [EmailTemplateUpdatingNotification](emailtemplateupdatingnotification/) |  |
| class [FrozenPricesThawedNotification](frozenpricesthawednotification/) |  |
| class [FrozenPricesThawingNotification](frozenpricesthawingnotification/) |  |
| class [GiftCardCreatedNotification](giftcardcreatednotification/) |  |
| class [GiftCardCreatingNotification](giftcardcreatingnotification/) |  |
| class [GiftCardDeletedNotification](giftcarddeletednotification/) |  |
| class [GiftCardDeletingNotification](giftcarddeletingnotification/) |  |
| abstract class [GiftCardNotificationEventBase&lt;TEntity&gt;](giftcardnotificationeventbase-1/) |  |
| class [GiftCardSavedNotification](giftcardsavednotification/) |  |
| class [GiftCardSavingNotification](giftcardsavingnotification/) |  |
| class [GiftCardUpdatedNotification](giftcardupdatednotification/) |  |
| class [GiftCardUpdatingNotification](giftcardupdatingnotification/) |  |
| interface [INotificationEvent](inotificationevent/) |  |
| abstract class [NotificationEventBase](notificationeventbase/) |  |
| abstract class [NotificationEventHandlerBase&lt;TNotificationEvent&gt;](notificationeventhandlerbase-1/) |  |
| class [OrderAssignedToCustomerNotification](orderassignedtocustomernotification/) |  |
| class [OrderAssigningToCustomerNotification](orderassigningtocustomernotification/) |  |
| abstract class [OrderAssignToCustomerNotificationBase&lt;TEntity&gt;](orderassigntocustomernotificationbase-1/) |  |
| abstract class [OrderCodeNotificationBase&lt;TEntity&gt;](ordercodenotificationbase-1/) |  |
| class [OrderCreatedNotification](ordercreatednotification/) |  |
| class [OrderCreatingNotification](ordercreatingnotification/) |  |
| class [OrderCurrencyChangedNotification](ordercurrencychangednotification/) |  |
| abstract class [OrderCurrencyChangeNotificationBase&lt;TEntity&gt;](ordercurrencychangenotificationbase-1/) |  |
| class [OrderCurrencyChangingNotification](ordercurrencychangingnotification/) |  |
| class [OrderDeletedNotification](orderdeletednotification/) |  |
| class [OrderDeletingNotification](orderdeletingnotification/) |  |
| class [OrderDiscountCodeRedeemedNotification](orderdiscountcoderedeemednotification/) |  |
| class [OrderDiscountCodeRedeemingNotification](orderdiscountcoderedeemingnotification/) |  |
| class [OrderDiscountCodeUnredeemedNotification](orderdiscountcodeunredeemednotification/) |  |
| class [OrderDiscountCodeUnredeemingNotification](orderdiscountcodeunredeemingnotification/) |  |
| class [OrderFinalizedNotification](orderfinalizednotification/) |  |
| class [OrderFinalizingNotification](orderfinalizingnotification/) |  |
| class [OrderGiftCardRedeemedNotification](ordergiftcardredeemednotification/) |  |
| class [OrderGiftCardRedeemingNotification](ordergiftcardredeemingnotification/) |  |
| class [OrderGiftCardUnredeemedNotification](ordergiftcardunredeemednotification/) |  |
| class [OrderGiftCardUnredeemingNotification](ordergiftcardunredeemingnotification/) |  |
| class [OrderLanguageChangedNotification](orderlanguagechangednotification/) |  |
| abstract class [OrderLanguageChangeNotificationBase&lt;TEntity&gt;](orderlanguagechangenotificationbase-1/) |  |
| class [OrderLanguageChangingNotification](orderlanguagechangingnotification/) |  |
| class [OrderLineAddedNotification](orderlineaddednotification/) |  |
| class [OrderLineAddingNotification](orderlineaddingnotification/) |  |
| class [OrderLineAddNotification&lt;TEntity&gt;](orderlineaddnotification-1/) |  |
| class [OrderLineChangedNotification](orderlinechangednotification/) |  |
| class [OrderLineChangeNotification&lt;TEntity&gt;](orderlinechangenotification-1/) |  |
| class [OrderLineChangingNotification](orderlinechangingnotification/) |  |
| class [OrderLineRemovedNotification](orderlineremovednotification/) |  |
| class [OrderLineRemoveNotification&lt;TEntity&gt;](orderlineremovenotification-1/) |  |
| class [OrderLineRemovingNotification](orderlineremovingnotification/) |  |
| abstract class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1/) |  |
| class [OrderPaymentCountryRegionChangedNotification](orderpaymentcountryregionchangednotification/) |  |
| abstract class [OrderPaymentCountryRegionChangeNotificationBase&lt;TEntity&gt;](orderpaymentcountryregionchangenotificationbase-1/) |  |
| class [OrderPaymentCountryRegionChangingNotification](orderpaymentcountryregionchangingnotification/) |  |
| class [OrderPaymentMethodChangedNotification](orderpaymentmethodchangednotification/) |  |
| abstract class [OrderPaymentMethodChangeNotificationBase&lt;TEntity&gt;](orderpaymentmethodchangenotificationbase-1/) |  |
| class [OrderPaymentMethodChangingNotification](orderpaymentmethodchangingnotification/) |  |
| class [OrderProductAddedNotification](orderproductaddednotification/) |  |
| class [OrderProductAddingNotification](orderproductaddingnotification/) |  |
| abstract class [OrderProductAddNotificationBase&lt;TEntity&gt;](orderproductaddnotificationbase-1/) |  |
| class [OrderPropertiesChangedNotification](orderpropertieschangednotification/) |  |
| abstract class [OrderPropertiesChangeNotificationBase&lt;TEntity&gt;](orderpropertieschangenotificationbase-1/) |  |
| class [OrderPropertiesChangingNotification](orderpropertieschangingnotification/) |  |
| class [OrderSavedNotification](ordersavednotification/) |  |
| class [OrderSavingNotification](ordersavingnotification/) |  |
| class [OrderShippingCountryRegionChangedNotification](ordershippingcountryregionchangednotification/) |  |
| abstract class [OrderShippingCountryRegionChangeNotificationBase&lt;TEntity&gt;](ordershippingcountryregionchangenotificationbase-1/) |  |
| class [OrderShippingCountryRegionChangingNotification](ordershippingcountryregionchangingnotification/) |  |
| class [OrderShippingMethodChangedNotification](ordershippingmethodchangednotification/) |  |
| abstract class [OrderShippingMethodChangeNotificationBase&lt;TEntity&gt;](ordershippingmethodchangenotificationbase-1/) |  |
| class [OrderShippingMethodChangingNotification](ordershippingmethodchangingnotification/) |  |
| class [OrderStatusChangedNotification](orderstatuschangednotification/) |  |
| abstract class [OrderStatusChangeNotificationBase&lt;TEntity&gt;](orderstatuschangenotificationbase-1/) |  |
| class [OrderStatusChangingNotification](orderstatuschangingnotification/) |  |
| class [OrderStatusCreatedNotification](orderstatuscreatednotification/) |  |
| class [OrderStatusCreatingNotification](orderstatuscreatingnotification/) |  |
| class [OrderStatusDeletedNotification](orderstatusdeletednotification/) |  |
| class [OrderStatusDeletingNotification](orderstatusdeletingnotification/) |  |
| abstract class [OrderStatusNotificationEventBase&lt;TEntity&gt;](orderstatusnotificationeventbase-1/) |  |
| class [OrderStatusSavedNotification](orderstatussavednotification/) |  |
| class [OrderStatusSavingNotification](orderstatussavingnotification/) |  |
| class [OrderStatusUpdatedNotification](orderstatusupdatednotification/) |  |
| class [OrderStatusUpdatingNotification](orderstatusupdatingnotification/) |  |
| class [OrderTaxClassChangedNotification](ordertaxclasschangednotification/) |  |
| abstract class [OrderTaxClassChangeNotificationBase&lt;TEntity&gt;](ordertaxclasschangenotificationbase-1/) |  |
| class [OrderTaxClassChangingNotification](ordertaxclasschangingnotification/) |  |
| abstract class [OrderTransactionChangeNotificationBase&lt;TEntity&gt;](ordertransactionchangenotificationbase-1/) |  |
| class [OrderTransactionUpdatedNotification](ordertransactionupdatednotification/) |  |
| class [OrderTransactionUpdatingNotification](ordertransactionupdatingnotification/) |  |
| class [OrderUpdatedNotification](orderupdatednotification/) |  |
| class [OrderUpdatingNotification](orderupdatingnotification/) |  |
| class [PaymentMethodCreatedNotification](paymentmethodcreatednotification/) |  |
| class [PaymentMethodCreatingNotification](paymentmethodcreatingnotification/) |  |
| class [PaymentMethodDeletedNotification](paymentmethoddeletednotification/) |  |
| class [PaymentMethodDeletingNotification](paymentmethoddeletingnotification/) |  |
| abstract class [PaymentMethodNotificationEventBase&lt;TEntity&gt;](paymentmethodnotificationeventbase-1/) |  |
| class [PaymentMethodSavedNotification](paymentmethodsavednotification/) |  |
| class [PaymentMethodSavingNotification](paymentmethodsavingnotification/) |  |
| class [PaymentMethodUpdatedNotification](paymentmethodupdatednotification/) |  |
| class [PaymentMethodUpdatingNotification](paymentmethodupdatingnotification/) |  |
| class [PipelineFailNotification](pipelinefailnotification/) |  |
| class [PipelineSuccessNotification](pipelinesuccessnotification/) |  |
| class [ProductAttributeCreatedNotification](productattributecreatednotification/) |  |
| class [ProductAttributeCreatingNotification](productattributecreatingnotification/) |  |
| class [ProductAttributeDeletedNotification](productattributedeletednotification/) |  |
| class [ProductAttributeDeletingNotification](productattributedeletingnotification/) |  |
| abstract class [ProductAttributeNotificationEventBase&lt;TEntity&gt;](productattributenotificationeventbase-1/) |  |
| class [ProductAttributePresetCreatedNotification](productattributepresetcreatednotification/) |  |
| class [ProductAttributePresetCreatingNotification](productattributepresetcreatingnotification/) |  |
| class [ProductAttributePresetDeletedNotification](productattributepresetdeletednotification/) |  |
| class [ProductAttributePresetDeletingNotification](productattributepresetdeletingnotification/) |  |
| abstract class [ProductAttributePresetNotificationEventBase&lt;TEntity&gt;](productattributepresetnotificationeventbase-1/) |  |
| class [ProductAttributePresetSavedNotification](productattributepresetsavednotification/) |  |
| class [ProductAttributePresetSavingNotification](productattributepresetsavingnotification/) |  |
| class [ProductAttributePresetUpdatedNotification](productattributepresetupdatednotification/) |  |
| class [ProductAttributePresetUpdatingNotification](productattributepresetupdatingnotification/) |  |
| class [ProductAttributeSavedNotification](productattributesavednotification/) |  |
| class [ProductAttributeSavingNotification](productattributesavingnotification/) |  |
| class [ProductAttributeUpdatedNotification](productattributeupdatednotification/) |  |
| class [ProductAttributeUpdatingNotification](productattributeupdatingnotification/) |  |
| class [RegionCreatedNotification](regioncreatednotification/) |  |
| class [RegionCreatingNotification](regioncreatingnotification/) |  |
| class [RegionDeletedNotification](regiondeletednotification/) |  |
| class [RegionDeletingNotification](regiondeletingnotification/) |  |
| abstract class [RegionNotificationEventBase&lt;TEntity&gt;](regionnotificationeventbase-1/) |  |
| class [RegionSavedNotification](regionsavednotification/) |  |
| class [RegionSavingNotification](regionsavingnotification/) |  |
| class [RegionUpdatedNotification](regionupdatednotification/) |  |
| class [RegionUpdatingNotification](regionupdatingnotification/) |  |
| class [ShippingMethodCreatedNotification](shippingmethodcreatednotification/) |  |
| class [ShippingMethodCreatingNotification](shippingmethodcreatingnotification/) |  |
| class [ShippingMethodDeletedNotification](shippingmethoddeletednotification/) |  |
| class [ShippingMethodDeletingNotification](shippingmethoddeletingnotification/) |  |
| abstract class [ShippingMethodNotificationEventBase&lt;TEntity&gt;](shippingmethodnotificationeventbase-1/) |  |
| class [ShippingMethodSavedNotification](shippingmethodsavednotification/) |  |
| class [ShippingMethodSavingNotification](shippingmethodsavingnotification/) |  |
| class [ShippingMethodUpdatedNotification](shippingmethodupdatednotification/) |  |
| class [ShippingMethodUpdatingNotification](shippingmethodupdatingnotification/) |  |
| class [StockChangedNotification](stockchangednotification/) |  |
| class [StockChangingNotification](stockchangingnotification/) |  |
| class [StoreCreatedNotification](storecreatednotification/) |  |
| class [StoreCreatingNotification](storecreatingnotification/) |  |
| class [StoreDeletedNotification](storedeletednotification/) |  |
| class [StoreDeletingNotification](storedeletingnotification/) |  |
| abstract class [StoreNotificationEventBase&lt;TEntity&gt;](storenotificationeventbase-1/) |  |
| class [StoreSavedNotification](storesavednotification/) |  |
| class [StoreSavingNotification](storesavingnotification/) |  |
| class [StoreUpdatedNotification](storeupdatednotification/) |  |
| class [StoreUpdatingNotification](storeupdatingnotification/) |  |
| class [TaxClassCreatedNotification](taxclasscreatednotification/) |  |
| class [TaxClassCreatingNotification](taxclasscreatingnotification/) |  |
| class [TaxClassDeletedNotification](taxclassdeletednotification/) |  |
| class [TaxClassDeletingNotification](taxclassdeletingnotification/) |  |
| abstract class [TaxClassNotificationEventBase&lt;TEntity&gt;](taxclassnotificationeventbase-1/) |  |
| class [TaxClassSavedNotification](taxclasssavednotification/) |  |
| class [TaxClassSavingNotification](taxclasssavingnotification/) |  |
| class [TaxClassUpdatedNotification](taxclassupdatednotification/) |  |
| class [TaxClassUpdatingNotification](taxclassupdatingnotification/) |  |

## Vendr.Core.Events.Notification.Handlers.Order namespace

| Public Type | Description |
| --- | --- |
| class [SendFinalizedOrderEmail](sendfinalizedorderemail/) |  |
| class [SendGiftCardEmails](sendgiftcardemails/) |  |

## Vendr.Core.Events.Validation namespace

| Public Type | Description |
| --- | --- |
| interface [IValidationEvent](ivalidationevent/) |  |
| class [ValidateCountryCodeChange](validatecountrycodechange/) |  |
| class [ValidateCountryCreate](validatecountrycreate/) |  |
| class [ValidateCountryDefaultCurrencyChange](validatecountrydefaultcurrencychange/) |  |
| class [ValidateCountryDefaultPaymentMethodChange](validatecountrydefaultpaymentmethodchange/) |  |
| class [ValidateCountryDefaultShippingMethodChange](validatecountrydefaultshippingmethodchange/) |  |
| class [ValidateCountryDelete](validatecountrydelete/) |  |
| class [ValidateCountryNameChange](validatecountrynamechange/) |  |
| class [ValidateCountrySave](validatecountrysave/) |  |
| class [ValidateCountryUpdate](validatecountryupdate/) |  |
| class [ValidateCurrencyAllowInCountry](validatecurrencyallowincountry/) |  |
| class [ValidateCurrencyCodeChange](validatecurrencycodechange/) |  |
| class [ValidateCurrencyCreate](validatecurrencycreate/) |  |
| class [ValidateCurrencyCultureChange](validatecurrencyculturechange/) |  |
| class [ValidateCurrencyCustomFormatTemplateChange](validatecurrencycustomformattemplatechange/) |  |
| class [ValidateCurrencyDelete](validatecurrencydelete/) |  |
| class [ValidateCurrencyDisallowInCountry](validatecurrencydisallowincountry/) |  |
| class [ValidateCurrencyNameChange](validatecurrencynamechange/) |  |
| class [ValidateCurrencySave](validatecurrencysave/) |  |
| class [ValidateCurrencyUpdate](validatecurrencyupdate/) |  |
| class [ValidateDiscountActiveChange](validatediscountactivechange/) |  |
| class [ValidateDiscountAliasChange](validatediscountaliaschange/) |  |
| class [ValidateDiscountCodeAdd](validatediscountcodeadd/) |  |
| class [ValidateDiscountCodeChange](validatediscountcodechange/) |  |
| class [ValidateDiscountCodeRemove](validatediscountcoderemove/) |  |
| class [ValidateDiscountCreate](validatediscountcreate/) |  |
| class [ValidateDiscountDateRangeChange](validatediscountdaterangechange/) |  |
| class [ValidateDiscountDelete](validatediscountdelete/) |  |
| class [ValidateDiscountNameChange](validatediscountnamechange/) |  |
| class [ValidateDiscountRewardsChange](validatediscountrewardschange/) |  |
| class [ValidateDiscountRulesChange](validatediscountruleschange/) |  |
| class [ValidateDiscountSave](validatediscountsave/) |  |
| class [ValidateDiscountTypeChange](validatediscounttypechange/) |  |
| class [ValidateDiscountUpdate](validatediscountupdate/) |  |
| class [ValidateEmailTemplateAliasChange](validateemailtemplatealiaschange/) |  |
| class [ValidateEmailTemplateBccAddressChange](validateemailtemplatebccaddresschange/) |  |
| class [ValidateEmailTemplateCategoryChange](validateemailtemplatecategorychange/) |  |
| class [ValidateEmailTemplateCcAddressChange](validateemailtemplateccaddresschange/) |  |
| class [ValidateEmailTemplateCreate](validateemailtemplatecreate/) |  |
| class [ValidateEmailTemplateDelete](validateemailtemplatedelete/) |  |
| class [ValidateEmailTemplateNameChange](validateemailtemplatenamechange/) |  |
| class [ValidateEmailTemplateSave](validateemailtemplatesave/) |  |
| class [ValidateEmailTemplateSenderChange](validateemailtemplatesenderchange/) |  |
| class [ValidateEmailTemplateSendToCustomerChange](validateemailtemplatesendtocustomerchange/) |  |
| class [ValidateEmailTemplateSubjectChange](validateemailtemplatesubjectchange/) |  |
| class [ValidateEmailTemplateToAddressChange](validateemailtemplatetoaddresschange/) |  |
| class [ValidateEmailTemplateUpdate](validateemailtemplateupdate/) |  |
| class [ValidateEmailTemplateViewChange](validateemailtemplateviewchange/) |  |
| class [ValidateGiftCardActiveChange](validategiftcardactivechange/) |  |
| class [ValidateGiftCardAmountsChange](validategiftcardamountschange/) |  |
| class [ValidateGiftCardCodeChange](validategiftcardcodechange/) |  |
| class [ValidateGiftCardCreate](validategiftcardcreate/) |  |
| class [ValidateGiftCardCurrencyChange](validategiftcardcurrencychange/) |  |
| class [ValidateGiftCardDelete](validategiftcarddelete/) |  |
| class [ValidateGiftCardExpiryDateChange](validategiftcardexpirydatechange/) |  |
| class [ValidateGiftCardOrderChange](validategiftcardorderchange/) |  |
| class [ValidateGiftCardPropertyChange](validategiftcardpropertychange/) |  |
| class [ValidateGiftCardSave](validategiftcardsave/) |  |
| class [ValidateGiftCardUpdate](validategiftcardupdate/) |  |
| class [ValidateOrderAssignToCustomer](validateorderassigntocustomer/) |  |
| class [ValidateOrderCodeEvent](validateordercodeevent/) |  |
| class [ValidateOrderCreate](validateordercreate/) |  |
| class [ValidateOrderCurrencyChange](validateordercurrencychange/) |  |
| class [ValidateOrderDelete](validateorderdelete/) |  |
| class [ValidateOrderDiscountCodeRedeem](validateorderdiscountcoderedeem/) |  |
| class [ValidateOrderDiscountCodeUnredeem](validateorderdiscountcodeunredeem/) |  |
| class [ValidateOrderFinalize](validateorderfinalize/) |  |
| class [ValidateOrderGiftCardRedeem](validateordergiftcardredeem/) |  |
| class [ValidateOrderGiftCardUnredeem](validateordergiftcardunredeem/) |  |
| class [ValidateOrderLanguageChange](validateorderlanguagechange/) |  |
| class [ValidateOrderLinePropertyChange](validateorderlinepropertychange/) |  |
| class [ValidateOrderLineQuantityChange](validateorderlinequantitychange/) |  |
| class [ValidateOrderLineRemove](validateorderlineremove/) |  |
| class [ValidateOrderPaymentCountryRegionChange](validateorderpaymentcountryregionchange/) |  |
| class [ValidateOrderPaymentMethodChange](validateorderpaymentmethodchange/) |  |
| class [ValidateOrderProductAdd](validateorderproductadd/) |  |
| class [ValidateOrderPropertyChange](validateorderpropertychange/) |  |
| class [ValidateOrderSave](validateordersave/) |  |
| class [ValidateOrderShippingCountryRegionChange](validateordershippingcountryregionchange/) |  |
| class [ValidateOrderShippingMethodChange](validateordershippingmethodchange/) |  |
| class [ValidateOrderStatusAliasChange](validateorderstatusaliaschange/) |  |
| class [ValidateOrderStatusChange](validateorderstatuschange/) |  |
| class [ValidateOrderStatusColorChange](validateorderstatuscolorchange/) |  |
| class [ValidateOrderStatusCreate](validateorderstatuscreate/) |  |
| class [ValidateOrderStatusDelete](validateorderstatusdelete/) |  |
| class [ValidateOrderStatusNameChange](validateorderstatusnamechange/) |  |
| class [ValidateOrderStatusSave](validateorderstatussave/) |  |
| class [ValidateOrderStatusUpdate](validateorderstatusupdate/) |  |
| class [ValidateOrderTaxClassChange](validateordertaxclasschange/) |  |
| class [ValidateOrderTransactionUpdate](validateordertransactionupdate/) |  |
| class [ValidateOrderUpdate](validateorderupdate/) |  |
| class [ValidatePaymentMethodAliasChange](validatepaymentmethodaliaschange/) |  |
| class [ValidatePaymentMethodAllowInCountryRegion](validatepaymentmethodallowincountryregion/) |  |
| class [ValidatePaymentMethodClearPrices](validatepaymentmethodclearprices/) |  |
| class [ValidatePaymentMethodCreate](validatepaymentmethodcreate/) |  |
| class [ValidatePaymentMethodDelete](validatepaymentmethoddelete/) |  |
| class [ValidatePaymentMethodDisallowInCountryRegion](validatepaymentmethoddisallowincountryregion/) |  |
| class [ValidatePaymentMethodImageChange](validatepaymentmethodimagechange/) |  |
| class [ValidatePaymentMethodNameChange](validatepaymentmethodnamechange/) |  |
| class [ValidatePaymentMethodPriceChange](validatepaymentmethodpricechange/) |  |
| class [ValidatePaymentMethodSave](validatepaymentmethodsave/) |  |
| class [ValidatePaymentMethodSettingChange](validatepaymentmethodsettingchange/) |  |
| class [ValidatePaymentMethodSkuChange](validatepaymentmethodskuchange/) |  |
| class [ValidatePaymentMethodTaxClassChange](validatepaymentmethodtaxclasschange/) |  |
| class [ValidatePaymentMethodToggleFeatures](validatepaymentmethodtogglefeatures/) |  |
| class [ValidatePaymentMethodUpdate](validatepaymentmethodupdate/) |  |
| class [ValidateProductAttributeAliasChange](validateproductattributealiaschange/) |  |
| class [ValidateProductAttributeCreate](validateproductattributecreate/) |  |
| class [ValidateProductAttributeDelete](validateproductattributedelete/) |  |
| class [ValidateProductAttributeNameChange](validateproductattributenamechange/) |  |
| class [ValidateProductAttributePresetAliasChange](validateproductattributepresetaliaschange/) |  |
| class [ValidateProductAttributePresetAllowAttribute](validateproductattributepresetallowattribute/) |  |
| class [ValidateProductAttributePresetCreate](validateproductattributepresetcreate/) |  |
| class [ValidateProductAttributePresetDelete](validateproductattributepresetdelete/) |  |
| class [ValidateProductAttributePresetDescriptionChange](validateproductattributepresetdescriptionchange/) |  |
| class [ValidateProductAttributePresetDisallowAttribute](validateproductattributepresetdisallowattribute/) |  |
| class [ValidateProductAttributePresetIconChange](validateproductattributepreseticonchange/) |  |
| class [ValidateProductAttributePresetNameChange](validateproductattributepresetnamechange/) |  |
| class [ValidateProductAttributePresetSave](validateproductattributepresetsave/) |  |
| class [ValidateProductAttributePresetUpdate](validateproductattributepresetupdate/) |  |
| class [ValidateProductAttributeSave](validateproductattributesave/) |  |
| class [ValidateProductAttributeUpdate](validateproductattributeupdate/) |  |
| class [ValidateProductAttributeValueAdd](validateproductattributevalueadd/) |  |
| class [ValidateProductAttributeValueNameChange](validateproductattributevaluenamechange/) |  |
| class [ValidateProductAttributeValueRemove](validateproductattributevalueremove/) |  |
| class [ValidateRegionCodeChange](validateregioncodechange/) |  |
| class [ValidateRegionCreate](validateregioncreate/) |  |
| class [ValidateRegionDefaultPaymentMethodChange](validateregiondefaultpaymentmethodchange/) |  |
| class [ValidateRegionDefaultShippingMethodChange](validateregiondefaultshippingmethodchange/) |  |
| class [ValidateRegionDelete](validateregiondelete/) |  |
| class [ValidateRegionNameChange](validateregionnamechange/) |  |
| class [ValidateRegionSave](validateregionsave/) |  |
| class [ValidateRegionUpdate](validateregionupdate/) |  |
| class [ValidateShippingMethodAliasChange](validateshippingmethodaliaschange/) |  |
| class [ValidateShippingMethodAllowInCountryRegion](validateshippingmethodallowincountryregion/) |  |
| class [ValidateShippingMethodClearPrices](validateshippingmethodclearprices/) |  |
| class [ValidateShippingMethodCreate](validateshippingmethodcreate/) |  |
| class [ValidateShippingMethodDelete](validateshippingmethoddelete/) |  |
| class [ValidateShippingMethodDisallowInCountryRegion](validateshippingmethoddisallowincountryregion/) |  |
| class [ValidateShippingMethodImageChange](validateshippingmethodimagechange/) |  |
| class [ValidateShippingMethodNameChange](validateshippingmethodnamechange/) |  |
| class [ValidateShippingMethodPriceChange](validateshippingmethodpricechange/) |  |
| class [ValidateShippingMethodSave](validateshippingmethodsave/) |  |
| class [ValidateShippingMethodSkuChange](validateshippingmethodskuchange/) |  |
| class [ValidateShippingMethodTaxClassChange](validateshippingmethodtaxclasschange/) |  |
| class [ValidateShippingMethodUpdate](validateshippingmethodupdate/) |  |
| class [ValidateStockChange](validatestockchange/) |  |
| class [ValidateStoreAddGiftCardPropertyAlias](validatestoreaddgiftcardpropertyalias/) |  |
| class [ValidateStoreAddProductPropertyAlias](validatestoreaddproductpropertyalias/) |  |
| class [ValidateStoreAddProductUniquenessPropertyAlias](validatestoreaddproductuniquenesspropertyalias/) |  |
| class [ValidateStoreAliasChange](validatestorealiaschange/) |  |
| class [ValidateStoreAllowUser](validatestoreallowuser/) |  |
| class [ValidateStoreAllowUserRole](validatestoreallowuserrole/) |  |
| class [ValidateStoreBaseCurrencyChange](validatestorebasecurrencychange/) |  |
| class [ValidateStoreCookiesChange](validatestorecookieschange/) |  |
| class [ValidateStoreCreate](validatestorecreate/) |  |
| class [ValidateStoreDefaultCountryChange](validatestoredefaultcountrychange/) |  |
| class [ValidateStoreDefaultTaxClassChange](validatestoredefaulttaxclasschange/) |  |
| class [ValidateStoreDelete](validatestoredelete/) |  |
| class [ValidateStoreDisallowUser](validatestoredisallowuser/) |  |
| class [ValidateStoreDisallowUserRole](validatestoredisallowuserrole/) |  |
| class [ValidateStoreGiftCardSettingsChange](validatestoregiftcardsettingschange/) |  |
| class [ValidateStoreNameChange](validatestorenamechange/) |  |
| class [ValidateStoreNotificationEmailTemplatesChange](validatestorenotificationemailtemplateschange/) |  |
| class [ValidateStoreOrderEditorConfigChange](validatestoreordereditorconfigchange/) |  |
| class [ValidateStoreOrderNumberTemplatesChange](validatestoreordernumbertemplateschange/) |  |
| class [ValidateStoreOrderStatusesChange](validatestoreorderstatuseschange/) |  |
| class [ValidateStorePriceTaxInclusivityChange](validatestorepricetaxinclusivitychange/) |  |
| class [ValidateStoreRemoveGiftCardPropertyAlias](validatestoreremovegiftcardpropertyalias/) |  |
| class [ValidateStoreRemoveProductPropertyAlias](validatestoreremoveproductpropertyalias/) |  |
| class [ValidateStoreRemoveProductUniquenessPropertyAlias](validatestoreremoveproductuniquenesspropertyalias/) |  |
| class [ValidateStoreSave](validatestoresave/) |  |
| class [ValidateStoreShareStockFromStoreChange](validatestoresharestockfromstorechange/) |  |
| class [ValidateStoreUpdate](validatestoreupdate/) |  |
| class [ValidateTaxClassAliasChange](validatetaxclassaliaschange/) |  |
| class [ValidateTaxClassClearTaxRates](validatetaxclasscleartaxrates/) |  |
| class [ValidateTaxClassCreate](validatetaxclasscreate/) |  |
| class [ValidateTaxClassDelete](validatetaxclassdelete/) |  |
| class [ValidateTaxClassNameChange](validatetaxclassnamechange/) |  |
| class [ValidateTaxClassSave](validatetaxclasssave/) |  |
| class [ValidateTaxClassTaxRateChange](validatetaxclasstaxratechange/) |  |
| class [ValidateTaxClassUpdate](validatetaxclassupdate/) |  |
| abstract class [ValidationEventBase](validationeventbase/) |  |
| abstract class [ValidationEventHandlerBase&lt;TValidationEvent&gt;](validationeventhandlerbase-1/) |  |

## Vendr.Core.Events.Validation.Handlers.Country namespace

| Public Type | Description |
| --- | --- |
| class [ValidateCountryCodeFormat](validatecountrycodeformat/) |  |
| class [ValidateDefaultCurrencyBelongsToCountryStore](validatedefaultcurrencybelongstocountrystore/) |  |
| class [ValidateDefaultPaymentMethodBelongsToCountryStore](validatedefaultpaymentmethodbelongstocountrystore/) |  |
| class [ValidateDefaultShippingMethodBelongsToCountryStore](validatedefaultshippingmethodbelongstocountrystore/) |  |
| class [ValidateNotStoreDefaultCountry](validatenotstoredefaultcountry/) |  |
| class [ValidateUniqueCountryCode](validateuniquecountrycode/) |  |

## Vendr.Core.Events.Validation.Handlers.Currency namespace

| Public Type | Description |
| --- | --- |
| class [ValidateAllowedCountryBelongsToCurrencyStore](validateallowedcountrybelongstocurrencystore/) |  |
| class [ValidateCulture](validateculture/) |  |
| class [ValidateCurrencyCodeFormat](validatecurrencycodeformat/) |  |
| class [ValidateLicenseMaxCurrencies](validatelicensemaxcurrencies/) |  |
| class [ValidateNotCountryDefaultCurrency](validatenotcountrydefaultcurrency/) |  |
| class [ValidateNotStoreBaseCurrency](validatenotstorebasecurrency/) |  |
| class [ValidateUniqueCurrencyCode](validateuniquecurrencycode/) |  |

## Vendr.Core.Events.Validation.Handlers.Discount namespace

| Public Type | Description |
| --- | --- |
| class [ValidateLicenseMaxActiveDiscounts](validatelicensemaxactivediscounts/) |  |
| class [ValidateLicenseMaxDiscounts](validatelicensemaxdiscounts/) |  |
| class [ValidateUniqueAlias](validateuniquealias/) |  |
| class [ValidateUniqueDiscountCode](validateuniquediscountcode/) |  |

## Vendr.Core.Events.Validation.Handlers.EmailTemplate namespace

| Public Type | Description |
| --- | --- |
| class [ValidateNotStoreDefaultEmailTemplate](validatenotstoredefaultemailtemplate/) |  |
| class [ValidateUniqueEmailTemplateAlias](validateuniqueemailtemplatealias/) |  |

## Vendr.Core.Events.Validation.Handlers.GiftCard namespace

| Public Type | Description |
| --- | --- |
| class [ValidateLicenseMaxActiveGiftCards](validatelicensemaxactivegiftcards/) |  |
| class [ValidateLicenseMaxGiftCards](validatelicensemaxgiftcards/) |  |
| class [ValidateUniqueGiftCardCode](validateuniquegiftcardcode/) |  |

## Vendr.Core.Events.Validation.Handlers.Order namespace

| Public Type | Description |
| --- | --- |
| class [ValidateCurrencyBelongsToOrderStore](validatecurrencybelongstoorderstore/) |  |
| class [ValidateDiscountCodeValid](validatediscountcodevalid/) |  |
| class [ValidateGiftCardValid](validategiftcardvalid/) |  |
| class [ValidateLicenseMaxOrders](validatelicensemaxorders/) |  |
| class [ValidateLicenseSupportsCustomProductAdapter](validatelicensesupportscustomproductadapter/) |  |
| class [ValidateOrderPaymentCountryRegionAllowedByOrderCurrency](validateorderpaymentcountryregionallowedbyordercurrency/) |  |
| class [ValidateOrderPaymentCountryRegionBelongsToOrderStore](validateorderpaymentcountryregionbelongstoorderstore/) |  |
| class [ValidateOrderShippingCountryRegionBelongsToOrderStore](validateordershippingcountryregionbelongstoorderstore/) |  |
| class [ValidateOrderStatusBelongsToOrderStore](validateorderstatusbelongstoorderstore/) |  |
| class [ValidateOrderStatusCode](validateorderstatuscode/) |  |
| class [ValidatePaymentMethodAllowedInPaymentCountryRegion](validatepaymentmethodallowedinpaymentcountryregion/) |  |
| class [ValidatePaymentMethodBelongsToOrderStore](validatepaymentmethodbelongstoorderstore/) |  |
| class [ValidateProductAddHasPrice](validateproductaddhasprice/) |  |
| class [ValidateProductAddQuantityPositive](validateproductaddquantitypositive/) |  |
| class [ValidateShippingMethodAllowedInShippingCountryRegion](validateshippingmethodallowedinshippingcountryregion/) |  |
| class [ValidateShippingMethodBelongsToOrderStore](validateshippingmethodbelongstoorderstore/) |  |
| class [ValidateTaxClassBelongsToOrderStore](validatetaxclassbelongstoorderstore/) |  |
| class [ValidateTransactionInitialized](validatetransactioninitialized/) |  |
| class [ValidateUniqueBundleId](validateuniquebundleid/) |  |

## Vendr.Core.Events.Validation.Handlers.OrderStatus namespace

| Public Type | Description |
| --- | --- |
| class [ValidateNotStoreDefaultOrderStatus](validatenotstoredefaultorderstatus/) |  |

## Vendr.Core.Events.Validation.Handlers.PaymentMethod namespace

| Public Type | Description |
| --- | --- |
| class [ValidateAllowedInPriceCountryRegion](validateallowedinpricecountryregion/) |  |
| class [ValidateLicenseMaxPaymentMethods](validatelicensemaxpaymentmethods/) |  |
| class [ValidateNotCountryDefaultPaymentMethod](validatenotcountrydefaultpaymentmethod/) |  |
| class [ValidateNotRegionDefaultPaymentMethod](validatenotregiondefaultpaymentmethod/) |  |
| class [ValidateUniquePaymentMethodAlias](validateuniquepaymentmethodalias/) |  |

## Vendr.Core.Events.Validation.Handlers.Region namespace

| Public Type | Description |
| --- | --- |
| class [ValidateDefaultPaymentMethodBelongsToRegionStore](validatedefaultpaymentmethodbelongstoregionstore/) |  |
| class [ValidateDefaultShippingMethodBelongsToRegionStore](validatedefaultshippingmethodbelongstoregionstore/) |  |
| class [ValidateUniqueRegionCode](validateuniqueregioncode/) |  |

## Vendr.Core.Events.Validation.Handlers.ShippingMethod namespace

| Public Type | Description |
| --- | --- |
| class [ValidateAllowedInPriceCountryRegion](validateallowedinpricecountryregion/) |  |
| class [ValidateNotCountryDefaultShippingMethod](validatenotcountrydefaultshippingmethod/) |  |
| class [ValidateNotRegionDefaultShippingMethod](validatenotregiondefaultshippingmethod/) |  |
| class [ValidateUniqueShippingMethodAlias](validateuniqueshippingmethodalias/) |  |

## Vendr.Core.Events.Validation.Handlers.Store namespace

| Public Type | Description |
| --- | --- |
| class [ValidateDefaultCountryBelongsToStore](validatedefaultcountrybelongstostore/) |  |
| class [ValidateDefaultTaxClassBelongsToStore](validatedefaulttaxclassbelongstostore/) |  |
| class [ValidateLicenseMaxStores](validatelicensemaxstores/) |  |
| class [ValidateLicenseMaxUsers](validatelicensemaxusers/) |  |
| class [ValidateLicenseStoreUserGroupPermissions](validatelicensestoreusergrouppermissions/) |  |
| class [ValidateNotificationEmailTemplatesBelongsToStore](validatenotificationemailtemplatesbelongstostore/) |  |
| class [ValidateOrderStatusesBelongsToStore](validateorderstatusesbelongstostore/) |  |
| class [ValidateUniqueStoreAlias](validateuniquestorealias/) |  |

## Vendr.Core.Events.Validation.Handlers.TaxClass namespace

| Public Type | Description |
| --- | --- |
| class [ValidateNotStoreDefaultTaxClass](validatenotstoredefaulttaxclass/) |  |
| class [ValidateUniqueTaxClassAlias](validateuniquetaxclassalias/) |  |

<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
