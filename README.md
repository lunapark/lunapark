# Luna Park

[Luna Park](https://luna-park.app/) brings visual programming to full-stack application development. Build interfaces, application logic, APIs, and databases in one workspace, then export your project and choose where to host it.

[Open the browser editor](https://luna-park.app/editor) · [Download the desktop beta](https://luna-park.app/) · [Read the documentation](https://luna-park.app/docs/) · [Report a bug or suggest a feature](https://github.com/lunapark/lunapark/issues/new/choose)

## What you can build

- **Interfaces and components:** responsive pages, reusable Vue components, shared design tokens, and live previews.
- **Application logic and state:** typed visual graphs with functions, conditions, loops, and centralized stores.
- **Backend and data:** REST APIs, PostgreSQL databases and queries, and scheduled tasks.
- **Extensions:** use third-party npm packages and Vue component libraries in your projects, or extend Luna Park through plugins.
- **AI assistance:** optionally use Sidekick with your chosen provider, API key, local model, or supported external agent. You can build without AI.
- **Exports and hosting:** export applications and source code, continue development with your usual tools, and deploy to your chosen infrastructure, subject to your plan and included dependency licenses.

Luna Park projects use Vue and Vite for the frontend, Node.js and Fastify for the backend, and PostgreSQL for data.

## Browser and desktop

Start in the [browser editor](https://luna-park.app/editor), or use the official website's **Download** button to get the desktop beta for Windows, macOS, or Linux.

Desktop supports Windows x64, macOS on Intel and Apple Silicon, and Linux x64. Keep backups of important projects while using the beta. Local editing and saving do not require a JavaScript toolchain; generating and running projects require the supported Node.js and pnpm versions.

The desktop application also supports native application builds:

- **Desktop:** build for the operating system you are using, with Rust and that system's Tauri prerequisites.
- **Android:** requires Rust, the Android SDK/NDK, and a compatible JDK.
- **iOS:** requires a Mac, Rust, Xcode, and Apple's signing tools and account.

Native builds package the frontend; applications using a backend need a deployed server. Editor access, export options, and native compilation depend on your plan. See [pricing](https://luna-park.app/pricing) and the [documentation](https://luna-park.app/docs/) for current availability and requirements.

## Learn and get help

- [Documentation](https://luna-park.app/docs/) — guides and technical reference.
- [Interactive challenges](https://luna-park.app/challenge) — practice visual programming.
- [Video academy](https://luna-park.app/academy) — guided courses and learning paths.
- [Education](https://luna-park.app/education) — resources for schools, teachers, and workshops.
- [Community forum](https://forum.luna-park.app/) and [Discord](https://discord.gg/2eAk2AHvdw) — questions, discussion, and support.

## About this repository

This is Luna Park's public product and feedback hub. Use the [issue forms](https://github.com/lunapark/lunapark/issues/new/choose) for reproducible bugs and feature requests. See [Contributing](CONTRIBUTING.md) before submitting a report or documentation change.

The proprietary editor source is not hosted here. Read [Source code and project ownership](SOURCE_CODE.md) and the [licensing notice](LICENSE.md) for the distinction between the editor, your projects, and third-party dependencies.
