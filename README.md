
# DzMC
Download mods for a Minecraft server, with three goals:
-   Create Mod
-   Good optimisation so the game runs better (with Fabric API)
-   Expanded world for exploration

I'm open to suggestions about adding new mods, but want to restrict the number of mods especially those which add significant gameplay features which can trivialise other parts of the game. The primary gameplay mod should be create.

## Downloads
 - All Mods
Or..
 - Required Mods
 - Optional Mods


## Setup Minecraft
**⚠️The server is running v1.20.1** 
This is slightly out of date but ensures better mod compatibility.

**Fabric API**
The server is setup to use the Fabric API. This is a modding platform, you will need to install Fabric onto your PC (specifically, your minecraft directory) in order to connect to the server.
[https://fabricmc.net/use/installer/](https://fabricmc.net/use/installer/ "https://fabricmc.net/use/installer/")
The installer will add a new profile to your minecraft launcher so that you can easily switch between this modded version and the vanilla/latest version.

## Required Mods
These mods are used by the server and must exist on your PC too, otherwise you won't be able to connect
* [**Cloth Config**](https://modrinth.com/mod/cloth-config), [**Fabric API**](https://modrinth.com/mod/fabric-api), [**ModMenu**](*https://modrinth.com/plugin/dcintegration/) *(Other)*
Libraries and stuff for mod management. These may be required by other mods and have little/no overhead so best to install them.
* **Yungs** - [**Better End**](*?), [**Better Mineshafts**](*?), [**Better Nether Fortresses**](*?), [**Better Ocean Monuments**](*?), [**Better Strongholds**](*?), [**Better Desert Temples**](*?), [**Better Dungeons**](*?), [**YungAPI**](*?) *(World enhancement)*
This collection of mods basically improves all of the generated structures in the world that has mobs in them. It adds complexity and difficulty to make exploring and adventuring much more fun.
* [**FerriteCore**](https://modrinth.com/mod/ferrite-core),  [**ImmediatelyFast**](https://modrinth.com/mod/immediatelyfast),   [**Lithium**](https://modrinth.com/mod/lithium), [**Clumps**](https://modrinth.com/mod/clumps)  
Optimisation mods that make things run faster/smoother. These might be optional? But the server runs them so YMMV, they're bring massive FPS improvements so worth it.

* [**Just Enough Items (JEI)**](https://modrinth.com/mod/jei) *(UI/Ux Improvement)*
Shows you all the items/recipes, basically required for create.


## Optional Mods (Client Side)
These mods should work completely optionally, they will be present on the server (so any additional features they provide will work) but you can turn them off if you don't like them.

* [**Xaero's World Map**](https://modrinth.com/mod/xaeros-world-map) 
Adds a map of all the places you've explored. It wont show the entire server you have to go explore! 

* [**Jade**](https://modrinth.com/mod/jade) *(UI/Ux Improvement)*
"What am I looking at" mod - adds information to the hud describing the block you are looking at. Can be really helpful for new players or when trying to diagnose complex CreateMod machines.

* [**Mouse Tweaks**](https://modrinth.com/mod/mouse-tweaks) *(UI/Ux Improvement)*
Improves certain parts of the UI, mostly around inventory management.

* [**Distant Horizons**](https://modrinth.com/mod/distanthorizons) *(Game Experience)*
A very clever mod that adds 'level of detail' rendering, allowing you to set MASSIVE render distances.
*⚠️ Warning: this mod creates low-poly chunks of the world and saves to your minecraft folder. It is computationally expensive and uses quite a lot of hard disk space. If your computer/minecraft app is running slow or you're running out of disk space, remove this mod!*

* [**Better Animations Collection**](https://modrinth.com/mod/better-animations-collection) *(Game Experience)*
Improves on the default animations, really improves how modern the game feels.

* [**Shulker Box Tooltip**](*https://modrinth.com/plugin/dcintegration/) *(UI/Ux Improvement)*
Massive improvement for shulker box inventory management

*  [**Sodium**](https://modrinth.com/mod/sodium),   [**Indium**](https://modrinth.com/mod/indium),   [**Iris**](https://modrinth.com/mod/iris),    [**Starlight**](https://modrinth.com/mod/starlight) 
Rendering mods that make the game run faster/better. Iris is a shader manager compatible with Optifine, that lets you add shaders to make the game look prettier on Fabric.

# Server
[**Discord Integration**](*https://modrinth.com/plugin/dcintegration/) *(Server)*
In-game chat integrated with Discord!
