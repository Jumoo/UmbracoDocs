---
title: ValidateStoreNameChange
description: API reference for ValidateStoreNameChange in Umbraco Commerce
---
## ValidateStoreNameChange

```csharp
public class ValidateStoreNameChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateStoreNameChange

```csharp
public ValidateStoreNameChange(StoreReadOnly store, ChangingValue<string> name)
```


### Properties

#### Name

```csharp
public ChangingValue<string> Name { get; }
```


---

#### Store

```csharp
public StoreReadOnly Store { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
