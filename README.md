# Cocos Doctor

Cocos Doctor is a paid, evidence-first Inspector extension for Cocos Creator 3.8.8. It helps answer two practical questions from one dockable panel: “what caused the current runtime problem?” and “does this UI remain structurally sound across four representative screens?”

The commercial product is offline-first. Deterministic diagnosis, Runtime Cause Trace, Doctor Checkup Matrix, Preview, Apply, Replay verification and Undo do not require an AI key. Optional AI can explain existing local findings only after the panel displays the complete minimized payload and the user approves that single request.

## Product boundaries

- Runtime Cause Trace observes the real Preview input path, engine hit-test result, final receiver and supported propagation/handler evidence. Locate selects an exact root-cause UUID when available and overlays the observed click point without inventing node bounds. It does not substitute rectangle overlap for an input result.
- Doctor Checkup Matrix scans 16:9, 19.5:9 with safe area, 4:3/tablet and the exact current custom viewport. It restores the viewport and never writes the project.
- Apply is limited to local, one-property allowlisted patches. Every write requires an exact Preview and a one-time grant, then recapture and verification. Runtime-bound work is verified only for comparable `FIX_VERIFIED` evidence; every other Replay result remains unverified. Doctor keeps an explicit inverse for Undo.
- Layout/Widget design intent and ambiguous runtime attribution remain “needs confirmation”; Doctor does not invent a confident fix.
- Product telemetry is off. AI is optional, configured in panel memory only, and requires fresh consent for each request.

This public repository contains documentation, sanitized sample reports, non-executable failure fixtures, privacy/security material, changelog and support entry points. It intentionally does not contain the commercial ZIP, private core, production runtime wrappers, source code, buyer data or research data.

Start with [Privacy](PRIVACY.md), [Security](SECURITY.md), [Purchase notice](PURCHASE-NOTICE.md), [Support](SUPPORT.md), the [sample report](samples/checkup-matrix-report.json) and the [failure fixture](fixtures/button-blocked.json).

Cocos Doctor is an independent third-party product. It is not an official Cocos product and is not endorsed by Cocos.
