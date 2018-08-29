# IChannelApi.GetChannelIdList method (1 of 2)

通过站点Id获取此站点下的所有栏目Id的列表。

```csharp
public List<int> GetChannelIdList(int siteId)
```

| parameter | description |
| --- | --- |
| siteId | 站点Id。 |

## Return Value

如果站点存在，则返回此站点的所有栏目的Id列表；否则返回 null。

## See Also

* interface [IChannelApi](sdk/IChannelApi.md)
* namespace [SiteServer.Plugin](sdk/README.md)

---

# IChannelApi.GetChannelIdList method (2 of 2)

通过站点Id以及父栏目Id获取父栏目下的栏目Id的列表。

```csharp
public List<int> GetChannelIdList(int siteId, int parentId)
```

| parameter | description |
| --- | --- |
| siteId | 站点Id。 |
| parentId | 父栏目Id |

## Return Value

如果站点及父栏目存在，则返回父栏目下的栏目的Id列表；否则返回 null。

## See Also

* interface [IChannelApi](sdk/IChannelApi.md)
* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->