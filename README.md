[AtomicLogo]: https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/images/repo/Atomic-Game-Engine-512.png
![alt text][AtomicLogo]

---

## ⚙️ Maintenance Notice

**This project is now actively maintained by [killerdevildog](https://github.com/killerdevildog).**  
When I discovered the Atomic Game Engine it had been archived and unmaintained, so I’ve taken on stewardship to keep it alive and modern.

> **Important:** The CEF version bundled with Atomic is over **10 years old** and depends on deprecated libraries that modern Ubuntu releases (including 24.04) no longer include by default. A key part of this maintenance effort will be bumping CEF to a supported, up‑to‑date release.

### 🛣️ Roadmap

1. **Update CEF submodule**  
   - Current CEF is ancient (10+ years) and relies on obsolete Ubuntu libraries.  
   - Bump to the latest CEF release from [killerdevildog/cef](https://github.com/killerdevildog/cef).  
2. **Primary platform support**  
   - Ensure the engine builds and runs smoothly on **Ubuntu 24.04 LTS** and other major Linux distributions.  
   - Native Windows support via Visual Studio/MSVC.  
3. **Secondary platform support**  
   - macOS, Android, iOS, and WebGL builds will follow once the Linux/Windows workflow is solid.  
4. **Future direction**  
   - After full Ubuntu 24.04 compatibility, I’ll evaluate ongoing feature work.  
   - With GitHub Copilot assistance, I plan to maintain and push updates more frequently than past maintainers.

---

#### Please note that Atomic was originally archived and is no longer officially supported by the original maintainers.  
**Issues** may not be addressed, but pull requests—especially those fixing build or runtime issues—are welcome and will be reviewed.  

---

### Why Atomic?

The Atomic Game Engine is powerful native technology with a consistent API and tooling available in C++, C#, TypeScript, and JavaScript. The Atomic Editor is **installed in over 75 countries** and has seen production use across multiple industries.

Atomic can also be used as a library in existing projects with a C++ SDK, C# NuGet, and JavaScript npm package in development.

---

### Atomic Technology

- Consistent **2D/3D API** available in **JavaScript, TypeScript, C#, and C++**
- Built-in Monaco JavaScript/TypeScript editor and support for **VSCode** and **Atom**
- C# IDE integration with **Visual Studio**, **Xamarin Studio**, and **MonoDevelop**
- **Android, iOS, Windows, macOS, Linux, and WebGL** platform deployment
- High performance native C++ core with single‑command builds and minimal dependencies
- Node‑based scene graph with low‑level graphics API access for custom rendering (D3D9/11, OpenGL 2/3/ES2, WebGL)
- Modular component system supporting C#, JavaScript, TypeScript, and C++ logic components with networking
- Drag‑and‑drop import of 2D/3D formats: FBX, Collada, Blender, Spriter, Tiled, and more
- Preview mode runs in a subprocess for editor stability and reduced memory fragmentation
- Embedded Chromium WebView for e‑commerce, social graph access, video streaming, etc.
- Automated script binding generation for native C++ subsystems
- First‑class third‑party integrations: Box2D/Bullet physics, Recast/Detour pathfinding, TurboBadger UI, CEF3, duktape VM, SDL2
- Available as precompiled binaries or fork on GitHub under the MIT license
- **Backed by industry professionals** with decades of experience in game and technology development

---

### Build Instructions

The Atomic Editor can be built for your platform using these [build instructions](https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/Building-Atomic-from-Source).

---

#### Community & Documentation

- **Discourse**: https://discourse.atomicgameengine.com/  
- **Gitter Chat**: https://gitter.im/AtomicGameEngine/AtomicGameEngine/  
- **Wiki**: https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/  

---

#### Screenshots

![Atomic Examples][DevSnapshot]  
[DevSnapshot]: https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/images/repo/DevSnapshot2116.png

![Atomic on Mobile][ToonTown]  
[ToonTown]: https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/images/repo/ToonTownTouchUpdate.gif

![Atomic Build Settings][AndroidBuildSettings]  
[AndroidBuildSettings]: https://github.com/AtomicGameEngine/AtomicGameEngine/wiki/images/repo/AndroidBuildSettings.png

---

### Project History

THUNDERBEAST GAMES began developing the Atomic Game Engine on November 12, 2014 by forking Urho3D. It was released under the permissive MIT license at GDC 2016. Atomic has 27 contributors, and runs on Windows, macOS, Android, iOS, Linux, and WebGL!  

