<p align="center">
  <img src="assets/banner.webp" alt="Hsin Hua (Chordee) Lin Banner" width="100%">
</p>

[English](README.md) | [日本語](README.ja.md)

# Hsin Hua (Chordee) Lin

<p>
  台湾・台北を拠点とする <b>Senior FX Artist & Pipeline TD</b><br>
  VFX制作の現場経験を活かし、スタジオのパイプライン設計・開発に取り組んでいます。
</p>

<p>
  <a href="https://chordee.github.io/"><img src="https://img.shields.io/badge/Portfolio-chordee.github.io-2dd4bf?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://chordee.github.io/ja/"><img src="https://img.shields.io/badge/Portfolio-日本語版-2dd4bf?style=flat-square" alt="Portfolio JA"></a>
  <a href="https://www.linkedin.com/in/chordee/"><img src="https://img.shields.io/badge/LinkedIn-in%2Fchordee-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:chordee@gmail.com"><img src="https://img.shields.io/badge/Email-chordee%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## プロフィール

長編映画のVFX制作とパイプライン開発に、**15年以上**携わってきました。

**HoudiniによるFX制作**からパイプライン設計までを担当しています。スタジオでの **Houdini・Solaris** への段階的な移行を主導し、レイヤー構成を軸とした **OpenUSDワークフロー**を設計してきました。また、Maya、Houdini、Solaris、Nukeの制作ワークフローを支える **C++・Pythonツール**を開発しています。

---

## 技術スタック

### 言語・API
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/VEX-SideFX%20Houdini-FF4500?style=flat-square" alt="VEX">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Qt%20%2F%20PySide-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt">
</p>

### DCC・制作ソフトウェア
<p>
  <img src="https://img.shields.io/badge/SideFX%20Houdini-FF6B00?style=flat-square&logo=sidefx&logoColor=white" alt="Houdini">
  <img src="https://img.shields.io/badge/Autodesk%20Maya-0696D7?style=flat-square&logo=autodesk&logoColor=white" alt="Maya">
  <img src="https://img.shields.io/badge/Foundry%20Nuke-F9B41B?style=flat-square&logo=foundry&logoColor=black" alt="Nuke">
  <img src="https://img.shields.io/badge/PFTrack-333333?style=flat-square" alt="PFTrack">
</p>

### パイプライン・アーキテクチャ
<p>
  <img src="https://img.shields.io/badge/OpenUSD%20%2F%20Solaris-00FFFF?style=flat-square&color=088389" alt="OpenUSD">
  <img src="https://img.shields.io/badge/Autodesk%20ShotGrid-111111?style=flat-square&logo=autodesk" alt="ShotGrid">
  <img src="https://img.shields.io/badge/ASWF%20Rez-000000?style=flat-square" alt="Rez">
  <img src="https://img.shields.io/badge/Pyblish-333333?style=flat-square" alt="Pyblish">
  <img src="https://img.shields.io/badge/ACES%20%2F%20OCIO-2B5797?style=flat-square" alt="ACES/OCIO">
  <img src="https://img.shields.io/badge/Git%20%2F%20GitHub-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

---

## 主なオープンソースプロジェクト

### パイプライン設計

- **[openusd-pipeline-architecture](https://github.com/chordee/openusd-pipeline-architecture)**\
  `OpenUSD` · `Solaris` · `Python` · `Asset Resolver`\
  制作向けOpenUSDパイプラインの参照設計。レイヤーの積み重ねとオーバーライド、パブリッシュ時のパッケージ構成、バージョン固定、検証、Solarisの暗黙レイヤー管理を扱う12本の設計文書を収録しています。テスト済みのSolaris Output ProcessorとUSD分割ツールも含みます。ドキュメントは繁体字中国語です。

### DCC・レンダリングプラグイン

- **[maya-gaussian-splatting-viewport-plugin](https://github.com/chordee/maya-gaussian-splatting-viewport-plugin)**\
  `Maya` · `C++` · `OpenGL` · `Viewport 2.0`\
  C++とOpenGLで開発したMaya Viewport 2.0プラグイン。3D Gaussian Splattingの `.ply` データをリアルタイムに描画します。

- **[nuke-lens-distort-cv](https://github.com/chordee/nuke-lens-distort-cv)**\
  `Nuke NDK` · `C++` · `OpenCV`\
  OpenCVの有理多項式モデル（k1–k6、p1、p2）を用いた、レンズ歪みの付与・補正用Nuke NDKプラグイン。NerfstudioのJSON形式にも対応しています。

### プロシージャル・モーションツール

- **[gnm-houdini](https://github.com/chordee/gnm-houdini)**\
  `Houdini HDA` · `Python` · `Google GNM`\
  Googleのパラメトリックな統計的3D頭部モデル（GNM）を統合したHoudini Digital Asset（HDA）。SOP上で編集可能な頭部メッシュを生成します。

- **[kimodo-houdini-bridge](https://github.com/chordee/kimodo-houdini-bridge)**\
  `Houdini` · `Python` · `NVIDIA Kimodo`\
  テキストからモーションを生成するNVIDIAのモデル「Kimodo」を、SideFX Houdiniへ直接接続するパイプラインブリッジです。

### AIエージェント・制作支援ツール

- **[houdini-tools](https://github.com/chordee/houdini-tools)**\
  `Python` · `CLI` · `MCP` · `OpenUSD`\
  ローカルにHoudiniをインストールせずに、`.bgeo.sc` ジオメトリキャッシュやUSDシーンを検査できる軽量ツールキット・MCPサーバーです。

<details>
<summary>ガイド・その他のリポジトリ</summary>
<br>

- **[colmap-camera-tracking](https://github.com/chordee/colmap-camera-tracking)** — カメラトラッキングと3D再構築を自動化するパイプライン。HoudiniおよびNeRF互換の出力に対応
- **[mcp-server-shotgrid](https://github.com/chordee/mcp-server-shotgrid)** — Autodesk ShotGrid REST API連携用のModel Context Protocolサーバー
- **[mcp-server-openexr](https://github.com/chordee/mcp-server-openexr)** — OpenEXRのメタデータ、チャンネル、ピクセル統計を照会するMCPサーバー
- **[rez-studio-docs](https://github.com/chordee/rez-studio-docs)** — Windows・Linux混在のVFXスタジオ向けRezパッケージ管理設計・クロスプラットフォーム導入ガイド
- **[mayaGeoCache](https://github.com/chordee/mayaGeoCache)** — PythonによるMayaジオメトリ・nParticleキャッシュ（.mc/.mcx）の入出力と、Houdini HDAエクスポーター
- **[scripts-collection](https://github.com/chordee/scripts-collection)** — Houdini（Solaris USD）とMayaのフォトグラメトリワークフロー向け制作パイプラインスクリプト

</details>

---

## 現在の関心・取り組み

Gaussian Splattingと、DCCワークフローで実用的に活用できるAI支援ツールを探索しています。

---

<p align="center">
  <sub>制作実績や技術的な取り組みは、<a href="https://chordee.github.io/ja/">日本語ポートフォリオ</a>をご覧ください。</sub>
</p>
