# AGENTIC OS V3.0 — Mission Control

AGENTIC OS est une application de bureau Windows qui réunit un tableau de bord, un assistant intelligent et des outils de gestion dans une interface unique.

## Fonctionnalités

Le paquet Windows comprend les modules suivants :

- **Mission Control** — Tableau de bord principal.
- **JARVIS** — Assistant intelligent.
- **Skills** — Gestion des compétences et des outils.
- **Memory** — Gestion de la mémoire.
- **Security Center** — Centre de sécurité.
- **JARVIS Vision** — Interface dédiée à la vision.
- **Multi-Agent Brain** — Gestion des agents.
- **Self-Improvement Lab** — Laboratoire d'expérimentation et d'amélioration.

La présence de ces modules a été vérifiée par inspection du paquet. Leur fonctionnement complet sur un ordinateur Windows neuf reste à valider.

## Installation

1. Utilisez un ordinateur Windows x64. La version minimale de Windows compatible reste à confirmer.

2. Une fois la version publiée, téléchargez `AGENTIC OS V3.0.exe` depuis les fichiers de la Release `v3.0.0`.

3. Vérifiez l'empreinte SHA-256 du fichier téléchargé avec PowerShell :

   ```powershell
   Get-FileHash -LiteralPath '.\AGENTIC OS V3.0.exe' -Algorithm SHA256
   ```

   **SHA-256 attendu :**

   `F9CAD341F86D9848FFD43DED7B685F6EF003CA4E9977BA2E41CCE534BA215202`

4. Après vérification, lancez l'installateur Windows et suivez les instructions.

   L'installateur conserve l'identité originale d'AGENTIC OS. Si une version utilisant cette même identité est déjà installée, vérifiez les conditions de mise à jour avant de poursuivre.

## Limitations

L'installateur ne possède pas de signature numérique Authenticode. Windows peut donc afficher un avertissement de sécurité.

La voix Hugo, Whisper et le fonctionnement du microphone ne font pas partie des fonctionnalités vérifiées pour cette version.

Certaines fonctionnalités nécessitent la configuration de services locaux supplémentaires.

## Licences

Le paquet contient les notices légales d'Electron et de Chromium, ainsi que des informations de licence concernant certaines dépendances.

Les droits de redistribution du paquet complet et les conditions de licence de l'application doivent être confirmés avant toute publication publique.

---

**Développé par NeuraxOS 💙**

*AGENTIC OS — Un seul centre de contrôle. Des possibilités infinies.*
