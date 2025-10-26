<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=700&size=24&pause=1000&color=00FF7F&background=0B0B0C00&center=true&vCenter=true&width=600&lines=Meher+%E2%80%9CDavanci%E2%80%9D;Game+Dev+%E2%80%A2+Tools+%E2%80%A2+Automation;Retro+CRT+Signal+Online" alt="Typing intro">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CRT_MODE-ACTIVE-00FF7F?style=for-the-badge&labelColor=111111" alt="CRT Mode">
  <img src="https://img.shields.io/badge/SYNC_STATUS-STABLE-00FF7F?style=for-the-badge&labelColor=111111" alt="Sync Status">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0B0B0C&height=80&section=header&text=Game%20Dev%20%E2%80%A2%20Tools%20%E2%80%A2%20Automation&fontColor=00FF7F&fontSize=24&fontAlign=50&fontAlignY=45&desc=Signal%3A%20Online&descAlign=50&descAlignY=75" alt="Capsule header">
</p>

<div align="center">

```
┌────────────────────────────────────────────┐
│  Meher “Davanci”                           │
│  Game Dev • Tools • Automation             │
│  Paris (Île-de-France) · FR / EN           │
│  Motto: Ship tactile worlds & robust pipes │
└────────────────────────────────────────────┘
```

</div>

- [Projects](#projects)
- [Stack & Toolbox](#stack--toolbox)
- [Terminal Feed](#terminal-feed)
- [Code Snippet](#code-snippet)
- [Contact & Links](#contact--links)

## Projects

```
╔══════════════════════════════════════════════╗
║ Unity Tools Pack (Editor)                    ║
╟─ What: Addressables helpers, TMP i18n,       ║
║         screenshot kit, perf macros          ║
╟─ Tech: C# · URP · Editor · Addressables      ║
╟─ Link: #                                     ║
╚══════════════════════════════════════════════╝
```

```
╔══════════════════════════════════════════════╗
║ Cocos Build Orchestrator                     ║
╟─ What: Deterministic iOS/Android/Xcode       ║
║         outputs for Cocos 3.x                ║
╟─ Tech: Node/TS · Python · Xcode · CLI        ║
╟─ Link: #                                     ║
╚══════════════════════════════════════════════╝
```

```
╔══════════════════════════════════════════════╗
║ Jenkins Auto-Gen Pipeline                    ║
╟─ What: Monorepo CI for Unity/Cocos/Flutter;  ║
║         dynamic engine paths; safe cleanup   ║
╟─ Tech: Groovy · Go · Python · macOS runners  ║
╟─ Link: #                                     ║
╚══════════════════════════════════════════════╝
```

```
╔══════════════════════════════════════════════╗
║ Rage Panda (Mobile)                          ║
╟─ What: Unity 6 mobile game; URP optimizations║
║         IAP; analytics; CI delivery          ║
╟─ Tech: Unity 6 · C# · Mobile                 ║
╟─ Link: #                                     ║
╚══════════════════════════════════════════════╝
```

## Stack & Toolbox

```
┌──────── CORE DEV ────────┬────── ENGINES ────────┬───── OPS / CI ──────┐
│ C# · Node.js · TypeScript │ Unity 6 · Cocos 3.x   │ Jenkins · GitHub CI │
│ Python · Go · Groovy      │ Godot (tooling)       │ Fastlane · Xcode    │
│ Bash · Zsh · Regex        │ Shader Graph          │ Docker · Homebrew   │
└───────────────────────────┴───────────────────────┴─────────────────────┘
```

<p>
  <img src="https://img.shields.io/badge/C%23-00FF7F?style=for-the-badge&labelColor=111111&logo=csharp&logoColor=00FF7F" alt="C#">
  <img src="https://img.shields.io/badge/Unity-00FF7F?style=for-the-badge&labelColor=111111&logo=unity&logoColor=00FF7F" alt="Unity">
  <img src="https://img.shields.io/badge/Node.js-00FF7F?style=for-the-badge&labelColor=111111&logo=node.js&logoColor=00FF7F" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-00FF7F?style=for-the-badge&labelColor=111111&logo=python&logoColor=00FF7F" alt="Python">
  <img src="https://img.shields.io/badge/Jenkins-00FF7F?style=for-the-badge&labelColor=111111&logo=jenkins&logoColor=00FF7F" alt="Jenkins">
  <img src="https://img.shields.io/badge/GitHub_Actions-00FF7F?style=for-the-badge&labelColor=111111&logo=githubactions&logoColor=00FF7F" alt="GitHub Actions">
</p>

## Terminal Feed

```ansi
\u001b[0;32m[00:01:42] boot sequence complete — signal integrity nominal\u001b[0m
\u001b[0;36m[00:03:09] syncing editor tooling → Unity/Cocos orchestration layer\u001b[0m
\u001b[0;33m[00:05:27] deploying CI nodes — macOS runners standing by\u001b[0m
\u001b[0;35m[00:07:54] analytics ping acknowledged — Rage Panda telemetry stable\u001b[0m
\u001b[0;32m[00:09:18] awaiting next command...\u001b[0m
```

## Code Snippet

```csharp
using UnityEngine;

[ExecuteInEditMode]
public sealed class GridSnapper : MonoBehaviour
{
    [SerializeField] float gridSize = 0.5f;

    void Update()
    {
        if (!Application.isEditor || Application.isPlaying) return;
        var p = transform.position;
        p.x = Mathf.Round(p.x / gridSize) * gridSize;
        p.y = Mathf.Round(p.y / gridSize) * gridSize;
        p.z = Mathf.Round(p.z / gridSize) * gridSize;
        transform.position = p;
    }
}
```

## Contact & Links

```
User:   meher-davanci
Email:  meher.davanci(at)proton.me
City:   Paris (Île-de-France) · FR / EN
Site:   https://davanci-ink.dev
LinkedIn: https://linkedin.com/
Itch.io:  https://itch.io/
```

<details>
  <summary>Version FR</summary>

Je conçois des outils Unity/Cocos et des pipelines CI modulaires pour livrer des jeux mobiles stables tout en gardant une esthétique rétro assumée.

</details>

---

Last updated: 2025-10-26

