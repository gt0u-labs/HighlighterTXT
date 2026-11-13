# 🔍 HighlighterTXT | Secure Log Annotation Engine

![Status](https://img.shields.io/badge/Status-Architectural_Case_Study-black?style=for-the-badge)
![Security](https://img.shields.io/badge/Encryption-AES--256--GCM-darkred?style=for-the-badge)
![Framework](https://img.shields.io/badge/Built_with-Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows_x64-0078D6?style=for-the-badge&logo=windows&logoColor=white)

> **Note:** This repository serves as an architectural case study and portfolio showcase. The source code is maintained privately (Closed Source) for security and personal use. The provided binaries in the Releases tab are for demonstration purposes.

HighlighterTXT is an offline-first desktop application designed for secure log review, text annotation, and applied local cryptography. It transforms raw data and text files into an organized, heavily encrypted local workspace.

## 🚀 System Architecture & Core Features

### 🟢 Annotation & Log Analysis Engine
*   **Real-time Threat/Pattern Tagging:** Multi-color highlighting specifically designed for log analysis and rapid pattern discovery.
*   **Metadata Layering:** Attach custom tags and persistent notes (including visual emoji markers) to specific strings without altering the raw source file.
*   **Navigation Dock:** Summary panel allowing instant traversal between flagged anomalies or annotated points.
*   **Report Compilation:** Automated conversion of annotated workspaces into clean, formatted PDF reports.

### 🛡️ Applied Cryptography & Local Security
*   **Custom `.hxt` Payload Format:** Implementation of **AES-256-GCM** encryption to secure sensitive local files against unauthorized access or tampering.
*   **Manual Workspace Lock:** Hardware-level UI lock trigger (`Ctrl+Alt+L`) requiring password verification to resume the session.
*   **Idle Auto-Lock:** Configurable timeout terminating the active session after periods of inactivity.
*   **Air-Gapped Design:** Zero telemetry, zero cloud synchronization. Operates strictly in an offline, local-first environment.

## 📥 Deployment

Check the **Releases** tab to download the compiled `.exe`.
*Run `HighlighterTXT_Setup.exe` (Administrator privileges may be required depending on local security policies).*

---
*Architected and maintained by [GT0u Labs](https://gt0u-labs.github.io).*
