# TrustLight 🟢🔴

> **"When the lights go out, Gloria doesn't know which alert is real. TrustLight gives her the answer in under five seconds."**

**On-device AI emergency alert verification for elderly adults living alone.**
PROPEL Future of Tech Innovation Challenge 2026 · Cybersecurity, Energy & Climate Resilience Track

> ⚠️ **This repository contains a concept proposal and research document only.** TrustLight has not been implemented or built as a working application. It was submitted as a design proposal to the PROPEL Future of Tech Innovation Challenge at Grambling State University in February 2026.

---

## The Problem in One Sentence

During grid failures, AI-generated fake emergency alerts and real ones look identical — and for a 73-year-old living alone with insulin that expires in 4 hours, guessing wrong is fatal.

---

## The Solution in Two Signals

TrustLight intercepts incoming alerts, verifies them on-device using Apple Intelligence in under 5 seconds, and delivers one of two answers:

| Signal | Meaning |
|---|---|
| 🟢 **GREEN** | Verified. Source confirmed. Act now. |
| 🔴 **RED** | Unverified. Do not act. I'll update you immediately. |

No middle state. No ambiguity. No cloud. No data leaves her phone.

---

## How It Works

```
Alert arrives
  → Apple Intelligence verifies source + language patterns
  → WeatherKit cross-checks local conditions
  → GREEN or RED delivered via Siri in plain language
  → If no response in 20 min → Denise gets one quiet iMessage
```

---

## Five Apple Platforms, One Binary Signal

| Platform | Role |
|---|---|
| iPhone | Primary verification + Siri voice delivery |
| Apple Watch | Haptic + glanceable verdict for low-vision users |
| HomePod | Ambient audio for users not holding a device |
| iPad | Expanded context for caregivers |
| Mac | Background monitoring + caregiver dashboard |

---

## Research Foundation

This proposal synthesized 20+ peer-reviewed sources into a STEEP-based risk model covering:

- **Social:** elderly isolation and cognitive load during emergencies
- **Technological:** on-device AI capabilities and privacy constraints
- **Economic:** cost of false positives vs false negatives in emergency response
- **Environmental:** grid failure scenarios and offline operation requirements
- **Political:** FCC and FEMA alert system trust gaps

---

## Why On-Device

- Grid failures take the internet with them
- Cloud-dependent verification fails exactly when it's needed most
- No alert content ever leaves the device
- Apple Intelligence runs entirely on-device with no server calls

---

## Repository Contents

- `TrustLight_MasterResearch_V4.pdf` — Full research document with STEEP analysis and source synthesis
- `TrustLight_PitchDeck.pdf` — PROPEL competition pitch deck
- `TECHNICAL.md` — Technical architecture and platform breakdown

---

## Built By

Patrick Ennin Selby · Grambling State University
Submitted to PROPEL Future of Tech Innovation Challenge · February 2026
