---
title: ExportTemplateMapper
description: API reference for ExportTemplateMapper in Vendr, the eCommerce solution for Umbraco v8+
---
## ExportTemplateMapper

```csharp
public static class ExportTemplateMapper
```

**Namespace**
* [Vendr.Web.Models.Mappers](../)

### Methods

#### ExportTemplateEntitiesToBasicDtos

```csharp
public static IEnumerable<ExportTemplateBasicDto> ExportTemplateEntitiesToBasicDtos(
    IEnumerable<ExportTemplateReadOnly> entities)
```


---

#### ExportTemplateEntityToBasicDto

```csharp
public static ExportTemplateBasicDto ExportTemplateEntityToBasicDto(ExportTemplateReadOnly entity, 
    ExportTemplateBasicDto dto = null)
```


---

#### ExportTemplateEntityToEditDto

```csharp
public static ExportTemplateEditDto ExportTemplateEntityToEditDto(ExportTemplateReadOnly entity, 
    ExportTemplateEditDto dto = null)
```


---

#### ExportTemplateSaveDtoToEntity

```csharp
public static ExportTemplate ExportTemplateSaveDtoToEntity(ExportTemplateSaveDto dto, 
    ExportTemplate entity)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->
