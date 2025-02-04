---
title: UmbracoCommerceTaxController
description: API reference for UmbracoCommerceTaxController in Umbraco Commerce
---
## UmbracoCommerceTaxController

```csharp
public class UmbracoCommerceTaxController : UmbracoCommerceAuthorizedJsonControllerBase
```

**Inheritance**

* class [UmbracoCommerceAuthorizedJsonControllerBase](umbracocommerceauthorizedjsoncontrollerbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Web.Controllers](README.md)

### Constructors

#### UmbracoCommerceTaxController

```csharp
public UmbracoCommerceTaxController(IBackOfficeSecurityAccessor backOfficeSecurityAccesor, 
    UmbracoCommerceContext ctx)
```


### Methods

#### CreateTaxClass

```csharp
public IActionResult CreateTaxClass(Guid storeId)
```


---

#### DeleteTaxClass

```csharp
public IActionResult DeleteTaxClass(Guid taxClassId)
```


---

#### GetTaxClass

```csharp
public IActionResult GetTaxClass(Guid taxClassId)
```


---

#### GetTaxClasses

```csharp
public IActionResult GetTaxClasses(Guid storeId)
```


---

#### SaveTaxClass

```csharp
public IActionResult SaveTaxClass(TaxClassSaveDto taxClass)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
