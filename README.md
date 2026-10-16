# Atomic Notes WebApp V0.3

Dedicated Flutter Web workspace for Atomic Notes, maintained by DevBehindYou.

This repository separates browser storage, authentication, UI, lifecycle and release work from the Android optimization repositories. The owner confirmed Flutter Web and Android release **2.03.9+9** on 16 October 2026.

The initial repository establishes the project boundary. Accepted browser foundations will be imported in a focused, reviewed change from Android App main `7468460d7e36c4936f03f9fa29084c611975e0e1`. Unmerged prepared-operation codec work will be reviewed here before integration. No browser notes runtime or deployment is accepted merely by creating this repository.

## Related repositories

- Browser-specific backend: `DevBehindYou/Atomic-Notes-WebApp-Server-V0.3`.
- Android App: `DevBehindYou/Atomic-Notes-App-V0.3`.
- Android/shared mutation Server: `DevBehindYou/Atomic-Notes-Server-V0.3`.
- Website and Controller: `DevBehindYou/Atomic-Notes-Community-V0.3`.

See [architecture and acceptance](docs/ARCHITECTURE.md). Local credentials, authentication exports, personal conversation archives and build caches do not belong in this repository.
