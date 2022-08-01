# NameplateStats
A VRChat [MelonLoader](https://github.com/LavaGang/MelonLoader) which aims to add statisics ontop of players nameplates!

## Features
* Enable/Disable nameplate stats
* Display players Ping/FPS above users nameplates
* Dynamic Colouring of the stats text (green = good, yellow = ok, red = bad)
  * Dynamic Colouring blends the colour based on the distance between stages
  * You can also change the colour scaling slightly (GoodFPS = max green, BadPing = max red)
* Static colouring of the stats text (RGB)
* Ability to change the update timer for NameplateStats (50ms-30000ms)

## Compatability
* Currently working on quest beta(maybe latest?)
* This mod was made for Melonloader 0.4.1
* Basic colour changing compatability with [BTKSANameplateFix](https://github.com/ddakebono/BTKSANameplateFix/)

 ## Installation
 https://gist.github.com/iryis/2b8cf54262a98b8c01ae0510a3f36b12

## Building
To build this mod, reference the following libraries from MelonLoader/Managed after assembly generation;
* Assembly-CSharp.dll
* Il2Cppmscorlib.dll
* UnhollowerBaseLib.dll
* UnhollowerRuntimeLib.dll
* UnityEngine.dll
* UnityEngine.CoreModule.dll
* UnityEngine.UI.dll
* Unity.TextMeshPro
* VRCCore-Standalone.dll

Additionally, reference the following library;
* MelonLoader.dll (from MelonLoader base directory)

Finally, build in your favourite IDE.

## Credits
* [Dawn](https://github.com/Arion-Kun) - Optimization, Moral support, general guidance, qt
* [DDAkebono](https://github.com/ddakebono) - Heavily referenced the code from [BTSKANameplateFix](https://github.com/ddakebono/BTKSANameplateFix)
* [loukylor](https://github.com/loukylor/) - Used [PlayerList](https://github.com/loukylor/VRC-Mods/tree/main/PlayerList)'s code to get ping/fps safely and learn about MelonUtils.Clamp
