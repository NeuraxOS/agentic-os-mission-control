# AGENTIC OS V3.0 — Mission Control

AGENTIC OS est une application de bureau Windows qui réunit un tableau de bord, un assistant et des outils de gestion dans une même interface.

## Fonctionnalités

Le paquet Windows contient les interfaces Mission Control, JARVIS, Skills, Memory, Security Center, JARVIS Vision, Multi-Agent Brain et Self-Improvement Lab. La présence de ces modules a été vérifiée par inspection du paquet. Leur exécution sur une machine vierge reste à valider.

## Installation

1. Utilisez un PC Windows x64. La version minimale de Windows reste à confirmer.
2. Une fois la version publiée, récupérez `AGENTIC OS V3.0.exe` dans les fichiers de la Release `v3.0.0`.
3. Vérifiez l’empreinte du téléchargement avec PowerShell.

   ```powershell
   Get-FileHash -LiteralPath '.\AGENTIC OS V3.0.exe' -Algorithm SHA256
   ```

   SHA-256 attendu : `F9CAD341F86D9848FFD43DED7B685F6EF003CA4E9977BA2E41CCE534BA215202`.

4. Après vérification, ouvrez l’installateur Windows et suivez l’assistant. Il utilise l’identité AGENTIC OS d’origine. Si une version portant cette identité est déjà installée, vérifiez le scénario de mise à jour avant de continuer.

## Limitations

L’installateur est dépourvu de signature Authenticode. Windows peut afficher un avertissement de sécurité. La voix Hugo, Whisper et la disponibilité du microphone ne font pas partie des fonctionnalités vérifiées pour cette version. Les fonctions qui dépendent de services locaux nécessitent leur configuration.

## Licences

Le paquet contient les notices Electron et Chromium et des avis de licence de dépendances. Les droits de redistribution du paquet complet et la licence de l’application doivent être confirmés avant publication.
