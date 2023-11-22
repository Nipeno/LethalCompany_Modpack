# LC-API
The definitive Lethal Company modding API. Includes some very useful features to make modding life easier.

# For Developers
If you want to use the API in your plugin, add the LC_API.dll as a project reference!

# Features
AssetBundle loading - Put asset bundles in BepInEx > Bundles and load them using BundleAPI.BundleLoader.GetLoadedAsset

ServerAPI - Utilities relating to the network and server. This includes:

ModdedServer - Automatically alerts other users when you host a server that your server is modded. 
It also lets mod authors make their mods put users in special matchmaking where they can only play with other modded users

Networking - Easily send data across the network to sync data between clients effortlessly

# Releases

# Version 1.0.0
- Release

# Version 1.1.0
- General bug fixes for Networking

- The local player now will NOT receive data that they broadcast. The bool value on the receive delegates is also gone. If you were using Networking, you will need to ajust your code.

# Version 1.1.1
- General bug fixes for Networking

- Plugin developers NEED to update to this version as it includes a fix for a bug that prevented Networking from being used.

# Version 1.2.0
- Added new GameInterfaceAPI. Documentation will be created soon.

- Added new CheatDatabase with the purpose of catching users trying to join non-modded servers with cheaty mods. The CheatDatabase also allows for the host to view all mods installed by people joining. (As long as they have LC_API installed).

# Version 1.2.1
- Adjusted README formatting.




