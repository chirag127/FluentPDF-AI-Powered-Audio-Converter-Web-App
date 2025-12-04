# FluentPDF-AI-Powered-Audio-Converter-Web-App

![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/ci.yml?style=flat-square)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Tech%20Stack-TypeScript%2C%20Tauri%2C%20TailwindCSS-blue?style=flat-square)
![Lint & Format](https://img.shields.io/badge/Biome-on-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App?style=flat-square)


### Empowering Accessibility: Convert PDFs to Spoken Audio with AI.

This application leverages advanced AI to transform PDF documents into natural-sounding spoken audio, enhancing accessibility and providing a seamless on-the-go listening experience.

<details>
<summary>🤖 AI Agent Directives</summary>

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
**Directives:** Detect the project type and apply the **Apex Toolchain**.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x** (Strict Mode). Key tools include **Vite 7** (with Rolldown for bundling), **Tauri v2.x** for native desktop applications, and **TailwindCSS v4** for rapid UI development. State management adheres to the standardized **Signals** pattern.
    *   **Linting & Formatting:** **Biome** is utilized for its exceptional speed and comprehensive linting/formatting capabilities across the entire project.
    *   **Testing:** **Vitest** is employed for fast unit testing, complemented by **Playwright** for end-to-end testing scenarios.
    *   **Architecture:** Implements the **Feature-Sliced Design (FSD)** methodology for scalable and maintainable frontend architecture.
    *   **AI Integration:** Assumed integration with a Text-to-Speech (TTS) API (e.g., Google Cloud TTS, OpenAI TTS). Prioritize modular design, clear API contracts, and robust error handling for all external AI model interactions.

### 4. CORE DEVELOPMENT PRINCIPLES
*   **SOLID:** Ensure all code adheres to the SOLID principles for maintainability and extensibility.
*   **DRY (Don't Repeat Yourself):** Minimize code duplication.
*   **YAGNI (You Ain't Gonna Need It):** Build only what is necessary.
*   **KISS (Keep It Simple, Stupid):** Favor simplicity in design and implementation.

### 5. VERIFICATION COMMANDS
*   **Linting & Formatting:** `biome check --apply`
*   **Unit Tests:** `vitest run`
*   **E2E Tests:** `npx playwright test`
*   **Build:** `npm run build`

</details>

---

## 🚀 Project Overview

FluentPDF is an innovative web application designed to make PDF content more accessible by converting documents into high-quality spoken audio. Utilizing cutting-edge AI for text-to-speech synthesis, it provides users with an easy-to-use interface to upload PDFs and receive audio files, perfect for hands-free consumption of information.

## 🏗️ Architecture

mermaid
graph TD
    A[User Interface (Tauri/Vite/React)] -- Upload PDF --> B(Backend Service)
    B -- Extract Text --> C(AI PDF Parser)
    C -- Text Content --> D(AI Text-to-Speech API)
    D -- Audio Stream --> B
    B -- Audio File --> A
    A -- Play Audio --> E(User Device)


## 📃 Table of Contents

*   [Project Overview](#-project-overview)
*   [Architecture](#-architecture)
*   [Table of Contents](#-table-of-contents)
*   [AI Agent Directives](#-ai-agent-directives)
*   [Key Features](#-key-features)
*   [Technology Stack](#-technology-stack)
*   [Getting Started](#-getting-started)
*   [Development Workflow](#-development-workflow)
*   [Contributing](#-contributing)
*   [License](#-license)

## ✨ Key Features

*   **AI-Powered Conversion:** High-fidelity text-to-speech synthesis for natural-sounding audio.
*   **Multi-Language Support:** Capable of processing and converting documents in various languages (API dependent).
*   **Accessible Interface:** Built with accessibility in mind, ensuring ease of use for all users.
*   **Cross-Platform:** Packaged as a desktop application via Tauri, offering a native experience.
*   **Efficient Processing:** Optimized workflows for quick PDF upload and audio generation.

## 🛠️ Technology Stack

*   **Frontend:** TypeScript, Vite, React, TailwindCSS v4
*   **Desktop Packaging:** Tauri v2
*   **AI Services:** Text-to-Speech API (e.g., Google Cloud TTS, OpenAI TTS)
*   **Linting & Formatting:** Biome
*   **Testing:** Vitest (Unit), Playwright (E2E)

## 🚀 Getting Started

### Prerequisites

*   Node.js LTS (v20+ recommended)
*   npm or Yarn
*   Rust (for Tauri development)

### Installation

bash
# 1. Clone the repository
git clone https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App.git
cd FluentPDF-AI-Powered-Audio-Converter-Web-App

# 2. Install Node.js dependencies
npm install

# 3. Install Rust dependencies (if not already installed)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# 4. Build the Tauri application
npm run tauri build


## 💼 Development Workflow

| Script            | Description                                     |
| :---------------- | :---------------------------------------------- |
| `npm run dev`     | Start the development server                    |
| `npm run build`   | Build the production release                    |
| `npm run lint`    | Run Biome linter                                |
| `npm run format`  | Format code with Biome                          |
| `npm run test:unit` | Run Vitest unit tests                         |
| `npm run test:e2e`  | Run Playwright end-to-end tests               |
| `npm run tauri dev` | Run the Tauri application in development mode |
| `npm run tauri build`| Build the Tauri desktop application            |

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/blob/main/.github/CONTRIBUTING.md) file for detailed guidelines on how to submit your contributions.

## 📜 License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](https://github.com/chirag127/FluentPDF-AI-Powered-Audio-Converter-Web-App/blob/main/LICENSE) file for more details.

**Note:** This repository is a conceptual representation following Apex Technical Authority standards. Actual AI integration and specific API keys are outside the scope of this template.
