# VeVak brand

Official brand, visual identity and communication guidance for **VeVak**.

## What the brand must communicate

VeVak is a privacy-first, open-source Android project for on-demand location sharing by SMS. Its identity should communicate **control, reassurance, sobriety and clarity** — not surveillance, panic or technological omnipotence.

Core public promise:

> A backup location request by SMS, local and under the user's control.

## Tone

Preferred tone:

- calm;
- precise;
- human;
- accessible;
- non-alarmist;
- technically honest;
- respectful of user autonomy.

Avoid:

- fear-based safety marketing;
- “always protected / always locatable” promises;
- surveillance or stalking aesthetics;
- military / tactical visual codes;
- exaggerated emergency imagery;
- language implying that VeVak replaces emergency services;
- dark patterns around permissions or consent.

## Product truths the identity must preserve

- the current core uses an explicitly authorised trusted contact;
- the core works locally and does not require a mandatory VeVak cloud account/server;
- SMS still depends on the mobile network and operator service;
- location is requested on demand rather than continuously in the current core;
- no advertising, trackers or telemetry;
- FOSS-first development and F-Droid compatibility are priorities;
- Android/device restrictions can prevent successful background operation;
- VeVak is not an emergency service and is not a guarantee of safety.

## Visual direction

The design system should favour:

- strong readability and generous spacing;
- accessible contrast;
- large, obvious interaction states;
- icons that remain understandable without colour alone;
- layouts that tolerate large text and accessibility settings;
- restrained animation and resource use;
- a small reusable component set rather than decorative complexity.

Any future SOS or device-recovery surfaces should remain visually distinct from ordinary settings, with explicit actions, cancellation paths and no ambiguous “panic” affordances that increase accidental triggering.

## August 2026 product direction

The visual system should be able to support three levels without implying that all are currently shipped:

1. **Core VeVak** — SMS request → validation → location → SMS reply.
2. **Reliability tools** — guided readiness test, battery/manufacturer diagnostics, dual-SIM clarity.
3. **Future modules under study** — explicit outgoing SOS and a local-first device-recovery module inspired by selected Find Hub/Find Device ideas such as ringing, battery/state information, lock-screen message and last-known-position recovery.

Future modules must look like extensions of the same consent-based product, not a separate surveillance application.

## Repository role

This repository is intended for source brand assets, export guidance, icon rules, screenshots/templates and communication constraints. Product behaviour belongs in `jasmin-abernathy/vevak`; project documentation belongs in `jasmin-abernathy/vevak-docs`.

## Licence

See `LICENSE`.
