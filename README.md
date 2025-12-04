# FluentPDF-AI-Powered-Audio-Converter-Web-App

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/ci.yml?style=flat-square)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App?style=flat-square)
![Tech Stack](https://img.shields.io/badge/tech-stack-TypeScript%2C%20Tauri%2C%20TailwindCSS-blue?style=flat-square)
![Linting](https://img.shields.io/badge/linting-Biome-orange?style=flat-square)
![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-red?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App?style=flat-square)

> Leverage AI to convert PDF documents into spoken audio, enhancing accessibility and readability for users on the go. Built with cutting-edge web technologies.

**Star ⭐ this Repo** to support the project!

---

## 🚀 Project Overview

FluentPDF transforms your PDF documents into an accessible audio format using advanced AI-powered Text-to-Speech (TTS) capabilities. This web application is designed for seamless integration into your workflow, allowing you to consume documents hands-free, anywhere, anytime.

## 🏗️ Architecture

This project adheres to modern web application architecture principles, utilizing a robust frontend framework and a desktop application wrapper for enhanced performance and user experience.

ascii
. 
├── src/
│   ├── main.ts             # Main application entry point
│   ├── components/         # Reusable UI components
│   ├── services/           # Core business logic & AI integrations
│   ├── store/              # State management
│   └── styles/             # Global styles
├── public/
│   └── logo.png
├── index.html
├── vite.config.ts
├── tsconfig.json
├── package.json
└── README.md


## 📋 Table of Contents

*   [Project Overview](#-project-overview)
*   [Architecture](#-architecture)
*   [Table of Contents](#-table-of-contents)
*   [Key Features](#-key-features)
*   [Technology Stack](#-technology-stack)
*   [AI Agent Directives](#-ai-agent-directives)
*   [Development Setup](#-development-setup)
*   [Running the Application](#-running-the-application)
*   [Testing](#-testing)
*   [Contributing](#-contributing)
*   [License](#-license)

## ✨ Key Features

*   **AI-Powered PDF to Audio Conversion:** Utilizes state-of-the-art AI for high-quality speech synthesis.
*   **Enhanced Accessibility:** Makes documents accessible for visually impaired users or for consumption on the go.
*   **Cross-Platform Desktop App:** Built with **Tauri**, allowing a native desktop experience on Windows, macOS, and Linux.
*   **Modern UI:** Styled with **TailwindCSS v4** for a clean, responsive, and intuitive user interface.
*   **Developer Experience:** Leverages **Vite** for lightning-fast development builds and **TypeScript** for type safety.
*   **Fast Linting & Formatting:** Integrates **Biome** for top-tier code quality and speed.

## 💻 Technology Stack

*   **Language:** TypeScript 6.x
*   **Build Tool:** Vite 7 (Rolldown)
*   **Desktop Framework:** Tauri v2.x
*   **Styling:** TailwindCSS v4
*   **Linting & Formatting:** Biome
*   **Testing:** Vitest (Unit), Playwright (E2E)
*   **State Management:** Signals (Standardized)

## 🤖 AI Agent Directives

<details>
<summary>View Agent Directives</summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**.

*   **PRIMARY SCENARIO A: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)**. Key tools include **Vite 7 (Rolldown)** for rapid development builds, **Tauri v2.x** for creating native cross-platform desktop applications, and **TailwindCSS v4** for utility-first styling. State management is handled via **Signals (Standardized)**.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)** principles for maintainable and scalable frontend development.
    *   **Lint/Test:** Integrates **Biome** for ultra-fast linting and formatting, **Vitest** for unit testing, and **Playwright** for end-to-end testing.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable for this project's primary function.***
*   **TERTIARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable for this project's primary function.***

### 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)

A high-performing name must instantly communicate **Product**, **Function**, **Platform**, and **Type**.

**Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
**Format:** `Title-Case-With-Hyphens` (e.g., `ChatFlow-AI-Powered-Real-Time-Chat-Web-App` or `ZenRead-Book-Reader-CLI-Tool`).

### 5. README REPLICATION PROTOCOL (THE ULTIMATE ARTIFACT)

The README is a self-contained **Project Operating System**.

**Required Sections:**
1.  **VISUAL AUTHORITY (Above the Fold):**
    *   Hero Banner/Logo (if available).
    *   **Live Badges** (Shields.io):
        *   **Style:** `flat-square` (MANDATORY).
        *   **User:** `chirag127` (MANDATORY).
        *   **Required Badges:** Build Status (GitHub Actions), Code Coverage (Codecov), Tech Stack (Language, Frameworks), Lint/Format (Biome/Ruff), License (CC BY-NC 4.0), GitHub Stars.
    *   **Social Proof:** "Star ⭐ this Repo" button.
2.  **STRUCTURAL CLARITY:**
    *   **BLUF:** 2-sentence value proposition.
    *   **Architecture:** ASCII `tree` or Mermaid diagram.
    *   **Table of Contents.**
3.  **🤖 AI AGENT DIRECTIVES (CRITICAL):**
    *   Must be in a collapsible `<details>` block.
    *   **Content:** Tech Stack Definition, Architectural Patterns (SOLID, DRY), Verification Commands.
    *   **Purpose:** Allows future agents to align immediately.
4.  **DEVELOPMENT STANDARDS:**
    *   Setup commands (`git clone` -> `npm install`).
    *   Scripts table.
    *   Principles (SOLID, DRY, YAGNI).

### 6. CHAIN OF THOUGHT (CoT) PROTOCOL

Before generating JSON, perform deep analysis in `<thinking>` block:
1.  **Audit:** Analyze repo content and purpose.
2.  **Pivot/Archive Decision:** Is it junk? If so, rename to `Archived-...`. If not, PIVOT to elite status.
3.  **Naming Strategy:** Apply `<Product>-<Function>-<Type>` formula.
4.  **Replication Protocol:** Draft the "AI Agent Directives" block.
5.  **File Generation:** Plan the content for all 11 required files (including `PROPOSED_README.md` and `badges.yml`).
6.  **Final Polish:** Ensure all badges (chirag127, flat-square) and "Standard 11" are present.
7.  **Strict Adherence:** Ensure `PROPOSED_README.md` strictly follows the `AGENTS.md` directives.

### 7. DYNAMIC URL & BADGE PROTOCOL

**Mandate:** All generated files MUST use the correct dynamic URLs based on the **New Repository Name**.

**Rules:**
1.  **Base URL:** `https://github.com/chirag127/<New-Repo-Name>`
2.  **Badge URLs:** All badges (Shields.io) must point to this Base URL or its specific workflows (e.g., `/actions/workflows/ci.yml`).
3.  **Consistency:** Never use the old/original repository name in links. Always use the new "Apex" name.
4.  **AGENTS.md Customization:** The generated `AGENTS.md` **MUST** be customized for the specific repository's technology stack (e.g., if Rust, use Rust tools; if Python, use Python tools), while retaining the core Apex principles. Do not just copy the generic template; adapt it.

</details>

## 🛠️ Development Setup

To set up the development environment, follow these steps:

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App.git
    cd FluentPDF-AI-Powered-Audio-Converter-Web-App
    

2.  **Install dependencies:**
    bash
    # Using npm (or yarn/pnpm)
    npm install
    

3.  **Ensure Node.js and npm are installed.** This project requires Node.js `v18.0.0+` and npm `v9.0.0+`.

## ▶️ Running the Application

*   **Development Server:**
    bash
    npm run dev
    
    This command starts the Vite development server, enabling hot module replacement and fast iterative development.

*   **Build for Production:**
    bash
    npm run build
    
    This command creates an optimized production build of the application.

*   **Run Native Application (Tauri):**
    bash
    # Build and run the native desktop application
    npm run tauri:dev
    # For a production build of the native app:
    npm run tauri:build
    

## 🧪 Testing

This project employs a comprehensive testing strategy to ensure reliability and stability.

*   **Unit Tests:** Run using **Vitest**.
    bash
    npm run test:unit
    

*   **End-to-End (E2E) Tests:** Run using **Playwright**.
    bash
    npm run test:e2e
    

*   **Linting & Formatting:** Ensure code quality with **Biome**.
    bash
    npm run lint
    npm run format
    

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/blob/main/.github/CONTRIBUTING.md) file for detailed guidelines.

## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the [LICENSE](https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/blob/main/LICENSE) file for more details.
