<!--lint disable awesome-heading awesome-toc awesome-github double-link -->

<div align="center">
<h1>Awesome Tauri</h1>

A curated collection of the best stuff from the Tauri ecosystem and community.

<br />

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

</div>

## Table of Contents

- [Getting Started](#getting-started)
  - [Guides](#guides)
  - [Tutorials](#tutorials)
  - [Templates](#templates)
- [Development](#development)
  - [Plugins](#plugins)
  - [Integrations](#integrations)
  - [Articles](#articles)
- [Applications](#applications)
  - [Audio & Video](#audio--video)
  - [ChatGPT clients](#chatgpt-clients)
  - [Data](#data)
  - [Developer tools](#developer-tools)
  - [Email & Feeds](#email--feeds)
  - [File management](#file-management)
  - [Finance](#finance)
  - [Gaming](#gaming)
  - [Information](#information)
  - [Learning](#learning)
  - [Networking](#networking)
  - [Office & Writing](#office--writing)
  - [Productivity](#productivity)
  - [Search](#search)
  - [Security](#security)
  - [Social media](#social-media)
  - [Utilities](#utilities)

## Getting Started

### Guides

- [Introduction](https://tauri.app/about/intro/) ![officially maintained] - Official introduction to Tauri.
- [Getting Started](https://tauri.app/v1/guides/getting-started/prerequisites/) ![officially maintained] - Official getting started with Tauri docs.
- [create-tauri-app](https://github.com/tauri-apps/create-tauri-app) ![officially maintained] - Rapidly scaffold your Tauri app.

### Tutorials

- [Create Tauri App with React](https://www.youtube.com/watch?v=zawhqLA7N9Y&ab_channel=chrisbiscardi) - Chris Biscardi shows how easy it is to wire up a Rust crate with a JS module and communicate between them.
- [Publish to Apple's App Store](https://thinkgo.io/post/2023/02/publish_tauri_to_apples_app_store/) - Details all the steps needed to publish your Mac app to the app store. Includes a sample bash script.
- [Tauri & ReactJS - Creating Modern Desktop Apps](https://youtube.com/playlist?list=PLmWYh0f8jKSjt9VC5sq2T3mFETasG2p2L) - Creating a modern desktop application with Tauri.

### Templates

- [angular-tauri](https://github.com/maximegris/angular-tauri) - Angular with Typescript, SASS, and Hot Reload.
- [tauri-angular-template](https://github.com/charlesxsh/tauri-angular-boilerplate) - Angular template
- [tauri-astro-template](https://github.com/HuakunShen/tauri-astro-template) - Astro template
- [tauri-clojurescript-template](https://github.com/rome-user/tauri-clojurescript-template) - Minimal ClojureScript template with Shadow CLJS and React.
- [tauri-deno-starter](https://github.com/marc2332/tauri-deno-starter) - React template using esbuild with Deno.
- [tauri-leptos-template](https://gitlab.com/cristofa/tauri-leptos-template) - Leptos template
- [tauri-nextjs-template](https://github.com/kvnxiao/tauri-nextjs-template) - Next.js (SSG) template, with TailwindCSS, opinionated linting, and GitHub Actions preconfigured.
- [tauri-nuxt-template](https://github.com/HuakunShen/tauri-nuxt-template) - Nuxt3 template.
- [tauri-preact-rsbuild-template](https://github.com/Alfredoes234/tauri-preact-rsbuild-template) - Preact template that uses rsbuild, rather than vite.
- [tauri-react-mantine-vite-template](https://github.com/elibroftw/modern-desktop-app-template) - React Mantine template featuring custom titlebar for Windows, auto publish action, auto update, and more.
- [tauri-react-parcel-template](https://github.com/henrhie/tauri-react-parcel-template) - React template with Parcel as build tool, TypeScript and hot module replacement.
- [tauri-rescript-template](https://github.com/JonasKruckenberg/tauri-rescript-template) - Tauri, ReScript, and React template.
- [tauri-solid-ts-tailwind-vite-template](https://github.com/AR10Dev/tauri-solid-ts-tailwind-vite) - SolidJS Template preconfigured to use Vite, TypeScript, Tailwind CSS, ESLint and Prettier.
- [tauri-svelte-template](https://github.com/probablykasper/tauri-svelte-template) - Svelte template with cross-platform GitHub action builds, Vite, TypeScript, Svelte Preprocess, hot module replacement, ESLint and Prettier.
- [tauri-sveltekit-template](https://github.com/deid84/tauri-sveltekit-admin-template) - SvelteKit Admin template with cross-platform GitHub action builds, Vite, TypeScript, Svelte Preprocess, hot module replacement, ESLint and Prettier.
- [tauri-sycamore-template](https://github.com/JonasKruckenberg/tauri-sycamore-template) - Tauri and Sycamore template.
- [tauri-vue-template](https://github.com/Uninen/tauri-vue-template) - Vue template with TypeScript, Vite + HMR, Vitest, Tailwind CSS, ESLint, and GitHub Actions.
- [tauri-vue-template-2](https://github.com/skymen/tauri-vue-template) - Another vue template with Javascript, Vite, Pinia, Vue Router and Github Actions.
- [tauri-yew-example](https://bitbucket.org/ftegtmeyer/tauri-yew-stopwatch/) - Simple stopwatch with Yew using commands and Tauri events.

## Development

### Plugins

- [tauri-plugin-authenticator](https://github.com/tauri-apps/tauri-plugin-authenticator) ![officially maintained] - Interface with hardware security keys.
- [tauri-plugin-log](https://github.com/tauri-apps/tauri-plugin-log) ![officially maintained] - Configurable logging.
- [tauri-plugin-sql](https://github.com/tauri-apps/tauri-plugin-sql) ![officially maintained] - Interface with SQL databases.
- [tauri-plugin-store](https://github.com/tauri-apps/tauri-plugin-store) ![officially maintained] - Persistent key value storage.
- [tauri-plugin-stronghold](https://github.com/tauri-apps/tauri-plugin-stronghold) ![officially maintained] - Encrypted, secure, p2p database.
- [tauri-plugin-window-state](https://github.com/tauri-apps/tauri-plugin-window-state) ![officially maintained] - Persist window sizes and positions.
- [window-vibrancy](https://github.com/tauri-apps/window-vibrancy) ![officially maintained] - Make your windows vibrant.
- [window-shadows](https://github.com/tauri-apps/window-shadows) ![officially maintained] - Add native shadows to your windows.
- [tauri-plugin-positioner](https://github.com/JonasKruckenberg/tauri-plugin-positioner) - Move windows to common locations.
- [tauri-plugin-graphql](https://github.com/JonasKruckenberg/tauri-plugin-graphql) - Type-safe IPC for Tauri using GraphQL.
- [sentry-tauri](https://github.com/timfish/sentry-tauri) - Capture JavaScript errors, Rust panics and native crash minidumps to Sentry.
- [tauri-plugin-aptabase](https://github.com/aptabase/tauri-plugin-aptabase) - Privacy-first and minimalist analytics for desktop and mobile apps.
- [tauri-plugin-clipboard](https://github.com/CrossCopy/tauri-plugin-clipboard) - Clipboard plugin for reading/writing clipboard text/image, and monitoring clipboard update.
- [taurpc](https://github.com/MatsDK/TauRPC) - Typesafe IPC wrapper for Tauri commands and events.
- [tauri-plugin-context-menu](https://github.com/c2r0b/tauri-plugin-context-menu) - Native context menu.
- [tauri-plugin-network](https://github.com/HuakunShen/tauri-plugin-network) - Tools for reading network information and scanning network.
- [tauri-plugin-serialport](https://github.com/deid84/tauri-plugin-serialport) - Cross-compatible serialport communication tool.
- [tauri-plugin-system-info](https://github.com/HuakunShen/tauri-plugin-system-info) - Detailed system information.
- [tauri-plugin-theme](https://github.com/wyhaya/tauri-plugin-theme) - Dynamically change Tauri App theme.
- [tauri-awesome-rpc](https://github.com/ahkohd/tauri-awesome-rpc) - Custom invoke system that leverages WebSocket.
- [tauri-nspanel](https://github.com/ahkohd/tauri-nspanel) - Convert a window to panel.
- [tauri-plugin-nosleep](https://github.com/pevers/tauri-plugin-nosleep/) - Block the power save functionality in the OS.

### Integrations

- [Astrodon](https://github.com/astrodon/astrodon) - Make Tauri desktop apps with Deno.
- [Tauri Specta](https://github.com/oscartbeaumont/tauri-specta) - Completely typesafe Tauri commands.
- [axios-tauri-adapter](https://git.kaki87.net/KaKi87/axios-tauri-adapter) - `axios` adapter for the `@tauri-apps/api/http` module.
- [axios-tauri-api-adapter](https://github.com/persiliao/axios-tauri-api-adapter) - Makes it easy to use Axios in Tauri, `axios` adapter for the `@tauri-apps/api/http` module.
- [ngx-tauri](https://codeberg.org/crapsilon/ngx-tauri) - Small lib to wrap around functions from tauri modules, to integrate easier with Angular.
- [svelte-tauri-filedrop](https://github.com/probablykasper/svelte-tauri-filedrop) - File drop handling component for Svelte.
- [tauri-macos-menubar-app-example](https://github.com/ahkohd/tauri-macos-menubar-app-example) - Example macOS Menubar app project.
- [tauri-macos-spotlight-example](https://github.com/ahkohd/tauri-macos-spotlight-example) - Example macOS Spotlight app project.
- [tauri-update-cloudflare](https://github.com/KilleenCode/tauri-update-cloudflare) - One-click deploy a Tauri Update Server to Cloudflare.
- [tauri-update-server](https://git.kaki87.net/KaKi87/tauri-update-server) - Automatically interface the Tauri updater with git repository releases.
- [vite-plugin-tauri](https://github.com/amrbashir/vite-plugin-tauri) - Integrate Tauri in a Vite project to build cross-platform apps.

### Articles

- [Getting Started Using Tauri Mobile](https://medium.com/p/6f90de5b098) ![paid] - Ed Rutherford outlines how to create a mobile app with Tauri.
- [How to use local SQLite database with Tauri and Rust](https://blog.moonguard.dev/how-to-use-local-sqlite-database-with-tauri) - Guide to setup and use SQLite database with Tauri and Rust.
- [Managing State in Desktop Applications with Rust and Tauri](https://blog.moonguard.dev/manage-state-with-tauri) - How to share and manage any kind of state globally in Tauri apps.
- [Setting up Actix Web in a Tauri App](https://blog.moonguard.dev/setting-up-actix-in-tauri) - How to setup a HTTP server with Tauri and Actix Web.
- [Tauri's async process](https://rfdonnelly.github.io/posts/tauri-async-rust-process/) - Rob Donnelly dives deep into Async with Tauri.

## Applications

### Audio & Video

- [Cider](https://cider.sh) ![closed source] - 3rd Party Client for Apple Music, Complete with Audio Lab.
- [Curses](https://github.com/mmpneo/curses) - Speech-to-Text and Text-to-Speech captions for OBS, VRChat, Twitch chat and more.
- [Douyin Downloader](https://github.com/lzdyes/douyin-downloader) - Cross-platform douyin video downloader.
- [Feiyu Player](https://github.com/idootop/feiyu-player) - Cross-platform online video player where beauty meets functionality.
- [Hypetrigger](https://hypetrigger.io/) ![closed source] - Detect highlight clips in video with FFMPEG + Tensorflow on the GPU.
- [Jellyfin Vue](https://github.com/jellyfin/jellyfin-vue) - GUI client for a Jellyfin server based on Vue.js and Tauri.
- [mediarepo](https://github.com/Trivernis/mediarepo) - Tag-based media management application.
- [Mr Tagger](https://github.com/probablykasper/mr-tagger) - Music file tagging app.
- [Lofi Engine](https://github.com/meel-hd/lofi-engine) - Generate Lo-Fi music on the go and locally.
- [XGetter](https://github.com/xgetter-team/xgetter) ![closed source]- Cross-platform GUI to download videos and audio from Youtube, Facebook, X(Twitter), Instagram, Tiktok and more.
- [yt-dlp GUI](https://github.com/gaeljacquin/yt-dlp-gui) - Cross-platform GUI client for the `yt-dlp` command-line audio/video downloader.

### ChatGPT clients

- [chatbox](https://github.com/Bin-Huang/chatbox) - Cross-platform desktop application for ChatGPT API (OpenAI API), also a prompt debugging and management tool.
- [ChatGPT](https://github.com/lencx/ChatGPT) - Cross-platform ChatGPT desktop application.
- [ChatGPT App](https://github.com/Poordeveloper/chatgpt-app) - Cross-platform ChatGPT App and more.
- [ChatGPT-Desktop](https://github.com/Synaptrix/ChatGPT-Desktop) - Cross-platform productivity ChatGPT assistant launcher.
- [Orion](https://github.com/taecontrol/orion) - Cross-platform app that lets you create multiple AI assistants with specific goals powered with ChatGPT.
- [QuickGPT](https://github.com/dubisdev/quickgpt) - Lightweight AI assistant for Windows.
- [Yack](https://github.com/rajatkulkarni95/yack) - Spotlight like app for interfacing with GPT APIs

### Data

- [BS Redis Desktop Client](https://github.com/fuyoo/bs-redis-desktop-client) - The Best Surprise Redis Desktop Client.
- [Dataflare](https://dataflare.app) ![closed source] ![paid] - Simple and elegant database manager.
- [Duckling](https://github.com/l1xnan/duckling) - Lightweight and fast viewer for csv/parquet files and databases such as DuckDB, SQLite, PostgreSQL, MySQL, Clickhouse, etc.
- [Mason](https://mason.app) ![closed source] - Seamlessly query, visualize and share data with your team.
- [Noir](https://noirdb.dev) - Keyboard-driven database management client.
- [pgMagic🪄](https://pgmagic.app/?ref=awesometauri) ![closed source] ![paid] - GUI client to talk to Postgres in SQL or with natural language.

### Developer tools

- [AHQ Store](https://github.com/ahqsoftwares/tauri-ahq-store) - Publish, Update and Install apps to the Windows-specific AHQ Store.
- [AppCenter Companion](https://github.com/zenoxs/tauri-appcenter-companion) - Regroup, build and track your `VS App Center` apps.
- [AppHub](https://github.com/francesco-gaglione/AppHub) - Streamlines .appImage package installation, management, and uninstallation through an intuitive Linux desktop interface.
- [Aptakube](https://aptakube.com/) ![closed source] - Multi-cluster Kubernetes UI.
- [claws](https://clawsapp.com/) ![closed source] - Visual interface for the AWS CLI.
- [CrabNebula DevTools](https://crabnebula.dev/devtools) - Visual tool for understanding your app. Optimize the development process with easy debugging and profiling.
- [CrabNebula DevTools Premium](https://crabnebula.dev/devtools) ![closed source] ![paid] - Optimize the development process with easy debugging and profiling. Debug the Rust portion of your app with the same comfort as JavaScript!
- [DevBox](https://www.dev-box.app/) ![closed source] - Many useful tools for developers, like generators, viewers, converters, etc.
- [DevClean](https://github.com/HuakunShen/devclean) - Clean up development environment with ease.
- [DevTools-X](https://github.com/fosslife/devtools-x) - Collection of 30+ cross platform development utilities.
- [Dropcode](https://github.com/egoist/dropcode) - Simple and lightweight code snippet manager.
- [Echoo](https://github.com/zsmatrix62/echoo-app) - Offline/Online utilities for developers on MacOS & Windows.
- [GitButler](https://gitbutler.com) - GitButler is a new Source Code Management system.
- [GitLight](https://github.com/colinlienard/gitlight) - GitHub & GitLab notifications on your desktop.
- [JET Pilot](https://www.jet-pilot.app) - Kubernetes desktop client that focuses on less clutter, speed and good looks.
- [Hoppscotch](https://hoppscotch.com/download) ![closed source] - Trusted by millions of developers to build, test and share APIs.
- [Keadex Mina](https://github.com/keadex/keadex) - Open Source, serverless IDE to easily code and organize at a scale C4 model diagrams.
- [KFtray](https://github.com/hcavarsan/kftray) - A tray application that manages port forwarding in Kubernetes.
- [Soda](https://github.com/Web3-Builders-Alliance/soda) - Generate source code from an IDL.
- [Pake](https://github.com/tw93/Pake) - Turn any webpage into a desktop app with Rust with ease.
- [Rivet](https://github.com/Ironclad/rivet) - Visual programming environment for creating AI features and agents.
- [TableX](https://tablex-tan.vercel.app/) - Table viewer for modern developers
- [Tauri Mobile Test](https://github.com/dedSyn4ps3/tauri-mobile-test) - Create and build cross-platform mobile applications.
- [Testfully](https://testfully.io/) ![closed source] ![paid] - Offline API Client & Testing tool.
- [verbcode](https://www.verbcode.com) ![closed source] ![paid] - Simplify your localization journey.
- [Yaak](https://yaak.app) ![closed source] - Interact with REST and GraphQL APIs.

### Email & Feeds

- [Alduin](https://alduin.stouder.io/) - Alduin is a free and open source RSS, Atom and JSON feed reader that allows you to keep track of your favorite websites.
- [Aleph](https://github.com/chezhe/aleph) - Aleph is an RSS reader & podcast client.
- [BULKUS](https://github.com/KM8Oz/BULKUS) - Email validation software.
- [Lettura](https://github.com/zhanglun/lettura) - Open-source feed reader for macOS.
- [mdsilo Desktop](https://github.com/mdSilo/mdSilo-app) - Feed reader and knowledge base.

### File management

- [enassi](https://github.com/enassi/enassi) - Encryption assistant that encrypts and stores your notes and files.
- [EzUp](https://github.com/HuakunShen/ezup) - File and Image uploader. Designed for blog writing and note taking.
- [Orange](https://github.com/naaive/orange) - Cross-platform file search engine that can quickly locate files or folders based on keywords.
- [Payload](https://payload.app/) ![closed source] - Drag & drop file transfers over local networks.
- [Spacedrive](https://github.com/spacedriveapp/spacedrive) - A file explorer from the future.
- [SquirrelDisk](https://github.com/adileo/squirreldisk) - Beautiful cross-platform disk usage analysis tool.
- [Time Machine Inspector](https://github.com/probablykasper/time-machine-inspector) - Find out what's taking up your Time Machine backup space.
- [Xplorer](https://github.com/kimlimjustin/xplorer) - Customizable, modern and cross-platform File Explorer.

### Finance

- [Compotes](https://github.com/Orbitale/Compotes) - Local bank account operations storage to vizualize them as graphs and customize them with rules and tags for better filtering.
- [CryptoBal](https://github.com/Rabbit-Company/CryptoBal-Desktop) - Desktop application for monitoring your crypto assets.
- [Ghorbu Wallet](https://github.com/matthias-wright/ghorbu-wallet) - Cross-platform desktop HD wallet for Bitcoin.
- [nym-wallet](https://github.com/nymtech/nym/tree/develop/nym-wallet) - The Nym desktop wallet enables you to use the Nym network and take advantage of its key capabilities.
- [UsTaxes](https://github.com/ustaxes/ustaxes) - Free, private, open-source US tax filings.

### Gaming

- [9Launcher](https://github.com/wearrrrr/9Launcher) - Modern Cross-platform launcher for Touhou Project Games.
- [BestCraft](https://github.com/Tnze/ffxiv-best-craft) - Crafting simulator with solver algorithms for Final Fantasy XIV(FF14).
- [BetterFleet](https://github.com/zelytra/BetterFleet) - Help players of Sea of Thieves create an alliance server.
- [clear](https://clear.adithya.zip) - Clean and minimalist video game library manager and launcher.
- [CubeShuffle](https://github.com/philipborg/CubeShuffle) - Card game shuffling utility.
- [En Croissant](https://github.com/franciscoBSalgueiro/en-croissant) - Chess database and game analysis app.
- [FishLauncher](https://github.com/fishfight/FishLauncher) - Cross-platform launcher for `Fish Fight`.
- [OpenGOAL](https://github.com/open-goal/launcher) - Cross-platform installer, mod-manager and launcher for `OpenGOAL`; the reverse engineered PC ports of the Jak and Daxter series.
- [OyasumiVR](https://github.com/Raphiiko/OyasumiVR) - Software that helps you sleep in virtual reality, for use with SteamVR, VRChat, and more.
- [Resolute](https://github.com/Gawdl3y/Resolute) - User-friendly, cross-platform mod manager for the game Resonite.
- [Steam Art Manager](https://github.com/Tormak9970/Steam-Art-Manager) - Tool for customizing the art of your Steam games.
- [Teyvat Guide](https://github.com/BTMuli/TeyvatGuide) - Game Tool for Genshin Impact player.

### Information

- [Seismic](https://github.com/breadthe/seismic) - Taskbar app for USGS earthquake tracking.
- [Stockman](https://github.com/awkj/stockman) - Display stock info on mac menubar.
- [Watchcoin](https://github.com/lifecoder1988/tauri-watch-coin) - Display cypto price on OS menubar without a window.

### Learning

- [Manjaro Starter](https://github.com/oguzkaganeren/manjaro-starter) - Documentation and support app for new Manjaro users.
- [Piano Trainer](https://github.com/ZaneH/piano-trainer) - Practice piano chords, scales, and more using your MIDI keyboard.
- [Solars](https://github.com/hiltontj/solars) - Visualize the planets of our solar system.
- [Syre](https://github.com/syre-data/syre) - Scientific data assistant.

### Networking

- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) - Continuation of Clash Verge, a rule-based proxy.
- [CyberAPI](https://github.com/vicanso/cyberapi) - API tool client for developer.
- [Jexpe](https://github.com/jexpe-apps/jexpe) - Cross-platform, open source SSH and SFTP client that makes connecting to your remote servers easy.
- [Mail-Dev](https://github.com/samirdjelal/mail-dev) - Cross-platform, local SMTP server for email testing/debugging.
- [Nhex](https://github.com/nhexirc/nhex) - Next-generation IRC client inspired by HexChat.
- [RustDesk](https://github.com/rustdesk/rustdesk-server) - Self-hosted server for RustDesk, an open source remote desktop.
- [RustDuck](https://github.com/thewh1teagle/RustDuck) - Cross platform dynamic DNS updater for duckdns.org.
- [T-Shell](https://github.com/TheBlindM/T-Shell) - An open-source SSH, SFTP intelligent command line terminal application.
- [TunnlTo](https://github.com/TunnlTo/desktop-app) - Windows WireGuard VPN client built for split tunneling.
- [UpVPN](https://github.com/upvpn/upvpn-app) - WireGuard VPN client for Linux, macOS, and Windows.
- [Watcher](https://github.com/windht/watcher) - API manager built for a easier use to manage and collaborate.
- [Wirefish](https://github.com/stefanodevenuto/wirefish) - Cross-platform packet sniffer and analyzer.

### Office & Writing

- [Bidirectional](https://github.com/samirdjelal/bidirectional) - Write Arabic text in apps that don't support bidirectional text.
- [Blank](https://github.com/FPurchess/blank) - Minimalistic, opinionated markdown editor made for writing.
- [Ensō](https://enso.sonnet.io) ![closed source] - Write now, edit later. Ensō is a writing tool that helps you enter a state of flow.
- [Handwriting keyboard](https://github.com/BigIskander/Handwriting-keyboard-for-Linux-tesseract) - Handwriting keyboard for Linux X11 desktop environment.
- [JournalV](https://github.com/ahmedkapro/journalv) - Journaling app for your days and dreams.
- [MarkFlowy](https://github.com/drl990114/MarkFlowy) - Modern markdown editor application with built-in ChatGPT extension.
- [MDX Editor](https://github.com/maqi1520/mdx-editor/tree/tauri-app) - Versatile WeChat typesetting editor and cross-platform Markdown note-taking software.
- [Noor](https://noor.to/) ![closed source] - Chat app for high-performance teams. Designed for uninterrupted deep work and rapid collaboration.
- [Notedown](https://github.com/ruralad/notedown) - Minimal, local-first cross-platform note taking app.
- [Parchment](https://github.com/tywil04/parchment) - Simple local-only cross-platform text editor with basic markdown support.
- [Semanmeter](https://yibiao.fun/) ![closed source] - OCR and document conversion software.
- [Ubiquity](https://github.com/opensourcecheemsburgers/ubiquity) - Cross-platform markdown editor; built with Yew, Tailwind, and DaisyUI.

### Productivity

- [Banban](https://github.com/HubertK05/banban) - Kanban board with tags, categories and markdown support.
- [BuildLog](https://github.com/rajatkulkarni95/buildlog) - Menu bar for keeping track of Vercel Deployments.
- [Dalgona](https://github.com/GHGHGHKO/dalgona) - GIF meme finder app for Windows and macOS.
- [GitBar](https://github.com/mikaelkristiansson/gitbar) - System tray app for GitHub reviews.
- [Gitification](https://github.com/Gitification-App/gitification) - Menu bar app for managing Github notifications.
- [Google Task Desktop Client](https://github.com/codad5/google-task-tauri) - Google Task Desktop Client
- [Jarvis](https://jarvis.huakun.tech/) - Cross-platform, extensible app launcher. Alternative to Alfred and Raycast.
- [Kanri](https://github.com/trobonox/kanri) - Cross-platform, offline-first Kanban board app with a focus on simplicity and user experience.
- [Kianalol](https://github.com/zxh3/kianalol) - Spotlight-like efficiency tool for swift website access.
- [Link Saas](https://github.com/linksaas/desktop) - Efficiency tools for software development teams.
- [MacroGraph](https://github.com/Brendonovich/macrograph) - Visual programming for content creators.
- [Obliqoro](https://github.com/mrjackwills/obliqoro) - Oblique Strategies meets Pomodoro.
- [Pomodoro](https://github.com/g07cha/pomodoro) - Time management tool based on Pomodoro technique.
- [Remind Me Again](https://github.com/probablykasper/remind-me-again) - Toggleable reminders app for Mac, Linux and Windows.
- [TimeChunks](https://danielulrich.com/en/timechunks/) ![closed source] - Time tracking for freelancers without timers and HH:MM:SS inputs.
- [WindowPet](https://github.com/SeakMengs/WindowPet) - Overlay app that lets you have adorable companions such as pets and anime characters on your screen.
- [Zawee](https://zawee.net) ![closed source] - Experience the synergy of Kanban boards, note-taking, file sharing, and more, seamlessly integrated into one powerful application.

### Search

- [Harana](https://github.com/harana/search) - Search your desktop and 300+ cloud apps, instantly.
- [Spyglass](https://github.com/a5huynh/spyglass) - Personal search engine that indexes your files/folders, cloud accounts, and whatever interests you on the internet.

### Security

- [Authme](https://github.com/Levminer/authme) - Two-factor (2FA) authentication app for desktop.
- [Calciumdibromid](https://codeberg.org/Calciumdibromid/CaBr2) - Generate "experiment wise safety sheets" in compliance to European law.
- [Gluhny](https://github.com/angeldollface/gluhny) A graphical interface to validate IMEI numbers.
- [OneKeePass](https://github.com/OneKeePass/desktop) - Secure, modern, cross-platform and KeePass compatible password manager.
- [Padloc](https://github.com/padloc/padloc) - Modern, open source password manager for individuals and teams.
- [Raspirus](https://github.com/Raspirus/Raspirus) - User- and resources-friendly signatures-based malware scanner.
- [Secops](https://github.com/kunalsin9h/secops) - Ubuntu Operating System security made easy.
- [Tauthy](https://github.com/pwltr/tauthy) - Cross-platform TOTP authentication client.

### Social media

- [Dorion](https://github.com/SpikeHD/Dorion) - Light weight third-party Discord client with support for plugins and themes.
- [Identia](https://github.com/iohzrd/identia) - Decentralized social media on IPFS.
- [Kadium](https://github.com/probablykasper/kadium) - App for staying on top of YouTube channel uploads.
- [Scraper Instagram GUI Desktop](https://git.kaki87.net/KaKi87/scraper-instagram-gui-desktop) - Alternative Instagram front-end for desktop.

### Utilities

- [AgeTimer](https://github.com/dhextras/age-timer-tauri) - Desktop utility that counts your age in real-time.
- [Auto Wallpaper](https://github.com/auto-wallpaper/auto-wallpaper) - Automatically generates 4K wallpapers based on user's location, weather, and time of day or any custom prompts.
- [bewCloud Desktop Sync](https://github.com/bewcloud/bewcloud-desktop) - Desktop sync app for bewCloud, a simpler alternative to Nextcloud and ownCloud.
- [Browsernaut](https://github.com/billyjacoby/browsernaut) - Browser picker for macOS.
- [Clipboard Record](https://github.com/lesterhnu/clipboard) - Record Clipboard Content.
- [Clippy](https://github.com/0-don/clippy) - Modern & Fast Clipboard Manager.
- [Fancy Screen Recorder](https://fancyapps.com/freebies/) ![closed source] - Record entire screen or a selected area, trim and save as a GIF or video.
- [Flying Carpet](https://github.com/spieglt/flyingcarpet) - File transfer between Android, iOS, Linux, macOS, and Windows over auto-configured hotspot.
- [Imagefly](https://www.imagefly.dev/?ref=awesometauri) ![closed source] - Powerful offline image processing toolkit for Windows, Linux and macOS
- [Jane Reader](https://janereader.com) ![closed source] - Modern and distraction-free epub reader.
- [KittyCAD](https://github.com/KittyCAD/modeling-app) - Modern 3D mechanical/hardware design. Build 3D models with both code and WYSIWYG editors.
- [KoS - Key on Screen](https://github.com/dubisdev/key-on-screen) - Show in your screen the keys you are pressing.
- [Lanaya](https://github.com/ChurchTao/Lanaya) - Easy to use, cross-platform clipboard management.
- [Linka!](https://github.com/linka-app/linka) - AI powered, easy to use, cross-platform bookmark management tool.
- [MBTiles Viewer](https://github.com/Akylas/mbview-rs) - MBTiles Viewer and Inspector.
- [Metronome](https://github.com/ZaneH/metronome) - Visual metronome for Windows, Linux and macOS.
- [Mobslide](https://github.com/thewh1teagle/mobslide) - Turn your smartphone into presentation remote controller.
- [Overlayed](https://overlayed.dev) - Voice chat overlay for Discord.
- [Pavo](https://github.com/zhanglun/pavo) - Cross-platform desktop wallpaper application.
- [Peekaboo](https://github.com/angeldollface/peekaboo) A graphical interface to display images.
- [Pointless](https://github.com/kkoomen/pointless) - Endless drawing canvas.
- [Pot](https://github.com/pot-app/pot-desktop) - Cross-platform Translation Software.
- [Rounded Corners](https://github.com/RoundedCorners/Application) - Rounded Corners app for Windows.
- [RunMath](https://github.com/dubisdev/runmath) - Keyboard-first calculator for Windows.
- [SensiMouse](https://github.com/Nicify/sensi-mouse) - Easily change macOS system-wide mouse sensitivity and acceleration settings.
- [Stable Diffusion Buddy](https://github.com/breadthe/sd-buddy) - Desktop UI companion for the self-hosted Mac version of Stable Diffusion.
- [Stacks](https://github.com/cablehead/stacks) - Modern and capable clipboard manager for macOS. Seeking Linux and Windows contributions.
- [Tauview](https://github.com/sprout2000/tauview) - Minimalist image viewer for macOS and Linux based on Leaflet.js.
- [ToeRings](https://github.com/acarl005/toerings) - Conky Seamod inspired system monitor app.
- [Toolcat](https://toolcat.app) ![closed source] - All-in-one toolkit for developers and creators.
- [TrguiNG](https://github.com/openscopeproject/TrguiNG) - Remote GUI for Transmission torrent daemon.
- [Verve](https://github.com/ParthJadhav/verve) - Launcher for accessing and opening applications, files and documents.
- [Vibe](https://thewh1teagle.github.io/vibe) - Transcribe audio or video in every language on every platform.
- [Wallpaper changer](https://github.com/zeet2020/wallpaper-changer-tauri) - Simple wallpaper changer app.
- [Zap](https://usezap.sh/?ref=awesometauri) ![closed source] - macOS spotlight-like dock that makes navigating apps convenient.

[officially maintained]: https://img.shields.io/badge/official-FFC131?&logo=tauri&logoColor=black
[closed source]: https://img.shields.io/badge/closed%20source-FFC131?&logoColor=black
[paid]: https://img.shields.io/badge/paid-FFC131?&logoColor=black
