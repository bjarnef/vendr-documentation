---
title: PrintTemplateMapper
description: API reference for PrintTemplateMapper in Vendr, the eCommerce solution for Umbraco v8+
---
## PrintTemplateMapper

```csharp
public static class PrintTemplateMapper
```

**Namespace**
* [Vendr.Web.Models.Mappers](../)

### Methods

#### PrintTemplateEntitiesToBasicDtos

```csharp
public static IEnumerable<PrintTemplateBasicDto> PrintTemplateEntitiesToBasicDtos(
    IEnumerable<PrintTemplateReadOnly> entities)
```


---

#### PrintTemplateEntityToBasicDto

```csharp
public static PrintTemplateBasicDto PrintTemplateEntityToBasicDto(PrintTemplateReadOnly entity, 
    PrintTemplateBasicDto dto = null)
```


---

#### PrintTemplateEntityToEditDto

```csharp
public static PrintTemplateEditDto PrintTemplateEntityToEditDto(PrintTemplateReadOnly entity, 
    PrintTemplateEditDto dto = null)
```


---

#### PrintTemplateSaveDtoToEntity

```csharp
public static PrintTemplate PrintTemplateSaveDtoToEntity(PrintTemplateSaveDto dto, 
    PrintTemplate entity)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Web.dll -->
