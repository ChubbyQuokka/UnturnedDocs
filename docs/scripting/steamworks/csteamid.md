# Steamworks.CSteamID

The interop structure for the native representation of a Steam64ID;

```C#
[Serializable, StructLayout(LayoutKind.Sequential, Pack = 4)]
public struct CSteamID : IEquatable<CSteamID>, IComparable<CSteamID>
```

### Fields:

Name | Description
------------ | -------------
[m_SteamID](scripting/steamworks/csteamid/m_steamid) | The [ulong](https://docs.microsoft.com/en-us/dotnet/api/system.uint64?view=netframework-3.5) representation of an ID.