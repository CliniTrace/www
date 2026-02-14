# MVP Outline (90 days)

## MVP goal
Prove clinical workflow value and safety with a narrow, measurable use case.

## MVP Use Case
**Wound / skin progression monitoring** (non-diagnostic).

## Core user flows
1) Capture/upload image → quality coach → pass/fail gate  
2) AI overlay: area estimate + markers  
3) Save as timepoint → compare across visits  
4) Generate structured summary → clinician review

## MVP features
- Auth (role-based: clinician/admin)
- Secure upload + encryption at rest (implementation choice)
- Quality gating (blur/lighting/glare/distance hints)
- Simple segmentation/ROI + area estimate
- Longitudinal delta (% change)
- Structured report text block
- Audit trail of actions (basic)

## Out of scope (MVP)
- autonomous diagnosis
- prescriptions
- emergency triage
- broad multi-condition coverage
