---
title: "Unity Developer Guide"
description: "Set up the Unity development environment for Zelda Twilight Princess Remastered"
weight: 2
---

This guide will walk you through setting up the **Unity** development environment to build and run the *Zelda Twilight Princess Remastered* project.

> ⚠️ **Important:** You can only build and run the project if you have legally acquired and imported the required assets listed below.

## Prerequisites

- Unity Editor (Version 2022.3 LTS or newer recommended)
- Git installed
- Basic knowledge of Unity and C#
- The required commercial assets (see below)

## 1. Clone the Repository

Clone the project using Git:

```bash
git clone https://github.com/F1mmel/ZeldaTwilightPrincessRemastered.git
```

## 2. Install Unity

Download and install [Unity Hub](https://unity.com/download) and then install **Unity 2022.3 LTS** or a compatible version used in the project.

> The Unity project was built using 2022.3.x, using the **URP Render Pipeline**.

## 3. Open the Project

1. Open Unity Hub
2. Click `Open project` and navigate to the downloaded/cloned folder
3. Let Unity import the project. This can take several minutes

## 4. Import Required Assets

The following assets are **commercial** and must be purchased separately from the Unity Asset Store. These assets are not included in this repository due to licensing restrictions.

Please acquire and import them into the project before attempting to build or play the game.

### Required Assets

- [Massive Clouds - Screen Space Volumetric Clouds](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/massive-clouds-screen-space-volumetric-clouds-131898)
- [Global Snow 2](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/global-snow-2-248191)
- [DOTween](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676)
- [Text Animator for Unity](https://assetstore.unity.com/packages/tools/gui/text-animator-for-unity-254677)
- [Third Person System 3](https://assetstore.unity.com/packages/templates/systems/third-person-system-3-0-2022-214330)
- [Dynamic Bone](https://assetstore.unity.com/packages/tools/animation/dynamic-bone-16743)
- [FinalIK](https://assetstore.unity.com/packages/tools/animation/final-ik-14290)
- [Stylized Water 2](https://assetstore.unity.com/packages/vfx/shaders/stylized-water-2-170386)
- [Dynamic Effects for Stylized Water 2 (Extension)](https://assetstore.unity.com/packages/vfx/shaders/dynamic-effects-for-stylized-water-2-extension-257865)
- [Underwater Rendering for Stylized Water 2 (Extension)](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/underwater-rendering-for-stylized-water-2-extension-185030)
- [Pegasus](https://assetstore.unity.com/packages/tools/animation/pegasus-65397)
> ⚠️ These assets are required for the full experience and for the game to compile successfully.

## 5. Configure Build Settings

Once all assets are imported:

1. Go to `File > Build Settings`
2. Switch to your target platform (Windows/Mac/Linux)
3. Ensure the correct scene(s) are added to the build list (e.g. `Assets/Scenes/MainMenu.unity`)
4. Set the resolution and quality settings as desired
5. Click `Build` or `Build and Run`

## 6. Editor Play Mode

To test the game in the editor:

- Press the **Play** button in the Unity toolbar
- Use a controller or keyboard/mouse to move around and test features
- Press `Esc` or `Start` to open the pause menu

## 7. Troubleshooting

- **Pink Materials:** Likely a missing shader or rendering issue. Make sure all assets are properly imported
- **Missing Scripts or References:** Check if Unity has properly recompiled scripts. Reimport the project or restart Unity
- **Build Errors:** Usually caused by missing commercial assets

## Need Help?

Feel free to open a GitHub Issue or ask questions on the Discord server.