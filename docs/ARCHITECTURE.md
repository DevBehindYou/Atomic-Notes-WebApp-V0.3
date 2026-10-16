# Browser workspace boundary

Owner decision, 16 October 2026: continue Flutter Web in an independent frontend repository and keep browser-specific server modules in a separate backend repository. Android optimization continues separately.

## Reuse and isolation

Reuse the accepted shared immutable sync envelope and inactive browser IndexedDB completion, lifecycle, owner-fencing and exact-preimage foundations. Record source commits, copied file hashes and deliberate import-name changes. Do not copy native credentials, signing files, Android runtime initialization, live account caches or ignored configuration.

The unmerged prepared-operation codec belongs to the WebApp workstream. It remains inactive until independently reviewed and tested. Native Android fixes can consume a shared protocol change later through a separate explicit compatibility change.

## Ordered gates

1. Import accepted browser foundations with a minimal web-only Flutter package, guarded entry point, strict analysis, protocol tests and real-Chromium storage tests. Preserve their original acceptance limits.
2. Review and accept the prepared-operation codec, then transactional journal admission/restore/settlement against owner and exact preimages.
3. Prove reload/crash/quota, single-writer and cross-tab behavior before browser editing or cloud writes.
4. Add the browser session gateway and read-only authenticated integration, with explicit cookie/CSRF/origin/owner context.
5. Prove Android/Web wire, economy, E2E and safe-logout interoperability using disposable services before real Drive and release acceptance.
6. Review rescue/PWA/update/rollback and browser-engine acceptance, then obtain deployment approval for a concrete verified release.

## Shared data authority

Repository separation does not authorize two independent mutation engines over the same MongoDB metadata, wallet and Google Drive state. The browser backend must delegate shared note/financial mutations to one reviewed authority, or use a separately accepted compatibility/fencing design. It must not store plaintext note content in MongoDB or assume native secure storage is a browser key store.

Final deployment URLs and authentication registrations remain unconfigured until the owner provides the verified links. Creating these repositories does not deploy either component or give the Android 2.03.9 Server a deployment green flag.
