# Chatroule — Releases

Téléchargements officiels de **Chatroule**, poste de pilotage desktop pour CLI
agentiques (Claude Code, opencode, GitHub Copilot CLI). Le code source est
développé dans un dépôt privé ; ce dépôt ne contient que les releases.

## Installation

Récupère la dernière version sur la page
**[Releases](https://github.com/b-love-official/chat-roule-releases/releases/latest)** :

| OS                        | Fichier                         | Installation |
| ------------------------- | ------------------------------- | ------------ |
| **Linux**                 | `Chatroule-<version>.AppImage`  | `chmod +x Chatroule-*.AppImage` puis lance-le. |
| **Windows**               | `Chatroule-Setup-<version>.exe` | Lance l'installeur (NSIS). SmartScreen peut avertir (non signé) → _Informations complémentaires → Exécuter quand même_. |
| **macOS** (Apple Silicon) | `Chatroule-<version>-arm64.dmg` | Ouvre le `.dmg`, glisse l'app dans `Applications`. Non signé → au 1er lancement, clic droit → **Ouvrir**. |
| **macOS** (Intel)         | `Chatroule-<version>.dmg`       | Idem — même procédure Gatekeeper. |

**Mises à jour automatiques** (Linux & Windows) : l'app vérifie ce dépôt au
démarrage et propose le téléchargement puis l'installation au redémarrage
(electron-updater). macOS est hors périmètre (signature Apple requise).

Les fichiers `latest*.yml` et `*.blockmap` servent au mécanisme de mise à
jour — ne pas les supprimer des releases.
