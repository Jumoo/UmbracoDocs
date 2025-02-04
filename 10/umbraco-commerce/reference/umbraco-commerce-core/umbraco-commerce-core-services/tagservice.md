---
title: TagService
description: API reference for TagService in Umbraco Commerce
---
## TagService

```csharp
public class TagService : ServiceBase<TagService>, ITagService
```

**Inheritance**

* class [ServiceBase&lt;TSelf&gt;](servicebase-1.md)
* interface [ITagService](itagservice.md)

**Namespace**
* [Umbraco.Commerce.Core.Services](README.md)

### Constructors

#### TagService

```csharp
public TagService(IRepositoryFactory repositoryFactory, IUnitOfWorkProvider uowProvider, 
    ILogger<TagService> logger, ICacheAccessor cacheAccessor)
```


### Methods

#### GetEntityTags

```csharp
public IEnumerable<string> GetEntityTags(Guid storeId, Guid entityId, string startsWith = null)
```


---

#### GetTags

```csharp
public IEnumerable<string> GetTags(Guid storeId, string startsWith = null)
```


---

#### GetTagsByEntityType

```csharp
public IEnumerable<string> GetTagsByEntityType(Guid storeId, string entityType, 
    string startsWith = null)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
