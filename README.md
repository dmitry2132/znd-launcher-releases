# ZND Launcher

A personal Windows game launcher built on the open-source Playnite foundation, with ZND's Desktop and Console experiences, Arabic and English interfaces, a local profile, a completed-game archive, and an upcoming-game watchlist.

[Download the latest installer](https://github.com/dmitry2132/znd-launcher-releases/releases/latest/download/ZND_Launcher_Setup.exe) · [Release history](https://github.com/dmitry2132/znd-launcher-releases/releases)

Windows 10/11 on 64-bit systems. The installer contains the required application runtime files and library integrations. Game files, personal libraries, platform sessions and publisher keys are excluded. Connect your own libraries after installation. Official platform clients and their normal authentication/DRM requirements still apply.

Starting with version 0.1.4, ZND checks this repository in the background and displays updates in the existing Notification Center. Choose **Update now** to download; choose **Install and restart** and confirm to install. Your library, completed games, local profile and settings are preserved. Older ZND versions require one manual upgrade to enable this updater. Updates do not require a ZND or GitHub account.

The update manifest is authenticated with the ZND publisher's pinned RSA key. Downloads are checked against the signed SHA-256 and file size. The Windows executable is **not Authenticode-signed**. Do not mistake the update manifest signature for a Windows code-signing certificate.

The launcher keeps a verified previous installer and a private data recovery copy during in-app upgrades. Read each release's notes and test report. Keep your own backup of personal data as well.

ZND account sign-in and hosted cloud synchronization are not connected to a public backend yet. The local launcher and profile work without an account.

Playnite is copyright Josef Nemec and its contributors, licensed under MIT. [Playnite source](https://github.com/JosefNemec/Playnite). The installer includes the upstream notice and licenses for bundled libraries and integrations. This release repository contains distribution assets; it is not the upstream Playnite repository.
