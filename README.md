<p align="center">
  <img height="400px" style="margin: 0; padding: 0" src=".moonwave\static\logo.png" />
</p>


# Loadstring

```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/luau/UniversalSynSaveInstance/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance
synsaveinstance(Options)
```



## Disclaimer

This project is provided for development, debugging, archival, and research purposes within the Roblox platform.

It is not intended for misuse, including violating platform rules, unauthorized access, or redistribution of content without permission.

Users are responsible for ensuring their usage complies with all applicable rules, including Roblox’s Terms of Use.

The maintainers do not support or condone misuse of this software and are not responsible for how it is used.

> [!TIP]
> Important part about this saveinstance is that it doesn't modify game state, which helps maintain stability and compatibility.<br />
> You can also enable the `SafeMode` option to improve compatibility and ensure more reliable saving across a wide range of experiences.<br /><br /> You can read more about it here [Documentation]
> If this script is helpful to you, please click `⭐ Star` in the upper right corner of the page to support it, thank you!

