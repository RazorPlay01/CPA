# Custom Player Animations - Example Resource Pack

[![Versions](http://cf.way2muchnoise.eu/versions/1364067.svg)](https://www.curseforge.com/minecraft/mc-mods/cpa)
[![Downloads](http://cf.way2muchnoise.eu/full_1364067_downloads.svg)](https://www.curseforge.com/minecraft/mc-mods/cpa)
[![Downloads Modrinth](https://img.shields.io/modrinth/dt/cpa?color=00AF5C&label=downloads&logo=modrinth)](https://modrinth.com/mod/cpa)

**Version:** 1.21.8+ 
**Dependencies:** [Custom Player Animations Mod](https://legacy.curseforge.com/minecraft/mc-mods/cpa), [Player Animation Library](https://www.curseforge.com/minecraft/mc-mods/player-animation-library)  
**Author:** RazorPlay01

## Overview

Welcome to the **Example Resource Pack** for **Custom Player Animations**, a companion to the visionary mod submitted for the **2025 CurseForge ModJam** under the theme *"The Future."* This resource pack serves as a **template and guide** for players and creators who want to **customize player animations** in Minecraft. By leveraging the mod’s flexible animation system, this pack demonstrates how to **override and personalize animations** to create unique, futuristic movement styles.

This resource pack is designed to be **simple to use and modify**, empowering you to craft animations that match your vision—whether it’s a **cyberpunk swagger**, a **sci-fi glide**, or something entirely new. Let’s shape the future of Minecraft animations together!

## ✨ Features

### 🚀 Example Animations

This resource pack includes a set of **pre-made animation overrides** to showcase the potential of **Custom Player Animations**. It modifies a subset of the mod’s animations to give you a taste of what’s possible:

| **Category** | **Animations Modified** | **Description** |
|--------------|-------------------------|--------------|
| **🟢 Main Animations** | Walking, Running, Idle Standing | Smooth, futuristic movements with a slight hover-like effect. |
| **🟡 Overlay Animations** | Sword Swing, Bow Drawing | Enhanced with dynamic flourishes for a high-tech combat feel. |
| **🔴 Special Animations** | Up-Hand Gesture | A sleek, robotic wave for futuristic interactions. |

These examples are stored in `assets/cpa/player_animations` as **JSON files**, ready for you to explore and tweak.

### 🎨 How to Customize Animations

The **Custom Player Animations** mod makes animation customization **accessible and powerful** through resource packs. Here’s how you can modify animations using this example pack as a starting point:

1. **Locate the Animation Files**  
   - Inside the resource pack, navigate to `assets/cpa/player_animations`.  
   - You’ll find JSON files for each animation (e.g., `walking`, `running`).  
   - Each file defines keyframes, rotations, and timings for smooth animation.

2. **Edit with Blockbench**  
   - The pack includes a **`.bbmodel` file** for use with **Blockbench**, a free tool for creating and editing Minecraft models and animations.  
   - Open the `.bbmodel` file in Blockbench to preview or modify animations visually.  
   - Export your changes as JSON files to update the resource pack.

3. **Override Animations**  
   - Copy the example resource pack folder to your Minecraft `resourcepacks` directory.  
   - Modify the JSON files directly or replace them with your own creations.  
   - Reload the resource pack in-game (`F3 + T` or via the resource pack menu) to see your changes instantly.

4. **Test and Iterate**  
   - Launch Minecraft with the **Custom Player Animations** mod installed.  
   - Test your animations in-game to ensure they feel natural and fluid.  
   - Adjust timings, keyframes, or easing functions in the JSON files to perfect your animations.

> **Pro Tip**: Use the included `.bbmodel` file as a template to create entirely new animations. Experiment with futuristic themes like low-gravity bounces or holographic effects!

### ⚙️ Animation File Structure

Each animation JSON file follows a structure compatible with the **Player Animator Library API**. Here’s a simplified example of what a `walking.json` file might look like:

```json
{
  "format_version": "1.8.0",
  "animations": {
    "blank_loop_animation": {
      "loop": true,
      "bones": {}
    }
  },
  "geckolib_format_version": 2
}
```

### 🛠️ Tools and Resources

- **Blockbench**: Download from [blockbench.net](https://www.blockbench.net/) to edit animations visually.  
- **Player Animator Library Documentation**: Check the [Player Animation Library](https://www.curseforge.com/minecraft/mc-mods/player-animation-library) page for advanced API details.  
- **Community Tutorials**: Search on CurseForge or Modrinth for community guides on animation modding.

## 📥 Installation

1. Ensure you have **Minecraft 1.21.8** with **Fabric** installed.  
2. Install the **[Custom Player Animations Mod](https://legacy.curseforge.com/minecraft/mc-mods/cpa)** and **[Player Animation Library](https://www.curseforge.com/minecraft/mc-mods/player-animation-library)**.  
3. Place this **Example Resource Pack** in your Minecraft `resourcepacks` folder.  
4. Activate the resource pack in the Minecraft resource pack menu.  
5. (Optional) Modify the JSON files or use Blockbench to create your own animations.  
6. Reload resources (`F3 + T`) to apply changes.

## ✅ Compatibility

- **Client-side only**: Works on any server as long as the mod is installed on your client.  
- Compatible with most animation-friendly mods.  
- Designed to work seamlessly with the **Custom Player Animations** mod.

## 🏆 Credits

- **Created by**: RazorPlay01  
- **Powered by**: [Player Animator Library](https://www.curseforge.com/minecraft/mc-mods/player-animation-library)  
- **Inspired by**: 2025 CurseForge ModJam’s theme *"The Future"*  

## 🌐 Links

- **Mod Page**: [CurseForge](https://legacy.curseforge.com/minecraft/mc-mods/cpa) | [Modrinth](https://modrinth.com/mod/cpa)  
- **Support**: Reach out on CurseForge or Modrinth for help with customization!

***

**Unleash your creativity and redefine how players move in Minecraft’s future!**
