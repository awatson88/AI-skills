---
name: enterprise-account-org-map-lucidchart
description: Research an enterprise account's business structure and generate a Databricks-branded, editable Lucidchart-compatible account map with a separate people overlay and BU drilldown.
version: 1.0
last_updated: 2026-11-03
---

# Skill: Enterprise Account Intelligence → Lucidchart Org Map

## Purpose

Build a reusable **enterprise account map for a Databricks Account Executive**. The visual must explain how the customer is organized, where its business units, product brands, acquired companies, and shared functions sit, and where Databricks has relationships or opportunities.

**The core design principle is to separate _how the company is organized_ from _who we know_.** Create the business map first with no individuals; use an identical backbone for the people overlay; add a focused drilldown only where there is meaningful sales activity. The deliverable must be **editable after importing into Lucidchart**—not a flattened image.

## Inputs to request or infer

- **Target company:** legal/commonly used name; any key subsidiaries or acquisitions.
- **As-of date:** current unless user specifies otherwise. Record fiscal year conventions.
- **Existing account context:** contacts, names/titles, call notes, screenshots, CRM data, existing diagrams, and Databricks workstreams.
- **Financial display preference:** actual full-year segment revenue if available; otherwise, clearly labeled annualized partial-year estimates when requested. Preserve the user's preferred presentation method.
- **Scope:** top-level structure only, or detailed lines of business/product brands; identify which functions merit a drilldown.
- **Contacts and photos:** public verified LinkedIn/company bios or user-provided photos; never substitute an unverified headshot.

If details are missing, proceed with clearly identified unknowns; do not hold up the entire map for one missing reporting line or headshot.

## Mandatory research workflow

### 1) Verify the financial and operating hierarchy

Use the freshest authoritative sources available, prioritizing:

1. Company 10-K/10-Q, annual report, investor presentation, and official leadership pages.
2. Company acquisition/integration announcements and corporate site.
3. Company product pages and executive bios.
4. Credible third-party reporting or professional profiles for gaps, marked accordingly.
5. User-provided notes and meeting transcripts for **account-specific evidence** (not automatically verified as a public reporting line).

Distinguish these hierarchy types in research and in labels:

| Type | Meaning | Example from Emerson iteration |
|---|---|---|
| Company | Legal/parent enterprise | Emerson |
| Reporting group | Financial/reporting umbrella | Software & Systems |
| Reported segment | Financial reporting unit | Control Systems & Software; Test & Measurement |
| Operating business | BU or managed portfolio | PSS / Process Systems & Solutions; AspenTech |
| Product family | Software/hardware portfolio | DeltaV; Ovation; NI SystemLink |
| Brand | Commercial name, **not necessarily a standalone BU** | Rosemount; Fisher; Micro Motion |
| Enterprise function | Shared governance/services, cross-business | Enterprise IT; Corporate Cybersecurity |
| BU-aligned function | Business-local IT, finance, security, engineering | PSS-aligned IT |

**Never present unlike organizational levels as equivalent reporting siblings without an explicit label.** An acquired company can retain independent product/customer teams while its finance/HR/IT or other corporate functions are integrated. Determine this rather than assuming either full independence or full centralization.

### 2) Map corporate vs. business-specific functions

Research how Enterprise IT, security, finance, technology/AI, procurement, HR, legal, and engineering are organized. Put **centralized/shared functions in a separate visual column**, not as another financial reporting segment. Where BU-aligned roles exist, place them inside or beside the BU and show **dashed relationships** to enterprise functions if justified.

For each important IT/AI opportunity, answer or mark unknown:

- Who owns the **business problem** and budget?
- Who **builds** the application/product?
- Who owns the **platform architecture and cloud environment**?
- Who **approves** software, security, procurement, and new AI models?
- Who **operates/supports** the workload and controls customer data?
- For embedded products, does the customer or OEM operate it, and what is the commercial deployment model?

**Do not turn an approval path into an employee reporting line.** An enterprise CIO/security team may set standards for a BU without being that BU's direct manager.

### 3) Research leaders and existing relationships

For each contact record:

| Field | Notes |
|---|---|
| Name / current title | Verify spelling, title, business association, and date |
| Business placement | Reporting segment + BU/product/function, if known |
| Role type | Business owner / technical builder / IT/security approver / influencer / executive |
| Relationship status | Met, meeting scheduled, intro requested, prospect, unknown |
| Direct reporting line | Verified / tentative / unknown |
| Evidence | User transcript, profile, annual report, official bio, etc. |
| LinkedIn or bio URL | Link to the correct person where verified |
| Photo | Verified public photo / provided photo / initials placeholder |
| Databricks opportunity | Enterprise usage, embedded product, joint customer motion, or unknown |

Use account meeting notes to inform the **relationship map**, while avoiding claims that a transcript proves a formal manager-report relationship.

### 4) Revenue calculation and labeling

Show segment revenue in the segment header (not on every product brand). Prefer audited/official FY figures if available. If using partial-year revenue and the user wants approximate full-year scale:

`Annualized estimate = reported period revenue × (12 / months in period)`

For example, a nine-month revenue figure is multiplied by **4/3**. Display as **`≈ $X.XXB annualized`** and add a conspicuous footnote: **"9M × 4/3; directional size estimate—not reported FY actuals or company guidance."** Record the source date, reporting currency, and fiscal period. Group totals must reconcile to constituent reported segments before rounding. Do not combine fiscal periods or give the estimates false precision.

## Design system

Match the successful Emerson iteration: spacious, crisp, consistent, designed for reuse across a territory.

| Element | Standard |
|---|---|
| Palette | Databricks Navy `#0B2026`, Lava `#FF3621`; Oat `#EEEDE9` and `#F9F7F4`; white; muted blue/gray text |
| Company and main group headers | Navy background, high-contrast white labels; Lava accent stripe |
| Reported segments | Light neutral boxes; clear segment title plus annualized revenue |
| Portfolio/product cards | White/neutral; 1-line name plus short function descriptor |
| Acquired business | Consistent Lava indicator/accent, but distinguish brand from reporting segment |
| Active relationships | Subtle colored accent/highlight; do not over-color every person |
| Enterprise functions | Separate right-side column; note **not a financial segment** |
| Formal grouping | **Solid connectors** for verified hierarchy |
| Portfolio associations / shared services / approvals | **Dashed connectors** with legend; do not imply direct reports |
| Type hierarchy | No tiny text; titles larger than descriptors; keep labels to 1–3 readable lines |
| Sources and confidence | Include an unobtrusive footer, source notes, and uncertain-line legend |

**Keep all main pages aligned** to a consistent grid so the people map visually overlays the portfolio map. A focused BU drilldown can use a different layout but must follow the same palette and legend.

## Required output pages

### Page 1 — Company portfolio (NO individuals)

Show parent company → reporting groups → reporting segments → operating businesses / notable products. Include top-of-chart segment revenue as above, plus the separate shared/corporate functions column. This page must stand on its own and be appropriate for a team account review without confidential contacts.

### Page 2 — People and account coverage overlay

**Duplicate Page 1's backbone and positions**, then add contacts, executive anchors, relationship status, BU-specific functions, and meaningful dotted approval relationships. Use **circular cropped verified headshots** if accessible and licensed/appropriate; otherwise use **consistent editable initials circles**. Make each person’s name and verified profile URL clickable if feasible.

Keep the top-level chart readable. Avoid drawing every possible employee reporting line. Where detail becomes crowded, reference the drilldown rather than shrinking typography.

### Page 3 — Priority business unit / opportunity drilldown

For the most active BU, show: BU/product group; business sponsors; product/engineering delivery; BU-aligned IT/security; corporate IT/security or AI governance; customer IT and data rights when applicable. Use **solid only for verified hierarchy**, dashed for working relationships or approvals. Include 2–3 concrete discovery questions or open hypotheses.

### Reusable blank master

Provide a structurally identical generic template, with replaceable company/segment/product/people cards, so the AE can replicate the process for other accounts.

## Packaging and technical delivery

Primary: **Draw.io / diagrams.net `.drawio`** file using **mxGraph XML**, which Lucidchart can import as editable shapes. Export both:

- `Account_Lucid_Complete.drawio` — 3 named pages: portfolio, people overlay, drilldown.
- `Account_Portfolio_Only.drawio`, `Account_People_Overlay.drawio`, `Account_BU_Drilldown.drawio` — independent imports if multi-page import fails.
- `Reusable_Account_OrgChart_Blank.drawio` — template.
- PNG previews for visual approval (preview images are **not** the editable deliverable).
- Short `Account_Org_Map_README.md` — source list, revenue methodology, confidence notes, people-status legend, and Lucidchart import instructions.

Optional: CSV with parent-child records for a conventional Lucidchart auto-layout org chart, **not** as a replacement for the richer `.drawio` layout. If authoring tools support other editable import formats, keep `.drawio` as the default unless user prefers otherwise.

### Draw.io implementation rules

- Use editable `mxCell` nodes for rectangles, labels, avatars and connectors. Avoid flattening the entire diagram into PNG/SVG.
- Avoid emitting XML/HTML numeric line-break entities into visible text: **the prior Emerson diagram displayed `&#10;` literally inside Lucidchart.** Prefer separate text nodes or clean plain-text labels with wrapping; set `html=0` where practical.
- Encode ampersands and markup correctly at the XML level. Do not double-escape entities.
- Ensure every referenced source/target ID exists and each XML document parses cleanly.
- Keep background connectors behind the boxes; prevent lines crossing important labels. Use consistent grid alignment, spacing, and reasonable font sizes.
- For photos, verify identity first. Embed pictures in an import-compatible, portable way when possible. If that cannot be validated, retain a initials placeholder rather than silently failing or using a mismatched image.
- Do not assert that Lucidchart rendered correctly unless it was actually tested. Report structural validation and PNG preview verification separately.

## QA / acceptance checklist

1. **Accuracy:** Business hierarchy agrees with dated authoritative sources; acquisitions and legacy brands are correctly situated; uncertain organizational connections are identified.
2. **Business vs. people:** Portfolio page has **no individual names**; people overlay uses the same top-level geometry and revenue labels.
3. **Financials:** Estimated vs. reported clearly distinguished; calculations reconcile; fiscal period and source are visible.
4. **Enterprise functions:** Shown as cross-company functions, not a sixth financial segment; BU-aligned IT or engineering is not automatically assumed to report centrally.
5. **Sales utility:** Each key contact has a placement, role, and known/unknown status. Separate (a) internal Databricks adoption, (b) embedded/built-on product, and (c) joint customer motion.
6. **Visual quality:** No overlaps, clipped names, broken alignment, near-invisible fonts, or excessive connector clutter. Preview every page at normal presentation size.
7. **Technical validity:** Parse XML; verify every page and referenced cell ID; scan for visible `&#10;`, `&amp;#10;` or related leaked entities; verify exported file paths exist.
8. **Portability:** Deliver a functioning editable `.drawio`, per-page fallback imports, preview PNGs, and README.
9. **Transparency:** Distinguish verified people/profile photos from placeholders; note anything that was not tested inside Lucidchart itself.

## Short task prompt to reuse

> **Build an editable Databricks-branded Lucidchart account org chart for `[ACCOUNT]`, as of `[DATE]`.** Research the latest reported groups/segments and actual operating businesses and acquired brands; show what they sell. Use confirmed annual revenue or (if applicable) clearly labeled 9-month × 4/3 annualized segment estimates. Put centralized enterprise functions in their own cross-business column, with solid lines for verified reporting and dashed lines for portfolio, shared-service, and approval relationships. Deliver (1) a portfolio view without people, (2) the same layout with my account contacts, roles, verified photos where available and relationship status, and (3) a BU/workstream drilldown. Generate a validated editable `.drawio` multi-page file plus individual fallback pages, PNG previews, a README with sources and uncertainties, and a reusable blank template. Preserve the Databricks Navy/Lava/Oat palette, readability, and the visual style of the Emerson example. Do not show literal XML line-break entities in labels. My existing account contacts and notes: `[PASTE HERE]`.

## Emerson iteration — what we learned

- **Good:** Financial/business hierarchy across five segments, estimated annualized revenue in segment headers, Databricks branding, product-level descriptors, enterprise-functions column, identical portfolio and people backbones, and a PSS drilldown.
- **Important business distinction:** NI is essentially the Test & Measurement segment; AspenTech is a distinct acquired business within Control Systems & Software; brands such as DeltaV and Rosemount are not equivalent management levels. Emerson PSS business-aligned IT should not be mistaken for corporate Enterprise IT.
- **Account-specific evidence:** David Zhang and Nikki Bishop sit on the same PSS/CSS leadership team per David's call; Terry Treadway is described as a PSS IT counterpart, with broader remit and direct manager not verified. The same call distinguishes product-embedded AI from internal HR/finance applications and describes major Databricks approvals as requiring Enterprise IT.
- **Issue fixed:** Earlier `.drawio` export showed literal `&#10;` codes in Lucidchart. Emit clean plain-text labels and validate before delivery.
- **Next improvement:** Add verified public professional headshots and link people cards to source profiles when the identity and usage are clear. Otherwise keep editable initials. Further subdivide crowded orgs on separate drilldowns instead of overloading the portfolio page.

### Example files from this project

Use the final Emerson iteration as visual reference when accessible in the current workspace:

- `Emerson_Databricks_Org_Iteration2.drawio`
- `Emerson_Portfolio_Only.drawio`
- `Emerson_People_Overlay.drawio`
- `Emerson_PSS_Drilldown.drawio`
- `Reusable_Account_OrgChart_Blank.drawio`
- `Emerson_Lucid_Iteration2_README.md`

These are examples, not universally valid company data. Re-research each new account and refresh source dates before generating its map.
