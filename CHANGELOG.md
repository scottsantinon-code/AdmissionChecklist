# Admission Checklist Changelog

## v0.1 — 2026-03-21
- Initial app build with complete CABG chapter
- App shell with iOS-native design language matching clinical-apps suite
- Home screen with condition selector (CABG active, 4 coming soon)
- Healthcare professional disclaimer modal on first load
- Handover Guide: 11 expandable sections with consideration nudges and deep-dive bottom sheets
  - Indication & Urgency (with graft types reference)
  - Bypass Time (complications by organ system)
  - Cross-Clamp Time (risk thresholds and evidence)
  - Pre-op Cardiac Function
  - Post-op TOE
  - Separating from Bypass
  - Blood Products & Fluid
  - Drains (monitoring thresholds)
  - Pacing Wires
  - Pericardium
  - Surgeon's Targets
- Admission Checklist: 7 domains with checkable items and progress tracking
  - Investigations (Bloods, CXR, ECG, Cardiac index)
  - Management (6 sub-sections: Medications, Sedation & Analgesia, Haemodynamic Support, Ventilation, Warming, Monitoring)
  - Routine Prophylaxis (VTE with PROTECT evidence, Stress Ulcer with REVISE/PEPTIC/SUP-ICU trials, Bowel Care)
  - Goals & Targets (MAP, CI, SpO2, K+ with TIGHT-K evidence, Mg, Temp, Glucose)
  - Nutrition
  - Goals of Care
  - Communication
- Reusable bottom sheet component with swipe-to-dismiss
- Full clinical content encoded (no truncation)
- Session-only state, reset function with confirmation
