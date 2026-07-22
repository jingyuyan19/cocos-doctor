# Security

## Design controls

- No AI-generated code execution, `eval`, arbitrary property setter or raw scene/prefab write.
- One typed property operation per Patch, with session/revision/node/old-value preconditions.
- One-time main-process Preview authority; failed, expired or mismatched attempts require a new Preview.
- Doctor-owned Chrome uses a private debugging pipe and an isolated temporary profile, not a listening CDP port or an existing browser session.
- Runtime wrappers are memory-only and restore patched engine functions, overlay state, viewport and temporary CSS on stop/page close/unload.
- Cause conclusions require linked engine evidence; rectangle overlap never proves the hit receiver.
- Matrix analysis is structural/layout-only, bounded to the qualified node capacity and reports incomplete capture as an integrity failure.
- AI receives only a fixed minimized projection after visible per-request consent and cannot create local actions.
- Commercial packaging and public export both use exact file allowlists and reject source, tests, private data, stale build files and symlink escapes.

## Reporting a vulnerability

Use the Cocos Store resource support channel for a private first report. Do not include a commercial project, credentials, buyer/order data or the commercial ZIP. A minimal disposable reproduction and the public Doctor error code are preferred.

Public issues may be opened at <https://github.com/jingyuyan19/cocos-doctor/issues> only after confidential material has been removed.
