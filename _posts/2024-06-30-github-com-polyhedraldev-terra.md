---
title: Terra
categories: ['java', 'minecraft', 'papermc']
---
## [Terra](https://github.com/PolyhedralDev/Terra)

### Voxel world generation modding platform


Terra is a modern world generation modding platform, primarily for Minecraft.
Terra allows complete customization of world generation with an advanced API,
tightly integrated with a powerful configuration system.

Terra consists of several parts:

* A voxel world generation API with emphasis on configuration and extensibility
* Several platform implementations, the layer between the API and the platform
  it's running on.
* An addon loader, which allows addons to interface with the Terra API in a
  platform-agnostic setting
* Several "core addons," which implement the "default" configurations of Terra.
  These addons can be thought of as the config "standard library"

Terra currently officially supports the Fabric mod loader and the Bukkit API
(Paper and friends). We welcome Pull Requests implementing additional platforms!
