# 03｜Supervisor Matching

This workspace is for comparing potential PhD supervisors, institutions, research groups, and outreach strategies.

## Purpose

Use this folder to decide which supervisors are worth deeper reading, which research groups fit the PhD direction, and how to write targeted outreach emails.

## Recommended Structure

```text
03_Supervisor_Matching/
├── README.md
├── supervisor_shortlist.md
├── decision_matrix.md
├── outreach_strategy.md
├── regional_longlists/
│   └── sweden_norway_denmark_netherlands_v1.md
└── supervisors/
    └── supervisor_name_institution/
        ├── README.md
        ├── fit_analysis.md
        ├── research_alignment_keywords.md
        ├── outreach_strategy.md
        └── papers_to_read.md
```

## Two-Level Supervisor Database Logic

Use two levels:

1. **Regional longlist**: broad country/region-based discovery. Use this before deep reading.
2. **Individual supervisor folder**: create only for A / A- / strong B+ supervisors after the first screening.

This avoids over-investing time in weak candidates while still expanding the application pool.

## Standard Collection Fields

Every new supervisor should be collected using the 14-field structure in `templates/supervisor_profile_template.md`:

1. School / University
2. Department / Centre
3. Supervisor Name
4. Position
5. Personal Profile URL
6. Email
7. Core Themes, 3–5
8. Theoretical Preference
9. Methodological Preference
10. Current PhD / Project Clues
11. Suggested Direction for Vivi
12. Overall Fit, 1–5
13. Priority
14. Application Round / Deadline

## Matching Criteria

1. **Research Theme Fit**: ageing, community, intergenerational relations, digital services, participatory design, responsible AI, inclusive technology.
2. **Methodological Fit**: ethnography, co-design, participatory design, HCI, qualitative research, situated prototyping, service design.
3. **Institutional Fit**: whether the school, lab, or research centre supports cross-disciplinary design research.
4. **Supervision Possibility**: whether the supervisor is active, has relevant funded projects, and may be connected to doctoral openings.
5. **Strategic Fit**: whether the supervisor naturally connects with the applicant’s background in industrial design, ergonomics, design psychology, smart product design, and community-oriented service design.
6. **Outreach Angle**: which project or paper should be used as the entry point for a first email.

## Current Strategy

For each high-priority supervisor, store a separate subfolder under `supervisors/`. This keeps profile notes, fit analysis, keywords, paper-reading priorities, and email strategy together.

After sending 7 emails with 0 replies, switch from a narrow cold-email strategy to a broader but tiered pipeline:

1. Build regional longlists by country.
2. Identify A / A- supervisors.
3. Read 2–3 papers or current project pages before emailing.
4. Track PhD vacancy pages and open calls.
5. Send tailored emails in small waves rather than mass emails.

## Verified profiles and reusable template

- [Supervisor profile template](../templates/supervisor_profile_template.md): canonical 14-field schema, source checks, fit scoring and application workflow. After loading this repository's skill, invoke `supervisor_profile_template: [name or region]`.
- [Verified four-country profiles — 25 candidates/contacts](regional_longlist_sweden_norway_denmark_netherlands.md): checked 2026-09-10; includes sources, existing-name corrections, current project evidence and application eligibility/deadline notes. This is not a list of 25 open PhD positions.
- [Earlier broad discovery list](regional_longlists/sweden_norway_denmark_netherlands_v1.md): retained for additional discovery leads. For overlapping people, use the verified profiles above for current affiliation, contact information and application notes; additional names in the earlier list still require individual verification before outreach.
