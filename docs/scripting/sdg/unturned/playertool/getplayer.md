# SDG.Unturned.PlayerTool.getPlayer

<blockquote><p><b>This page is incomplete, please help finish it by contributing.<p></b></blockquote>

> Every member is client and server compatible.

## Overloads:

Name | Description
------------ | -------------
[getPlayer(CSteamID)](scripting/sdg/unturned/playertool/getplayer?id=sdgunturnedplayertoolgetplayercsteamid) | Finds a player using their [CSteamID](scripting/steamworks/csteamid)
[getPlayer(string)](scripting/sdg/unturned/playertool/getplayer?id=sdgunturnedplayertoolgetplayerstring) | Finds a player using their name

----

## SDG.Unturned.PlayerTool.getPlayer(CSteamID)

Gets a player using their [CSteamID](scripting/steamworks/csteamid).

This call is valid on both the client and server.

```csharp
public static Player getPlayer(CSteamID steamID);
```

### Returns:

Type | Description
------------ | -------------
[Player](scripting/sdg/unturned/player) | The player object returned; if no player was found, this will return `null`

### Parameters:

Type | Name | Description
------------ | ------------- | -------------
[CSteamID](scripting/steamworks/csteamid) | steamID | The id of the player you would like to find

----

## SDG.Unturned.PlayerTool.getPlayer(string)

Gets a player using their name.

This call is valid on both the client and server.

```csharp
public static Player getPlayer(string name);
```

### Returns:

Type | Description
------------ | -------------
[Player](scripting/sdg/unturned/player) | The player object returned; if no player was found, this will return `null`

### Parameters:

Type | Name | Description
------------ | ------------- | -------------
[string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-3.5) | name | The name of the player you would like to find