# AGENTIC OS V3.0 — Mission Control

AGENTIC OS is a Windows desktop application that brings together a dashboard, an assistant, and management tools in a single interface.

## Features

The Windows package includes the Mission Control, JARVIS, Skills, Memory, Security Center, JARVIS Vision, Multi-Agent Brain, and Self-Improvement Lab interfaces.

The presence of these modules has been verified through package inspection. Their functionality on a clean Windows installation has yet to be validated.

## Installation

1. Use a Windows x64 PC. The minimum supported Windows version has yet to be confirmed.

2. Once the release is published, download `AGENTIC OS V3.0.exe` from the assets of Release `v3.0.0`.

3. Verify the downloaded file's checksum using PowerShell:

   ```powershell
   Get-FileHash -LiteralPath '.\AGENTIC OS V3.0.exe' -Algorithm SHA256
   ```

   **Expected SHA-256:**

   `F9CAD341F86D9848FFD43DED7B685F6EF003CA4E9977BA2E41CCE534BA215202`

4. After verification, launch the Windows installer and follow the setup wizard.

   The installer uses the original AGENTIC OS application identity. If a version with the same identity is already installed, verify the upgrade procedure before proceeding.

## Limitations

The installer is not digitally signed with an Authenticode signature. Windows may display a security warning.

Hugo Voice, Whisper, and microphone availability are not among the verified features of this release.

Features that depend on local services require additional configuration.

## Licenses

The package includes Electron and Chromium notices, along with license notices for dependencies.

The redistribution rights for the complete package and the application's licensing terms must be confirmed before publication.
