# WinUI 3 SystemBackdrops API Samples

This repository contains samples on how to use the new [WinUI 3]("https://github.com/microsoft/microsoft-ui-xaml") 1.1 Preview 3 SystemBackdrops API.

## Materials

As documented in the Design in Windows 11 [Materials](https://docs.microsoft.com/en-us/windows/apps/design/signature-experiences/materials) documentation, Materials are visual effects applied to UX surfaces that resemble real life artifacts.

The SystemBackdrops API was introduced in the [WinUI 3.0 1.0 Preview 3](https://docs.microsoft.com/en-us/windows/apps/windows-app-sdk/preview-channel#version-11-preview-3-110-preview3) release.

SystemBackdrops are used to provide a consistent visual appearance across the entire app.

### Acrylic

![Acrylic](https://docs.microsoft.com/en-us/windows/apps/design/signature-experiences/images/materials_acrylic_hero_1880.png)

Acrylic is a semi-transparent material that replicates the effect of frosted glass. In Windows 11, acrylic has been updated to be brighter and more translucent, allowing for a stronger contextual relationship with the visuals behind it. Acrylic is used only for transient, light-dismiss surfaces such as flyouts and context menus.

Acrylic is mode aware; it supports both light and dark mode.

### Mica

![Mica](https://docs.microsoft.com/en-us/windows/apps/design/signature-experiences/images/materials_mica_hero_1880.png)

Mica is a new opaque material introduced in Windows 11. Mica surfaces are subtly tinted with the user's desktop background color.

Mica is mode aware; it supports both light and dark modes. Mica also indicates window focus with active and inactive states as a built in feature.

## References

- [WinUI 3](https://github.com/microsoft/microsoft-ui-xaml)
- [Windows App SDK](https://github.com/microsoft/WindowsAppSDK)
- [SystemBackdrops Code Samples](https://github.com/microsoft/WinUI-Gallery/tree/winui3/XamlControlsGallery/ControlPagesSampleCode/SystemBackdrops)
- [Materials in Windows 11](https://docs.microsoft.com/en-us/windows/apps/design/signature-experiences/materials)