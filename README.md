# ZoomButtonPatch

A client-side C# submod for **Vintage Story** that automatically hides custom third-party mod GUIs and overlay HUDs when zooming with **Zoom Button - Reborn**.

---

## Features

* **Purely Client-Side:** Installs purely on the client side; no server installation needed.
* **Automatic Mod Detection:** Hooks into third-party `GuiDialog` windows and `IRenderer` HUD overlays across installed mods without requiring manual configuration.
* **No Hard Dependencies:** Reads zoom state directly from `capi.ObjectCache`, ensuring the mod won't crash if ZoomButton is updated, missing, or renamed.
* **Fast Startup:** Filters out engine and system assemblies during initialization to minimize load times and avoid rendering overhead.

---


### How To Use
- [see mod page](https://mods.vintagestory.at/show/mod/60829)
---

## Contribution & Development

Want to contribute code or compile this mod locally? Please review the central [Contributing Guidelines](https://github.com/Furio-s-Mods/.github/blob/main/CONTRIBUTING.md) for environment setup and path management instructions.

## Acknowledgements
* **[Anego Studios](https://anegostudios.com)** - Vintage Story Devs
* **Goxmeor** - Original mod author
* **SpearAndFang** - Official mod maintainer


## License

This project is licensed under the [MIT License](LICENSE).

---
