<h1 align="center">awesome-rokid</h1>

<p align="center">
  A curated list of apps, tools, SDKs, docs, launchers, experiments, and companion projects built for Rokid glasses.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Rokid%20Glasses-0f1514?style=for-the-badge" alt="Platform: Rokid Glasses" />
  <img src="https://img.shields.io/badge/focus-Apps%20%7C%20Tools%20%7C%20AI-1d7f5f?style=for-the-badge" alt="Focus: Apps, Tools, AI" />
  <img src="https://img.shields.io/badge/status-Community%20Curated-cfe8d6?style=for-the-badge" alt="Status: Community Curated" />
  <img src="https://img.shields.io/badge/projects-50+-8b5cf6?style=for-the-badge" alt="50+ Projects" />
</p>

<p align="center">
  <a href="https://ko-fi.com/M8R61ZTXMI" target="_blank">
    <img height="36" style="border:0px;height:36px;" src="https://storage.ko-fi.com/cdn/kofi4.png?v=6" border="0" alt="Buy Me a Coffee at ko-fi.com" />
  </a>
</p>

<p align="center">
  A single place to discover what people are actually building for the Rokid ecosystem.
</p>

---

### Table of contents

[Why this exists](#-why-this-exists) · [Scope](#-scope) · [AI and assistants](#-ai-and-assistants) · [AIUI agents](#-aiui-agents) · [Translation and communication](#-translation-and-communication) · [Navigation and mobility](#-navigation-and-mobility) · [Media and utilities](#-media-and-utilities) · [iOS apps](#-ios-apps) · [Learning and experiments](#-learning-and-experiments) · [EUNG SOFT catalog](#-catalog-apps-by-eung-soft) · [Infra and bridges](#-infra-and-bridges) · [China / Lingzhu ecosystem](#-china--lingzhu-ecosystem) · [Templates and demos](#-templates-and-demos) · [Developer resources](#-developer-resources) · [Add your project](#-add-your-project)

---

## 💡 Why this exists

Rokid projects are still scattered across personal repos, prototypes, hackathon builds, and side experiments.

This repo collects them in one clean index so developers, tinkerers, and curious users can:

- discover real apps for Rokid glasses
- find inspiration for their own builds
- track what is already possible on the platform
- share new projects with the community

> This is a community list, not an official Rokid catalog.

---

## 📐 Scope

Projects listed here should match at least one of these:

- native apps that run directly on Rokid glasses
- phone plus glasses companion systems
- launchers, HUDs, utilities, or media tools for Rokid devices
- server or bridge projects built specifically for a Rokid workflow
- SDKs, documentation, or developer resources that help people build for Rokid
- serious experiments that help push the ecosystem forward

---

## Directory

### 🤖 AI and assistants

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `AssistBridge` | `Phone + Glasses` | Relays visible Gemini or Google Assistant answers from an Android phone to a Rokid glasses HUD using Accessibility capture and Global Hi Rokid CXR-L. | [Repo](https://github.com/Anezium/AssistBridge) |
| `Rokid Claude` | `Glasses + Mac Relay` | Voice-control Claude Code running on a home Mac from Rokid Glasses, with local whisper.cpp STT, WebSocket relay, streamed agent progress, and on-glasses permission confirmation. | [Repo](https://github.com/williamlzz/Rokid_Claude) |
| `Clawsses` | `Phone + Glasses` | Wearable AI interface for Rokid glasses powered by OpenClaw, with voice, camera, streaming chat, and TTS. | [Repo](https://github.com/dweddepohl/clawsses) |
| `HelloRokid-v2` | `Phone + Glasses + Backend` | Business-card scanning and management system for Rokid glasses, with glasses camera capture, BLE image transfer, a phone app, and Gemini-backed analysis. | [Repo](https://github.com/saintlouisleetokyowest-bot/HelloRokid-v2) |
| `JSOS` | `Phone + Glasses` | Development-preview spatial interface for Rokid glasses and a local or private OpenClaw Gateway, with a phone core app, dedicated glasses HUD, voice input, sessions, TTS, and camera handoff. | [Repo](https://github.com/IWhatsskill/JSOS) |
| `Rokid AI Input Bridge` | `Phone + Glasses Prototype` | Experimental Rokid glasses and phone companion stack for Gemini-powered keyboard or voice input, glasses-side answers, calendar/mail notification context, and a small Rokid manager launcher. | [Repo](https://github.com/tenru-do/rokid-ai-input-bridge) |
| `openclaw-rokid` | `Glasses App` | Direct WiFi OpenClaw client for Rokid AI Glasses, focused on voice-first wearable AI without a phone bridge. | [Repo](https://github.com/etdofreshai/openclaw-rokid) |
| `NeuroGlasses` | `Phone + Glasses` | Experimental Rokid AI chat bridge with vision, ASR, TTS, and OpenAI-compatible API support. | [Repo](https://github.com/ECHO-HELLO-WORLD424/NeuroGlasses) |
| `Rokid_auditC_v2` | `RV101 + Backend` | Voice-powered AR quality-control system for diagnostic labs on Rokid RV101, with CXR-M, FastAPI, Whisper transcription, AI verification, HUD status, and PDF/TXT reports. | [Repo](https://github.com/Bellzum/Rokid_auditC_v2) |
| `RokidGlassAI` | `Phone + Glasses` | Photo-based AI assistant that captures images on Rokid glasses, sends them to a phone over Bluetooth SPP, calls a vision relay, and displays paged answers on the glasses. | [Repo](https://github.com/Spphire/RokidGlassAI) |
| `RokidAIAssistant` | `Phone + Glasses` | Open-source Android AI assistant for Rokid Glasses with voice control and intelligent query handling. | [Repo](https://github.com/zero2005x/RokidAIAssistant) |
| `rokid__visual_agent` | `Phone + Glasses` | CXR-based visual AI assistant for Rokid AR glasses that captures a photo and voice query, streams a vision-model answer to the HUD, and speaks it on the phone. | [Repo](https://github.com/im-sanjay-sai/rokid__visual_agent) |
| `rokid-ar-agent` | `Server Agent` | ReAct + RAG multi-tool AI agent for Rokid AR glasses with SSE streaming output. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-ar-agent) |
| `rokid-haitangui-agent` | `Voice Game Agent` | Voice-driven turtle soup reasoning game agent built for Rokid AR glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-haitangui-agent) |
| `rokid-leetcode-hot100-agent` | `Learning Agent` | Voice-first LeetCode Hot100 tutor for Rokid AR glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-leetcode-hot100-agent) |
| `rokid-resume-interviewer-agent` | `Interview Agent` | AI mock interviewer for Rokid AR glasses based on resume text or spoken self-introduction. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-resume-interviewer-agent) |
| `rokid_ai_agent` | `Server Agent` | Smart scene agent system for Rokid AI glasses with search, translation, memory, and glasses control. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid_ai_agent) |
| `rokid_ai_vision_rag` | `Vision Backend` | Multimodal visual analysis and RAG knowledge assistant for Rokid AI glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid_ai_vision_rag) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🧠 AIUI agents

AIUI projects that run as Rokid/Lingzhu `.aix` agents or help build and debug them.

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `Rokid-AIUI` | `AIUI Dev Kit` | Reference kit for contract-driven AIUI agent development on Rokid AI glasses, with HUD design rules, project templates, local debug guidance, and `.aix` packaging workflow. | [Repo](https://github.com/wangqioo/Rokid-AIUI) |
| `rokid-aiui-lab` | `AIUI Lab` | Collection of Rokid Glasses and Lingzhu AIUI experiments, including QR scanning, beginner tutorials, QR code tooling, capability probes, and field notes. | [Repo](https://github.com/saibozhanzhang/rokid-aiui-lab) |
| `rokid_aiui_logtool` | `AIUI Tool` | Standalone AIUI logging demo that posts glasses interaction logs to a local Node.js server and displays them live in a browser via SSE. | [Repo](https://github.com/MersiSun/rokid_aiui_logtool) |
| `Rokid_Cube_Copilot` | `AIUI App` | Rubik's Cube solving coach for Rokid single-green Micro-LED glasses, with camera scanning, local min2phase solving, HUD arrows, and voice controls. | [Repo](https://github.com/guiguihui/Rokid_Cube_Copilot) |
| `RokidInterviewCrusher` | `AIUI App` | Interview training and review assistant for Rokid AIUI, with short HUD hint cards, user-triggered recording, OpenAI-compatible model config, and structured post-interview feedback. | [Repo](https://github.com/shuyixiao-better/RokidInterviewCrusher) |
| `Rokid-MeetMemo` | `AIUI App` | Offline conversation-memory AIUI agent for Rokid AR glasses that turns spoken notes about people into relationship cards, follow-up tasks, and glanceable HUD recall. | [Repo](https://github.com/qrx-joe/Rokid-MeetMemo) |
| `rokid-jingzhai-energy-station` | `AIUI Health Game` | Gentle neck-and-shoulder relaxation game MVP for Rokid AIUI, combining safe posture exercises, light motion gameplay, and AI wellness reports. | [Repo](https://github.com/sojipi/rokid-jingzhai-energy-station) |
| `rokid-life-danmaku-layer` | `AIUI Prototype` | Ambient life-commentary overlay prototype for Rokid Glass AIUI, simulating scene understanding, persona-driven comments, memory cues, safety controls, and recap concepts. | [Repo](https://github.com/Yrd980/rokid-life-danmaku-layer) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🌍 Translation and communication

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `rokid-ar-translator` | `Translation App` | Real-time AR translation workflow built with the Rokid Glasses SDK and LLM-based processing. | [Repo](https://github.com/Donald8511/rokid-ar-translator) |
| `rokid-spain-trip` | `Translation App` | Real-time translation app for Rokid AR glasses, built around travel use cases such as Spain or Italy trips. | [Repo](https://github.com/etdofreshai/rokid-spain-trip) |
| `Rokid-VideoCall` | `Communication App` | WebRTC-based remote audio and video calling system designed for Rokid Glasses. | [Repo](https://github.com/njujiangxiang/Rokid-VideoCall) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🧭 Navigation and mobility

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `Rokid-GMaps` | `Phone + Glasses` | Turn-by-turn navigation for Rokid AR glasses with optional Google provider support and transit mode. | [Repo](https://github.com/Anezium/Rokid-GMaps) |
| `Rokid-Maps` | `Phone + Glasses` | Standalone map and directions app for Rokid AI Glasses. | [Repo](https://github.com/chartmann1590/Rokid-Maps) |
| `rokid-ar-navigation` | `Glasses App` | Native AR navigation app for Rokid AI Glasses with nearby search, voice destination search, and walking HUD. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-ar-navigation) |
| `M365-Rokid-HUD` | `Mobility HUD` | BLE telemetry HUD for Xiaomi M365 scooters with encrypted communication and Rokid-facing display logic. | [Repo](https://github.com/zero2005x/M365-Rokid-HUD) |
| `RokidSmartLife` | `Glasses App` | Local life and POI navigation app for Rokid AI glasses with D-pad controls. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/RokidSmartLife) |
| `Rokid_Subway` | `Transit App` | Voice-controlled subway navigation app for Rokid AR smart glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/Rokid_Subway) |
| `Rokid_Wifi` | `Utility App` | WiFi connection tool for touchless Rokid AR glasses with gesture and offline voice input. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/Rokid_Wifi) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🎵 Media and utilities

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `R08-Access-Bridge` | `Phone + Glasses` | Uses the R08 smart ring as a navigation controller for Rokid Glasses, bridging ring input into glasses-friendly controls. | [Repo](https://github.com/Anezium/R08-Access-Bridge) |
| `Rokid-APKs` | `Phone + Glasses` | Installs Android APKs on Rokid glasses from a phone using CXR-M, Hi Rokid CXR-L, Bluetooth SPP, or Wi-Fi LAN transfer modes. | [Repo](https://github.com/Anezium/Rokid-APKs) |
| `RokidBrew` | `Phone App` | Community app store for Rokid AR glasses, with browsing, app details, update tracking, and install flows for phone, glasses, and combo apps. | [Repo](https://github.com/Anezium/RokidBrew) |
| `OverlayRec` | `Glasses App` | Triggers Rokid AR screenshots and AR recording from the glasses with a two-finger gesture overlay. | [Repo](https://github.com/Anezium/OverlayRec) |
| `Rokid Zoom Camera` | `Glasses App` | Unofficial camera prototype for Rokid Glasses with temple-swipe zoom, zoomed photo capture, and physical-button video recording. | [Folder](https://github.com/tenru-do/----/tree/main/rokid/rokid-zoom-camera) |
| `Rokid Lyrics` | `Phone + Glasses` | Streams synced song lyrics from an Android phone to Rokid glasses over Bluetooth. | [Repo](https://github.com/Anezium/Rokid-Lyrics) |
| `Rokid Live Studio` | `Phone + Glasses` | Streams the Rokid Glasses camera and microphone from an Android phone to YouTube or Twitch, with preview, encoding, RTMP publishing, and chat overlay support. | [Repo](https://github.com/Anezium/Rokid-Live-Studio) |
| `Rokid Relay` | `Phone + Glasses` | Forwards replyable Android phone notifications to a Rokid Glasses overlay and lets you answer from the glasses with voice input, CXR audio, and Android direct reply. | [Repo](https://github.com/Anezium/Rokid-Relay) |
| `Tasker Bridge` | `Phone + Glasses` | Launches Android Tasker automations from a Rokid Glasses HUD, using Global Hi Rokid CXR-L for helper setup and Bluetooth for task lists and launch commands. | [Repo](https://github.com/Anezium/Tasker-Bridge) |
| `Rokid-Scribe` | `Phone + Glasses` | Captures voice notes on Rokid glasses, syncs them to a phone, transcribes them locally, and exports transcripts as TXT or PDF. | [Repo](https://github.com/Anezium/Rokid-Scribe) |
| `rokid-vibe-notify` | `Notification Bridge` | Minimal Mac-to-phone-to-glasses notification bridge that pushes Claude Code events and other alerts onto Rokid Glasses. | [Repo](https://github.com/GaryChangCN/rokid-vibe-notify) |
| `hubu` | `Fitness HUD` | Rokid Glasses app that connects to BLE devices such as Garmin watches and displays live workout metrics like pace, heart rate, and cadence. | [Repo](https://github.com/hanabix/hubu) |
| `Rokid Manager 1.5` | `System Utility` | Allows you to turn Wi-Fi on or off, add Bluetooth devices, install or uninstall apps, and clean up memory. | [Download](https://drive.google.com/file/d/1VIZ9gsBRQ06ySyBgqtbMLBBJIkfaZ05x/view) |
| `RokidGlassesAppCenter` | `Phone + Glasses` | Remote app manager that lists, launches, stops, installs, and uninstalls apps on Rokid Glasses from a phone companion app. | [Repo](https://github.com/TakanariShimbo/RokidGlassesAppCenter) |
| `RokidGlassesReader` | `Phone App` | Android reading companion that captures on-screen text from phone apps such as WeChat Reader and streams it to Rokid Glasses in real time. Chinese-only UI. | [Repo](https://github.com/conclean/RokidGlassesReader) |
| `rokid-Strava` | `RV101 + Phone` | Strava workout HUD for Rokid RV101 on YodaOS-Sprite, streaming duration, distance, pace, and speed from phone notifications to a glasses-side Bluetooth SPP dashboard. | [Repo](https://github.com/mlustosa/rokid-Strava) |
| `rokid-glass-transfer` | `YodaOS-Sprite Utility` | PC-to-glasses wireless APK transfer tool for Rokid AR Glasses on YodaOS-Sprite, using UDP discovery, a local HTTP server, and a lightweight glasses-side installer app. | [Repo](https://github.com/mlustosa/rokid-glass-transfer) |
| `rokid-newsfeed` | `Glasses App` | Minimal news feed app for Rokid AI Glasses that opens a Google/Chrome-style personalized news feed, with optional Google API configuration. | [Repo](https://github.com/mlustosa/rokid-newsfeed) |
| `rokid-youtube` | `Glasses App` | Minimal web-based YouTube player for Rokid glasses, configured with a YouTube API key and packaged as an APK. | [Repo](https://github.com/mlustosa/rokid-youtube) |
| `Rokid NewPipe` | `Video App` | Rokid-focused NewPipe fork with a 480x640 glasses UI, swipe/tap/back navigation, simplified video detail screens, accessible player actions, and R08 ring support. | [Repo](https://github.com/Anezium/Rokid-NewPipe) |
| `Rokid Remote / Rokid Browser` | `Phone + Glasses` | Web browser for Rokid glasses controlled from an Android phone over Bluetooth, with trackpad input, scrolling, zoom, typing, bookmarks, history, WiFi management, and theater mode. | [Repo](https://github.com/Inplov/rokid-browser) |
| `Rokidglasses-HUD` | `Glasses App` | Chinese head-up utility for Rokid Glasses that uses accessibility and motion sensors to wake the display on head tilt and show a small time/date overlay. | [Repo](https://github.com/HagridANG/Rokidglasses-HUD) |
| `Rokid Shell` | `Glasses App` | Native file explorer for Rokid glasses with APK install flow and local HTTP transfer server. | [Repo](https://github.com/Anezium/Rokid-Shell) |
| `RokidAppMaker / GazeMou` | `Launcher / Input Tool` | Head-gesture cursor, wake mode, favorites, and app drawer utility for Rokid Glasses. | [Release](https://github.com/KUPdriveouter/RokidAppMaker/releases/tag/v1.6.0) |
| `rokid-ssh-terminal` | `Developer Tool` | Glasses-native SSH terminal and tmux control surface for Rokid glasses. | [Repo](https://github.com/bzerk/rokid-ssh-terminal) |
| `photoDel4rokidglasses` | `Utility App` | Simple utility to view and delete photos or videos directly on Rokid glasses. | [Repo](https://github.com/osagem/photoDel4rokidglasses) |
| `Rokid Manga Viewer` | `Reader App` | Manga and comic reader optimized for Rokid AR glasses, with direct ZIP loading, touchpad/DPAD/R08 controls, inverted-color mode, spread view, and saved reading progress. | [Repo](https://github.com/vyw00741/rokid-manga-viewer) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🍎 iOS apps

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `Rokid Lyrics iOS` | `iOS + Glasses` | Native SwiftUI companion for Rokid Lyrics with Spotify OAuth PKCE currently-playing lookup, synced lyrics provider fallback, local playback timeline controls, CXR-L integration, and IPA build workflows. | [Repo](https://github.com/Anezium/Rokid-Lyrics-iOS) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🧪 Learning and experiments

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `Memora_rokid` | `Learning App` | Immersive language learning app for Rokid glasses with HUD study flows and AI-assisted memory tools. | [Repo](https://github.com/e7naq3y/Memora_rokid) |
| `Rokid-DragonBallScouter` | `Glasses App` | Dragon Ball inspired scouter HUD with live face lock, pseudo-AR mode, and battle power reveal. | [Repo](https://github.com/Anezium/Rokid-DragonBallScouter) |
| `rokid-lc-hot100` | `Learning App` | Offline LeetCode Hot100 study assistant designed for Rokid AR glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-lc-hot100) |
| `rokid-mahjong-assistant` | `Glasses App` | Mahjong assistant adapted for Rokid AI glasses with camera recognition and AR suggestions. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-mahjong-assistant) |
| `rokid-music-score` | `Music Utility` | Piano score viewer packaged as an APK for Rokid RG-glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-music-score) |
| `cafeglasspoc` | `YodaOS-Sprite POC` | Hackathon barista recipe-guidance prototype for Rokid smart glasses, using USB-C screen mirroring, transparent black background, and touchpad/tap step navigation. | [Repo](https://github.com/leopaul29/cafeglasspoc) |
| `pua-simulator-glasses` | `Experience Prototype` | Multi-component Rokid glasses experience with first-person camera capture, cloud scene understanding, Dify agent orchestration, TTS/RTC voice interactions, and a companion web app. | [Repo](https://github.com/K-Drift/pua-simulator-glasses) |
| `RokidSearchHelper` | `Learning App` | Android companion app for Rokid AR glasses focused on question search workflows, with robust dual-mode Bluetooth handling on newer Android builds. | [Repo](https://github.com/zxy7906052/RokidSearchHelper) |
| `RokidGames` | `Glasses App` | Retro-style mini-game collection for Rokid Glasses with monochrome pixel art, touchpad controls, and head-tracked gameplay. | [Repo](https://github.com/ARDings/RokidGames) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🏪 Catalog apps by EUNG SOFT

20 apps from the [EUNG SOFT Rokid catalog](https://eung.pe.kr/rokid/).

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `EK Pilot` | `Game` | 3D flight mission game built around head-tilt controls. | [Details](https://eung.pe.kr/app-detail.html?app=ekpilot&type=RokidGlasses) |
| `EK Word Up` | `Learning App` | Hands-free vocabulary app for Rokid Glasses with shared study material support. | [Details](https://eung.pe.kr/app-detail.html?app=EKWordUp&type=RokidGlasses) |
| `TextHome` | `Launcher` | Simple text-first home launcher with wallpaper, clock, weather, battery, and text widgets. | [Details](https://eung.pe.kr/app-detail.html?app=TextHome&type=RokidGlasses) |
| `EKReader` | `Reader App` | Clean and intuitive e-book reader for Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=EKReader&type=RokidGlasses) |
| `EK Live Cam` | `Camera App` | Live streaming utility for the Rokid glasses camera. | [Details](https://eung.pe.kr/app-detail.html?app=EKLiveCam&type=RokidGlasses) |
| `EKHome` | `Launcher` | Custom home launcher app for Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=EKHome&type=RokidGlasses) |
| `Persona` | `Analysis App` | Face and palm reading app combining data-driven analysis with traditional references. | [Details](https://eung.pe.kr/app-detail.html?app=Persona&type=RokidGlasses) |
| `Rokid Connect HUD (Glasses)` | `Navigation HUD` | Glasses-side navigation HUD app for T Map and Naver Map. | [Details](https://eung.pe.kr/app-detail.html?app=RokidConnectHud2&type=RokidGlasses) |
| `Rokid Connect HUD (Phone)` | `Phone Companion` | Phone companion app for the Rokid Connect HUD navigation workflow. | [Details](https://eung.pe.kr/app-detail.html?app=RokidConnectHud&type=RokidGlasses) |
| `Text Translation` | `Translation App` | Offline English-Korean text translation app. | [Details](https://eung.pe.kr/app-detail.html?app=Trans&type=RokidGlasses) |
| `EK Zoom` | `Vision Utility` | Magnifier and telescope-style camera zoom app. | [Details](https://eung.pe.kr/app-detail.html?app=zoom&type=RokidGlasses) |
| `EK Arrow` | `Game` | Mini archery game for Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=EKArrow&type=RokidGlasses) |
| `EK Find Price` | `Shopping Utility` | Takes a photo and searches Naver for matching product prices. | [Details](https://eung.pe.kr/app-detail.html?app=EKFind&type=RokidGlasses) |
| `Matrix Vision` | `Camera Effect App` | Matrix-style visual filter app for Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=MatrixVision&type=RokidGlasses) |
| `DcimWebServer` | `File Utility` | Local DCIM web server for browsing or downloading captured media from Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=DcimWebServer&type=RokidGlasses) |
| `YourVoice` | `Voice Utility` | Voice-focused utility app for Rokid Glasses distributed through the EUNG catalog. | [Details](https://eung.pe.kr/app-detail.html?app=YourVoice&type=RokidGlasses) |
| `EK Meta Player` | `Web App Player` | Utility for running games and apps developed for Meta display on Rokid Glasses, with a built-in program list and QR-based custom app management. | [Details](https://eung.pe.kr/app-detail.html?app=EKMeta&type=RokidGlasses) |
| `EK Timer` | `Timer Utility` | Timer utility for Rokid Glasses distributed through the EUNG catalog. | [Details](https://eung.pe.kr/app-detail.html?app=EKTimer&type=RokidGlasses) |
| `EK Remover` | `Utility App` | Rokid Glasses utility app distributed through the EUNG catalog. | [Details](https://eung.pe.kr/app-detail.html?app=EKRemover&type=RokidGlasses) |
| `EKWeb / Dew Browser` | `Browser App` | Lightweight web browsing app for Rokid Glasses. | [Details](https://eung.pe.kr/app-detail.html?app=EKWeb&type=RokidGlasses) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🔌 Infra and bridges

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `HassGlass` | `Home Assistant Bridge` | Design-stage HACS integration that aims to turn Rokid AR Glasses into a local Home Assistant Assist voice and HUD satellite, with notifications, gesture events, and glasses entities. | [Repo](https://github.com/constructorfleet/HassGlass) |
| `meeting-helper-rokid` | `OpenClaw Bridge App` | Standalone Rokid AI Glasses meeting assistant that streams mic audio over WebSocket to an OpenClaw gateway for transcription, summaries, quick Q&A, and a minimal recording HUD. | [Repo](https://github.com/KeithHello/meeting-helper-rokid) |
| `openclaw-rokid-glasses` | `Server Bridge` | SSE bridge that adapts Rokid AI App requests to an OpenAI-compatible OpenClaw stack. | [Repo](https://github.com/yi-john-huang/openclaw-rokid-glasses) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🇨🇳 China / Lingzhu ecosystem

Projects built around the Chinese Rokid Lingzhu platform. These may not work on global Rokid devices or accounts without access to Lingzhu custom agents.

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `rokid-xiaozhi` | `CN / CXR-S App` | Chinese Xiaozhi AI voice conversation app for Rokid glasses, built with the Rokid CXR-S SDK and a cyberpunk matrix-style UI. | [Repo](https://github.com/mdloverm/rokid-xiaozhi) |
| `rokid-glasses-suite` | `CN / Lingzhu Suite` | Meta-suite for connecting Rokid Glasses and the Lingzhu platform to Home Assistant, OpenClaw, and Hermes/Rhasspy-style ecosystems. | [Repo](https://github.com/Hylouis233/rokid-glasses-suite) |
| `rokid-ha-control-kit` | `CN / Home Assistant Bridge` | Home Assistant control service for Rokid and Lingzhu SSE flows, with natural language control, entity allowlists, service allowlists, and audit logging. | [Repo](https://github.com/Hylouis233/rokid-ha-control-kit) |
| `rokid-lingzhu-openclaw` | `CN / OpenClaw Bridge` | Lingzhu-to-OpenClaw plugin that converts Lingzhu SSE requests into OpenClaw Chat Completions and streams responses back to the glasses. | [Repo](https://github.com/Hylouis233/rokid-lingzhu-openclaw) |
| `rokid-hermes-connector` | `CN / Hermes Bridge` | Bridge from Rokid Glasses and Lingzhu SSE input to Home Assistant Conversation or Hermes/Rhasspy MQTT intent payloads. | [Repo](https://github.com/Hylouis233/rokid-hermes-connector) |
| `rokid-hermes-bridge` | `CN / Hermes Bridge` | Bridge that connects Rokid AR glasses through the Lingzhu/Rizon SSE platform to a local Hermes Agent gateway, with voice dialogue, image input, context memory, and Cloudflare Tunnel deployment notes. | [Repo](https://github.com/xingdongcai/rokid-hermes-bridge) |
| `fuluk-lingzhu` | `CN / Session Gateway Bridge` | Middleware that exposes Rokid Lingzhu custom-agent SSE and forwards voice/text requests to Fuluk Gateway's unified natural-language session API. | [Repo](https://github.com/springycloveting/fuluk-lingzhu) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 🧰 Templates and demos

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `GlassKit` | `Dev Suite` | Open-source Rokid-first dev suite for building real-time, vision-enabled smart glasses apps. | [Repo](https://github.com/RealComputer/GlassKit) |
| `GlassKit - Rokid Feature Demo` | `Example App` | Feature and control-pattern demo for Rokid Glasses, including voice commands and emulator-friendly input mapping. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-feature-demo) |
| `GlassKit - Rokid OpenAI Realtime` | `Example App` | Vision-enabled voice assistant demo for Rokid Glasses using the OpenAI Realtime API over WebRTC. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-openai-realtime) |
| `GlassKit - Rokid OpenAI Realtime + RF-DETR` | `Example App` | Rokid voice assistant demo that adds backend RF-DETR object detection for stronger visual understanding. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-openai-realtime-rfdetr) |
| `GlassKit - Rokid Overshoot` | `Example App` | Live scene-description HUD for Rokid Glasses that streams camera video to Overshoot and displays inference text. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-overshoot) |
| `GlassKit - Drink-making Coach` | `Example App` | Proactive Rokid Glasses assistant that combines Overshoot and OpenAI Realtime for drink-making guidance. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-overshoot-openai-realtime) |
| `GlassKit - RF-DETR Speedrun HUD` | `Example App` | Object-detection speedrun HUD for Rokid Glasses with hands-free split timing and backend RF-DETR inference. | [Folder](https://github.com/RealComputer/GlassKit/tree/main/examples/rokid-rfdetr) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

### 📚 Developer resources

| Project | Type | What it does | Link |
| --- | --- | --- | --- |
| `EUNG SOFT Web Install` | `Web Installer` | Browser-based WebUSB installer for APK sideloading, plus file upload helpers for apps like EK Reader, TextHome, and EK Word Up. | [Site](https://eung.pe.kr/web-install/) |
| `client-glasses` | `OS / Firmware Tooling` | Rokid AR glasses OS and firmware tooling with Android services, capture/file sync, tracing, power and touchpad daemons, wake-word assets, and rooted firmware build scripts. | [Repo](https://github.com/jaskier-os/client-glasses) |
| `client-phone` | `Phone Companion Tooling` | Companion Android app for the glasses + phone assistant stack, handling Bluetooth relay, backend WebSocket orchestration, chat, notifications, navigation, and WebRTC audio. | [Repo](https://github.com/jaskier-os/client-phone) |
| `RokidAIGlassesUnityBridge` | `Unity Plugin` | Unity Android plugin wrapping Rokid CXR-L `client-l` so phone-based Unity apps can authenticate through Rokid AI App, capture glasses photo/audio streams, and drive CustomView UI. | [Repo](https://github.com/ARDings/RokidAIGlassesUnityBridge) |
| `rokid-glasses-analysis` | `Research Docs` | System analysis and reverse-engineering notes for Rokid AI glasses. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-glasses-analysis) |
| `rokid-glasses-control` | `Control Tool` | ADB + scrcpy tooling to view and control Rokid AI glasses from macOS. | [Folder](https://github.com/bcefghj/rokid-collection/tree/main/rokid-glasses-control) |
| `rokid-private-tts-kit` | `Android Library` | Reusable Android client for the private Rokid Glasses TTS binder, with a minimal sample app for bind, speak, and stop checks. | [Repo](https://github.com/bzerk/rokid-private-tts-kit) |
| `rokid-docs` | `Documentation` | Community-maintained Rokid development docs covering SDKs, internals, hardware notes, and reverse-engineered references. | [Repo](https://github.com/buildwithfenna/rokid-docs) |

<p align="right"><a href="#table-of-contents">⬆ back to top</a></p>

---

## ✏️ Add your project

Pull requests are welcome. If you built something for Rokid glasses, open a PR and add a row to the relevant section.

**Format:**

```md
| `Project Name` | `Type` | One short sentence explaining what it does. | [Repo](https://github.com/you/project) |
```

**Bonus points if your repo includes:**

- screenshots or short demo videos
- install instructions
- APK release artifacts when possible
- device compatibility notes

---

## Missing something?

If you know a Rokid project that belongs here and it is not listed yet:

1. open a pull request
2. or open an issue with the repo link

The goal is simple: make `awesome-rokid` the best starting point for exploring the Rokid app ecosystem.
