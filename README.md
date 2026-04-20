# On-call Physician Workflow Companion

## 1. App name
O plantonista

## 2. One-line summary
A public-safe technical case for an on-call physician workflow companion focused on organization, synthesis, and shift continuity.

## 3. Primary user
On-call physician

## 4. Secondary user
Clinical reviewer or support team

## 5. Problem solved
Shift work suffers from fragmentation across notes, events, pending tasks, and patient context, especially on mobile.

## 6. Short workflow
A physician captures events during the shift, reviews a patient-centered summary, updates a structured document, and prepares handoff material in a controlled interface.

## 7. Public-safe technical scope
Public-safe scope covers shift dashboards, patient organization, structured summaries, mobile-first workflow, and handoff support.

## 8. High-level integrations
High-level only: web client, real-time update layer, structured persistence, and controlled document generation.

## 9. What stays private and why
Clinical event content, internal normalization logic, document derivation rules, and any real patient handling detail remain private because they are sensitive by nature.

## 10. Confidence level
HIGH

## 11. Exposure risk
HIGH

## 12. Repository map
```text
dr2-o-plantonista-showcase/
├── README.md
├── LICENSE
├── .gitignore
├── PUBLIC_DISCLOSURE_POLICY.md
├── SECURITY_BOUNDARY.md
├── APP_CARD_PTBR.md
├── TECHNICAL_STORY.md
├── ARCHITECTURE.md
├── WORKFLOW.md
├── PRIVACY_BOUNDARY.md
├── IMPACT_NOTES.md
├── MANUAL_TODO.md
├── site/
│   └── SITE_COPY_PTBR.md
├── screenshots/
│   └── SHOTLIST.md
├── synthetic-data/
│   ├── README.md
│   └── SYNTHETIC_DATA_TODO.md
├── reports/
│   ├── PRIVACY_AUDIT.md
│   └── PUBLISH_CHECKLIST.md
└── docs/
    ├── og-social-card.svg
    └── repo-map.svg
```

## 13. Manual public-safe evidence still needed
- Capture mobile-first screenshots with synthetic placeholders
- Validate the public wording around SBAR and handoff support
- Confirm which neutral workflow screen best represents the product
