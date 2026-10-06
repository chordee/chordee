<p align="center">
  <img src="assets/banner.webp" alt="Hsin Hua (Chordee) Lin Banner" width="100%">
</p>

[English](README.md) | [日本語](README.ja.md)

# 🎬 Hsin Hua (Chordee) Lin

<p>
  <b>Senior FX Artist & Pipeline TD</b> based in <b>Taipei, Taiwan</b> 🇹🇼<br>
  Bridging hands-on visual effects production with studio pipeline architecture.
</p>

<p>
  <a href="https://chordee.github.io/"><img src="https://img.shields.io/badge/Portfolio-chordee.github.io-2dd4bf?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://chordee.github.io/ja/"><img src="https://img.shields.io/badge/Portfolio-日本語版-2dd4bf?style=flat-square" alt="Portfolio JA"></a>
  <a href="https://www.linkedin.com/in/chordee/"><img src="https://img.shields.io/badge/LinkedIn-in%2Fchordee-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:chordee@gmail.com"><img src="https://img.shields.io/badge/Email-chordee%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

I have **15+ years** of experience in feature-film visual effects and pipeline engineering.

My work spans hands-on **Houdini FX** production and pipeline architecture. I have led phased studio transitions to **Houdini and Solaris**, designed layer-based **OpenUSD workflows**, and developed **C++ and Python tools** supporting production workflows across Maya, Houdini, Solaris, and Nuke.

---

## Tech Stack

### Languages & APIs
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/VEX-SideFX%20Houdini-FF4500?style=flat-square" alt="VEX">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Qt%20%2F%20PySide-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt">
</p>

### DCC & Production Software
<p>
  <img src="https://img.shields.io/badge/SideFX%20Houdini-FF6B00?style=flat-square&logo=sidefx&logoColor=white" alt="Houdini">
  <img src="https://img.shields.io/badge/Autodesk%20Maya-0696D7?style=flat-square&logo=autodesk&logoColor=white" alt="Maya">
  <img src="https://img.shields.io/badge/Foundry%20Nuke-F9B41B?style=flat-square&logo=foundry&logoColor=black" alt="Nuke">
  <img src="https://img.shields.io/badge/PFTrack-333333?style=flat-square" alt="PFTrack">
</p>

### Pipeline & Architecture
<p>
  <img src="https://img.shields.io/badge/OpenUSD%20%2F%20Solaris-00FFFF?style=flat-square&color=088389" alt="OpenUSD">
  <img src="https://img.shields.io/badge/Autodesk%20ShotGrid-111111?style=flat-square&logo=autodesk" alt="ShotGrid">
  <img src="https://img.shields.io/badge/ASWF%20Rez-000000?style=flat-square" alt="Rez">
  <img src="https://img.shields.io/badge/Pyblish-333333?style=flat-square" alt="Pyblish">
  <img src="https://img.shields.io/badge/ACES%20%2F%20OCIO-2B5797?style=flat-square" alt="ACES/OCIO">
  <img src="https://img.shields.io/badge/Git%20%2F%20GitHub-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

---

## Featured Open Source Projects

### Pipeline Architecture
- **[openusd-pipeline-architecture](https://github.com/chordee/openusd-pipeline-architecture)**\
  `OpenUSD` · `Solaris` · `Python` · `Asset Resolver`\
  Reference architecture for a production OpenUSD pipeline: 12 design documents on layer stacking and overrides, publish packaging, version pinning, validation, and Solaris implicit-layer governance, with tested Solaris output processors and USD splitting tools. Documentation in Traditional Chinese.

### DCC & Rendering Plug-ins
- **[maya-gaussian-splatting-viewport-plugin](https://github.com/chordee/maya-gaussian-splatting-viewport-plugin)**  
  `Maya` · `C++` · `OpenGL` · `Viewport 2.0`  
  Maya Viewport 2.0 plug-in in C++ and OpenGL for real-time 3D Gaussian Splatting (`.ply`) rendering.

- **[nuke-lens-distort-cv](https://github.com/chordee/nuke-lens-distort-cv)**  
  `Nuke NDK` · `C++` · `OpenCV`  
  Nuke NDK plug-in for lens distortion and undistortion using the OpenCV rational polynomial model (k1–k6, p1, p2) with Nerfstudio JSON support.

### Procedural & Motion Tools
- **[gnm-houdini](https://github.com/chordee/gnm-houdini)**  
  `Houdini HDA` · `Python` · `Google GNM`  
  Houdini Digital Asset (HDA) integrating Google's parametric statistical 3D head model (GNM) to generate editable head meshes in SOPs.

- **[kimodo-houdini-bridge](https://github.com/chordee/kimodo-houdini-bridge)**  
  `Houdini` · `Python` · `NVIDIA Kimodo`  
  Pipeline bridge connecting NVIDIA's text-driven motion generation model (Kimodo) directly into SideFX Houdini.

### AI Agents & Studio Tooling
- **[houdini-tools](https://github.com/chordee/houdini-tools)**  
  `Python` · `CLI` · `MCP` · `OpenUSD`  
  Lightweight toolkit and MCP server for inspecting `.bgeo.sc` geometry caches and USD scenes without requiring a local Houdini installation.

<details>
<summary>Guides & More Repositories</summary>
<br>

- **[colmap-camera-tracking](https://github.com/chordee/colmap-camera-tracking)** — Automated camera tracking and 3D reconstruction pipeline with Houdini and NeRF-compatible output
- **[mcp-server-shotgrid](https://github.com/chordee/mcp-server-shotgrid)** — Model Context Protocol server for Autodesk ShotGrid REST API integration
- **[mcp-server-openexr](https://github.com/chordee/mcp-server-openexr)** — MCP server for querying OpenEXR metadata, channels, and pixel statistics
- **[rez-studio-docs](https://github.com/chordee/rez-studio-docs)** — Rez package management architecture and cross-platform deployment guide for hybrid Windows/Linux VFX studios
- **[mayaGeoCache](https://github.com/chordee/mayaGeoCache)** — Maya geometry & nParticle cache (.mc/.mcx) I/O in Python with Houdini HDA exporter
- **[scripts-collection](https://github.com/chordee/scripts-collection)** — Production pipeline scripts for Houdini (Solaris USD) and Maya photogrammetry workflows

</details>

---

## Current Focus

Exploring Gaussian Splatting and practical AI-assisted tools for DCC workflows.

---

<p align="center">
  <sub>Explore selected projects and technical work on my <a href="https://chordee.github.io/">portfolio</a>.</sub>
</p>
