# Contributing to ShieldApp

Thank you for your interest in contributing to ShieldApp! This project is structured as a customized derivative of the Tauri framework.

## Local Development Setup

### Using Dev Containers (Recommended)
This repository includes a complete `.devcontainer` configuration. If you use VS Code:
1. Install the **Dev Containers** extension.
2. Open the repository in VS Code and click **Reopen in Container** when prompted.
3. All required dependencies (Rust, Node.js, and Tauri prerequisites) will be configured automatically.

### Manual Local Build
If building manually on your host machine:
1. Ensure Rust and Node.js are installed.
2. Install project dependencies:
   ```bash
   pnpm install