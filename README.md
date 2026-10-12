# Awesome-Developer-IDE-Debugging

## Top Developer IDE Debugging Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cloud Development Environments, Remote IDE & Debugging Tools*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer IDE & Debugging**. These tools enable developers to code, debug, and collaborate from anywhere — from cloud-hosted development environments and browser-based IDEs to powerful local debuggers and remote debugging protocols.



**Examples** include Salesforce Developer Console, Visual Studio Code Online, GitHub Codespaces, JetBrains Fleet, Replit, Gitpod, Eclipse Theia, Codeanywhere, StackBlitz, and Sourcegraph (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom cloud IDEs, and open debugging infrastructure — ideal for developers, platform engineers, and teams seeking transparent, vendor-independent development environments.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Developer Console](https://developer.salesforce.com/)**  

  Browser-based IDE for Salesforce development with Apex debugging, SOQL queries, logs, and test execution. Integrated directly into Salesforce orgs.



- **[Visual Studio Code Online](https://vscode.dev/)**  

  Browser-based version of VS Code for lightweight code browsing and editing. Supports GitHub repos and limited extensions without local installation .



- **[GitHub Codespaces](https://github.com/features/codespaces)**  

  Cloud-hosted dev environments defined as code via Dev Containers. Instantly launches from any GitHub repo with terminal, extensions, and port forwarding .



- **[JetBrains Fleet](https://www.jetbrains.com/fleet/)**  

  Next-generation IDE from JetBrains with distributed architecture. Supports remote development, collaboration, and polyglot projects.



- **[Replit](https://replit.com/)**  

  Browser-based IDE with instant execution, hosting, and AI assistance. Popular for rapid prototyping, learning, and collaborative coding .



- **[Gitpod](https://www.gitpod.io/)**  

  Automated cloud dev environments for GitHub, GitLab, and Bitbucket. Ephemeral workspaces with prebuilds and team collaboration .



- **[Eclipse Theia](https://theia-ide.org/)**  

  Cloud & desktop IDE platform (open-core) with VS Code extension compatibility. Used by Google Cloud Shell, Arduino IDE 2.x, and others.



- **[Codeanywhere](https://codeanywhere.com/)**  

  Cloud IDE with prebuilt environments for multiple languages. Features collaboration, SSH access, and DevOps tooling.



- **[StackBlitz](https://stackblitz.com/)**  

  Browser-based IDE for web development with instant preview. Runs Node.js in-browser via WebContainers .



- **[Sourcegraph](https://sourcegraph.com/)**  

  Code intelligence platform with search, navigation, and batch changes across large codebases. Includes Cody AI assistant.



## Open-Source GitHub Projects



- **[OpenVSCode Server](https://github.com/gitpod-io/openvscode-server)**  

  Run VS Code on a remote server accessible via browser (MIT). Based on upstream VS Code with minimal modifications. Gitpod maintains and uses it as foundation for Gitpod .



- **[code-server](https://github.com/coder/code-server)**  

  Run VS Code on a remote server, accessible through the browser (MIT). Supports any machine with consistent dev environment. 60k+ GitHub stars.



- **[Eclipse Theia](https://github.com/eclipse-theia/theia)**  

  Open-source cloud & desktop IDE (EPL-2.0). Full VS Code extension compatibility, vendor-neutral, and customizable. Used by Google Cloud Shell, Arduino IDE 2.x .



- **[DevPod](https://github.com/loft-sh/devpod)**  

  Codespaces but open-source, client-only and unopinionated (MPL-2.0). Works with any IDE and lets you use any cloud, Kubernetes, or localhost Docker. 5,853+ GitHub stars .



- **[Daytona](https://github.com/daytonaio/daytona)**  

  Open-source dev environment manager (Apache-2.0). Single command transforms any VM into a secure, shareable, standardized development environment .



- **[Codebox](https://github.com/davidebianchi03/codebox)**  

  Self-hosted distributed provider of remote development environments (license varies). Define workspaces using Docker Compose or Devcontainers. Connect via SSH with VS Code extension support .



- **[Orchard CDE](https://github.com/orchard-cde/orchard)**  

  Open-source Cloud Development Environments (license varies). Devcontainer-native, VM-isolated, with VS Code Remote SSH and CLI. Includes Canopy UI for workspace management .



- **[Multi-Language IDE](https://github.com/KrishJani/Scalable-Multi-Language-IDE)**  

  Modern web-based IDE supporting Python, JavaScript, Java, C++, C, and Bash (license varies). Monaco Editor, Docker-based execution with timeout protection. Cloud deployment ready .



- **[Cloud IDE](https://github.com/munna-yadav/Cloud-IDE)**  

  Collaborative cloud IDE inspired by VS Code (license varies). React/TypeScript frontend, Socket.io for real-time collaboration, Monaco Editor, Docker sandbox for code execution .



- **[DNCDbg](https://github.com/viewizard/dncdbg)**  

  Managed-code debugger for .NET Core (MIT). Implements Debug Adapter Protocol (DAP) for VS Code and other DAP-compatible IDEs. 11.7M memory footprint vs 146.8M for VsDbg .



- **[Seer](https://github.com/epasveer/seer)**  

  GUI frontend to GDB (GPL-3.0). 2,056+ GitHub stars. Provides visual debugging for C/C++ with breakpoints, watches, and stack traces .



- **[GDBFrontend](https://github.com/rohanrhu/gdb-frontend)**  

  Easy, flexible, extensible GUI debugger (MIT). 2,911+ GitHub stars. Web-based debugging interface for GDB .



- **[dap-buddy.nvim](https://github.com/pocco81/dap-buddy.nvim)**  

  Debug Adapter Protocol manager for Neovim (MIT). 400+ GitHub stars. Simplifies DAP configuration for multiple languages .



### Additional Strong Open-Source Options



- **[BOBOcloud](https://github.com/NemophilistJohn/BOBOcloud-A-cloud-based-remote-compilation-platform)** — Cloud-based compiler with LSP and DAP debugging services, Docker scheduling .

- **[Open Devbox](https://github.com/Howryann/open-devbox)** — Portable Docker-based development box with SSH access and Mutagen sync .

- **[Ploomber Engine](https://github.com/ploomber/ploomber-engine)** — Jupyter notebook testing, debugging, and profiling toolbox.

- **[Snoop](https://github.com/alexmojaki/snoop)** — Powerful Python debugging tools based on PySnooper. 1,330+ GitHub stars .

- **[nopdb](https://github.com/cifkao/nopdb)** — Non-interactive Python debugger.

- **[CocoaDebug](https://github.com/CocoaDebug/CocoaDebug)** — iOS debugging tool. 4,090+ GitHub stars .

- **[eruda](https://github.com/liriliri/eruda)** — Console for mobile browsers.

- Community **VS Code Remote** extensions for SSH, Containers, and WSL.



**Frameworks for building custom systems**: Combine **code-server** or **OpenVSCode Server** as the browser IDE with **DevPod** or **Daytona** for environment orchestration, **DNCDbg** or **Seer** for debugging, and **Docker** for isolation — creating a fully self-hosted, enterprise-grade cloud IDE platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud IDEs and remote development tools must comply with data protection and security regulations (GDPR, SOC 2, etc.).

- Self-hosted open-source solutions require proper security hardening, resource provisioning, and ongoing maintenance for production reliability.



---



**Made for developers, platform engineers, DevOps teams, and organizations building transparent development environments.**  

Let's make Developer IDE & Debugging more open, data-driven, and efficient.
