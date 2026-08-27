# Therapist Tools

An open-source collection of browser-based tools, calculators, checklists, estimators, and practice resources for therapists, social workers, counselors, and other behavioral health professionals.

The repository now includes searchable, interactive index pages that organize the tools into four practical areas:

- **Clinical Practice** — clinical decision support, documentation, billing/coding, ethics, onboarding, and client-care tools.
- **Practice Planning** — career planning, workload, caseload, rates, income, burnout, and private-practice readiness.
- **Build Your Practice** — niche development, marketing, referrals, revenue, taxes, sliding scale, and practice review.
- **Build a Group Practice** — hiring readiness, compensation, W-2 vs. 1099 comparisons, and solo-to-group-practice planning.

## Interactive tool library

The root `index.html` provides the English tool library. A Chinese-language version is available at `zh/index.html`.

Both index pages include:

- Search and category filtering
- Responsive tool-card layouts
- Inline tool expansion without navigating away from the library
- Isolated iframe loading so each tool's HTML, CSS, and JavaScript can run without interfering with other tools
- Mobile-friendly controls and layouts
- Keyboard focus states and reduced-motion support

The individual tool source files remain separate from the index pages. When a user opens a tool, the index loads that tool into an isolated embedded frame on the same page.

## Languages

- **English:** root tool files and `index.html`
- **简体中文:** Chinese tool files and `zh/index.html`

## Privacy

The tools are designed to run in the browser without user accounts or a project database. Users should avoid entering protected health information (PHI), personally identifiable information (PII), or other sensitive client information unless a specific tool and deployment environment have been independently reviewed for that use.

## Important note

These resources are intended for educational, clinical-support, and practice-management purposes. They do not replace clinical judgment, legal advice, tax advice, professional ethics consultation, or payer-specific requirements.

## Demo and additional resources

For the curated Mind X Associates collection and additional therapist resources, visit:

https://www.mindx.us/resources/for-therapists/free-tools

Maintained by **Mind X Associates**.