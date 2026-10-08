<a href="https://ryanstoffel.dev">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" width="100%" alt="Ryan Stoffel">
</picture>
</a>

Software engineer focused on backend systems, infrastructure, and applied AI. I like building things end to end, from the environment a system runs in to the interface someone uses.

**Studying** &nbsp; B.S. Computer Science, AI/ML · Cal Baptist · May 2027<br>
**Recently** &nbsp; Software Engineer Intern, NSWC Corona<br>
**Based in** &nbsp; Corona, California

<a href="https://ryanstoffel.dev"><img src="./assets/buttons/portfolio.svg" alt="Portfolio"></a>
<a href="mailto:stoffel.thomas.ryan@gmail.com"><img src="./assets/buttons/email.svg" alt="Email me"></a>
<a href="https://www.linkedin.com/in/ryan-stoffel"><img src="./assets/buttons/linkedin.svg" alt="LinkedIn"></a>
<a href="https://ryanstoffel.dev/resume"><img src="./assets/buttons/resume.svg" alt="Resume"></a>

<br>

<a id="experience"></a>
<a href="#experience">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/headings/experience-dark.svg">
  <img src="./assets/headings/experience-light.svg" alt="Experience">
</picture>
</a>

### Software Engineer Intern

**Naval Surface Warfare Center, Corona Division** · Jun – Aug 2026

Built an AI operations assistant into a naval range scoring platform, a WPF/.NET desktop application in a DoD environment. Operators control range hardware from chat, and disruptive actions wait for human approval. The agent stack runs in Docker on a self-configuring NixOS gateway VM, and an offline installer deploys it to air-gapped sites.

<img src="./assets/experience/nswc-corona.webp" width="100%" alt="Summer 2026 at NSWC Corona: the flight deck of CVN 70, the intern cohort, a carrier tour, and the poster session">

`C#` `.NET` `WPF` `WebSockets` `NixOS` `Docker` `PostgreSQL`

### Software Engineer Research Assistant

**CBU AI & Machine Learning Lab** · May 2025 – Apr 2026

Cut recommendation latency from 60s to 3s on the DINA Matching Engine, a recommendation system for a production Salesforce org, by pairing a Python data pipeline with pgvector similarity search in PostgreSQL on GCP.

<img src="./assets/experience/dina-matching.webp" width="100%" alt="The DINA pipeline: Salesforce records flow through a Python extract, transform, embed, and load pipeline into PostgreSQL with pgvector on GCP">

`Python` `Salesforce` `Apex` `PostgreSQL` `pgvector` `GCP`

<br>

<a id="projects"></a>
<a href="#projects">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/headings/projects-dark.svg">
  <img src="./assets/headings/projects-light.svg" alt="Projects">
</picture>
</a>

What I'm building now. Each one links to its code.

### [Ember](https://github.com/cbu-capstone-design-27/ember)

**Senior capstone. Project memory for AI coding agents.** · Apr 2026 – now

<a href="https://github.com/cbu-capstone-design-27/ember"><img src="./assets/projects/ember.webp" width="100%" alt="Ember's knowledge graph: GitHub, Jira, and Slack feed pull requests, tickets, and decisions into a graph that a coding agent queries over MCP"></a>

A typed knowledge graph of why a codebase is the way it is: decisions, tickets, pull requests, and the people behind them. It fills itself from GitHub, Jira, Slack, Teams, and GitLab, and serves that context to coding agents through an MCP server. I own GitHub ingestion, the GitHub to Jira sync, and the retrieval pipeline. Graph retrieval matched embedding search accuracy with 35–45% fewer tokens.

`Python` `Neo4j AuraDB` `MCP` `GitHub Webhooks` `Jira REST API`

### [Formula Fly](https://github.com/cbu-machine-and-deep-learning-26/formula-fly)

**A race car driven by a fruit fly's visual system.** · Sep 2026 – now

<a href="https://github.com/cbu-machine-and-deep-learning-26/formula-fly"><img src="./assets/projects/formula-fly.webp" width="100%" alt="The Silverstone practice track with the car partway through lap one"></a>

A simulated driver whose eye is a model of the fruit fly optic lobe, wired from the real fly connectome. It trains on a MuJoCo practice track built from Silverstone's centerline. The question behind it: is fly wiring a useful prior for closed-loop control, or only a constraint?

`Python` `PyTorch` `MuJoCo` `NumPy` `flyvis`

### [Parallax](https://github.com/ryan-stoffel/parallax)

**Coding agents on computers you own.** · Sep 2026 – now

<a href="https://github.com/ryan-stoffel/parallax"><img src="./assets/projects/parallax.webp" width="100%" alt="A Parallax project: the coordinator's plan for a dry-run JSON flag on Tidy, with two subagent changes landed on the integration branch"></a>

An open-source desktop app for coordinator-and-subagent AI projects. A coordinator chat plans the work and hands pieces to subagents, each in its own git worktree. The work runs in plxd, a Rust daemon on your machine or a remote host over SSH, so a project keeps running with the laptop closed.

`Rust` `TypeScript` `Electron` `GitHub Actions` `Linear`

### [SnapDose](https://github.com/cbu-jr-design-26/snap-dose)

**Junior design project. Team lead.** · Jan – Apr 2026

<a href="https://github.com/cbu-jr-design-26/snap-dose"><img src="./assets/projects/snap-dose.webp" width="100%" alt="SnapDose screens: home dashboard, AI carb estimate, dose confirmation, and food gallery"></a>

Led a 5-person team building a Type 1 Diabetes management app. I architected the Java Spring Boot REST API on GCP Cloud Run with Firestore, behind a React Native client. It reads live glucose from the Dexcom CGM API, estimates carbs from a meal photo with Gemini, and sends bolus commands to an ESP32-P4 insulin pump simulator.

`Java` `Spring Boot` `React Native` `GCP Cloud Run` `Firestore` `Gemini` `ESP32-P4`

<br>

<a id="tools"></a>
<a href="#tools">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/headings/tools-dark.svg">
  <img src="./assets/headings/tools-light.svg" alt="Tools">
</picture>
</a>

Smaller software I build and use. The macOS apps install from my Homebrew tap.

<table>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/photon"><img src="./assets/tools/photon.webp" width="100%" alt="Photon's launcher suggesting apps"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/photon">Photon</a></b> · Swift
      <br>A fast, minimal launcher for apps, clipboard history, notes, file search, and window keybinds.</td>
  </tr>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/tidy"><img src="./assets/tools/tidy.webp" width="100%" alt="Tidy's app icon"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/tidy">Tidy</a></b> · Swift
      <br>Files your Desktop and Downloads by rule the moment files land.</td>
  </tr>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/caffeine"><img src="./assets/tools/caffeine.webp" width="100%" alt="Caffeine's app icon with an awake timer"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/caffeine">Caffeine</a></b> · Swift
      <br>Keeps the display awake from the menu bar, with a lid-closed mode and an awake timer.</td>
  </tr>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/hush"><img src="./assets/tools/hush.webp" width="100%" alt="Hush's recording pill with a live waveform"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/hush">Hush</a></b> · Swift · in progress
      <br>Hold a key, speak, release. On-device dictation into any app.</td>
  </tr>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/dotfiles"><img src="./assets/tools/dotfiles.webp" width="100%" alt="A dotfiles rebuild switching to a new generation"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/dotfiles">dotfiles</a></b> · Nix
      <br>This Mac as code: nix-darwin, Home Manager, and sops-encrypted secrets.</td>
  </tr>
  <tr>
    <td width="140"><a href="https://github.com/ryan-stoffel/bogey-busters"><img src="./assets/tools/bogey-busters.webp" width="100%" alt="Bogey Busters screens: hole GPS, scorecard, and nearby courses"></a></td>
    <td><b><a href="https://github.com/ryan-stoffel/bogey-busters">Bogey Busters</a></b> · Flutter
      <br>Golf tracking with GPS course navigation, live scoring, and a social feed.</td>
  </tr>
</table>
