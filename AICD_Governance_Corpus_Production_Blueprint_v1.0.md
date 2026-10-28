# Australian Corporate Governance and Directorship Research Corpus
## Stage 1: Master production blueprint and editorial specification

**Specification status:** Proposed for review; no corpus file has been authored.
**Specification version:** 1.0.0-draft
**Evidence cutoff and law verification date:** 27 October 2026 (Australia/Perth)
**AICD curriculum vintage:** Company Directors Course 2025/26, V1, except differently dated standalone references.
**Output architecture:** Exactly nine Markdown knowledge files (00-08), with no permanent tenth file. This blueprint is a separate temporary production-control document.
**Primary intended use:** Private retrieval and synthesis within a Gemini Notebook.

## A. Controlling editorial decisions

1. **Equal utility, not false equivalence.** General directors' responsibilities are taught once, and their distinct legal manifestations are mapped for (a) ordinary Corporations Act companies including ASX entities, (b) charities, not-for-profits and state incorporated associations, and (c) CATSI Act corporations and RNTBC/PBCs. Do not imply one statute regulates all organisations.
2. **Concept first, curriculum preserved in traceability.** The main files integrate topics across the curriculum. A complete curriculum crosswalk and individual tool/case ledgers must preserve all substantive source coverage, even when a topic is covered outside the AICD unit where it originally appeared.
3. **Historical teaching and live law are independent layers.** Record `AICD 2025/26 approach` separately from `Law/regulator position verified on [date]`; record an explicit delta if they differ. A draft proposal is never represented as operative law.
4. **Authorities differ.** Label statutory or delegated law, case law, binding listing/prudential requirements, regulator interpretation, voluntary governance standard, cultural governance principle, analyst inference and historical course pedagogy separately.
5. **Practical usefulness.** Explain not only what a director must understand, but what evidence to request, how to probe it, what decision is reserved to the board, what can be delegated, and what to minute and monitor.
6. **Indigenous governance is neither an appendix nor a generic template.** Apply Aboriginal and Torres Strait Islander governance throughout the corpus; provide deep CATSI/RNTBC coverage in 07; attribute community-specific practices to the originating people/organisation and do not invent customary rules.
7. **Copyright-safe synthesis.** Draft original explanations and new analytical checklists. Preserve titles, framework names and short attributions but do not reproduce course chapters, long exercises, slide diagrams or proprietary templates wholesale. The source PDFs remain a private reference library, not corpus content.
8. **Retrieval quality is a release requirement.** Each section is independently legible, uses a stable section identifier, carries its evidence locally and cross-refers to related sections without relying on previous conversational context.

## B. Inventory and accessibility assessment

**Inventory outcome:** 24 mounted and readable PDF files, 1,363 physical PDF pages. Every PDF opens and has machine-extractable text (including a few intentionally blank pages). There is one exact binary duplicate pair, leaving 23 distinct PDF byte streams / 1,224 pages. Several other files are substantively repeated as excerpts or appendices; unique page count therefore exceeds truly unique instructional content.

**Local source aliases** (use consistently throughout the project):

| ID | Uploaded PDF (exact filename) | PDF pages | Treatment and main destination |
|---|---|---:|---|
| GOV | `01 Governance and the Practice of Directorship - Course notes.pdf` | 104 | Core original, 01,02,06,07,08 |
| LEG | `02 The Legal Environment - Course notes.pdf` | 122 | Core original, printed main text pp1-121 plus final blank, 01,02,06,07,08 |
| RISK | `03 Risk and Strategy - Course notes.pdf` | 184 | Core original, 03,02,07,08 |
| FIN | `04 Financial Literacy and Peformance - Course notes.pdf` | 182 | Printed main notes pp1-126 and appended Nick Scali report 56 pp, 04,05,08. Filename contains `Peformance` typo. |
| IFS | `05 Interpreting Financial Statements - Course Notes.pdf` | 71 | Core additional course, pp1-50 and repeated annexes pp51-71, 04,05,08 |
| BE | `06 Achieving Board Effectiveness - Course notes.pdf` | 112 | Core original, printed pp1-111 plus final blank, 02,01,07,08 |
| TOOL | `07 Director tools - Compiled.pdf` | 139 | Canonical 48-tool collection, 08 plus thematic files |
| TOOL-DUP | `Director tools - Compiled - Copy.pdf` | 139 | Exact SHA-256 duplicate of TOOL; omit as redundant source |
| GAPP | `Governance and the Practice of Directorship - Appendices.pdf` | 33 | ASX 4th principles, code, charters, cases, 01,02,06,08 |
| LAPP | `The Legal Environment - Appendices.pdf` | 14 | Penalties; March 2024 comparative state/CATSI table; disclosure; NFP/CATSI, 01,06,07,08 |
| RAPP | `Risk and Strategy - Appendices.pdf` | 35 | Emerging risks, foresight, risk appetite example, ERM standards, NFP/public strategy, 03,06,07,08 |
| FAPP | `Financial Literacy and Performance - Appendices.pdf` | 14 | Financial glossary and 2024 Surf Life Saving Queensland NFP accounts, 04,05,06,08 |
| GSH | `Governance and the Practice of Directorship - Slides handout.pdf` | 25 | Teaching emphasis incl. Costa Group case and governance frameworks, 01,02,06,08 |
| LSH | `The Legal Environment - Slides handout.pdf` | 23 | Teaching emphasis and case questions, 01,08; some 2024/25 headers |
| RSH | `Risk and Strategy - Slides handout.pdf` | 24 | Strategy and risk diagrams, exercises, case questions, 03,08 |
| FSH | `Financial Literacy and Performance - Slides handout.pdf` | 25 | Numeric methods, Nick Scali worked analysis, 04,05,08 |
| NICK | `Financial Literacy and Performance - Nick Scali Annual Report extract.pdf` | 56 | Same report appended to FIN; retain as individually navigable illustration, not extra unique text |
| DISC | `2024 Annual Report Extracts.pdf` | 5 | Discount Depot fictional 2024 statements, reproduced within IFS pp51-55; note internal cover metadata discrepancy |
| FIFTY | `50 Matters to be Considered before Signing off a Company's Financial Statements.pdf` | 12 | **2016 third edition**; historical perspective, cross-check with TOOL pp47-52 and current law; 05,08 |
| HEALTH | `Financial health checklist.pdf` | 5 | Repeated in IFS pp56-60; pedagogical heuristics, 04,08 |
| GLOSS | `Glossary of terms.pdf` | 7 | Repeated in IFS pp61-67; terminology support, 00,04,05 |
| METHOD | `Methodologies for reviewing financial statements.pdf` | 4 | Repeated in IFS pp68-71; 7-step/4-step/5-step methods, 04,08 |
| EXEMP | `AICD_Assignment exemplar.pdf` | 4 | Short, non-exhaustive exemplar of scenario analysis, 08 |
| ASSESS | `AICD_cdc-participant-assessment-guide.pdf` | 24 | Course context and assessment integrity, 00,08; not generic substantive law |

**Hash evidence:** TOOL and TOOL-DUP share SHA-256 beginning `d6a74c47f87b`; the canonical file is TOOL. Use full SHA-256 values in the later final source manifest; page count is PDF physical pages, not necessarily printed folio.

**Section-level duplicates:** IFS 51-55~DISC; 56-60~HEALTH; 61-67~GLOSS; 68-71~METHOD. FIN 127-182~NICK. These are equivalent content or near-identical extracted text, not identical PDF bytes. Keep separate source records; do not draft the same lesson twice.

**Source warnings to preserve:** The comparative legislation table in LAPP p5 is marked current as at **March 2024**; use it as historical teaching only until state-by-state re-verification. FIFTY is **October 2016**, not a statement of 2026 law. Some slides retain 2024/25 slide footers despite 2025/26 packaging. One Discount Depot 2024 statement shows a `3 July 2024` line where a 30 June roll-forward is implied; check source before using. The names of fictional AICD case organisations and hypothetical facts must be clearly labelled.

**Academic integrity:** ASSESS (2025/26, printed pp4-6) states that submitting AI- or third-party-produced work as one's own for course assessment is academic misconduct. This private research corpus is for independent learning, not assessment submission or circumvention of that rule.

**Not available in the uploaded PDF set:** separately delivered `The Director Mindset` eLearning, the `NRGworks` case packet referenced by LEG, the full for-profit and NFP assessment case-study packs, mock exams/quizzes and practice-exam exemplar, and separate board-effectiveness handout/appendices if they exist. These are *not evidenced as uploaded*. Do not invent their contents, and log the gap without blocking this blueprint.

## C. Comprehensive curriculum source-to-topic-to-file matrix

The range after each source ID refers to **printed AICD course pages**, unless `PDF` is stated. A plus sign in a destination means a distinct conceptual cross-application rather than redundant rewriting. `08` contains practical applications/cases/tools; a concept's canonical explanation stays in its thematic file. `00` houses source metadata and index, not substantive exposition.

| Coverage code | Original source and page(s) | Detailed curriculum/topic scope to preserve | Primary file | Secondary file(s) |
|---|---|---|---|---|
| C01 | GOV 9-20; GAPP 32-33 | Legal and corporate environment; incorporation; public/proprietary/limited by guarantee/cooperative/association/statutory forms; separate personality; constitution, replaceable rules; governance titles | 01 | 06,07 |
| C02 | GOV 21-34; GSH 20-23 | Legal/de facto/shadow/alternate directors, officers; role profiles; appointments, selection, onboarding, competence, paid/unpaid status, departures, disqualification, board-entry diligence | 01 | 02,08 |
| C03 | GOV 35-51; GAPP 1-10; GSH 12-15 | Corporate governance definitions; separation of ownership/control; AICD Corporate Governance Framework; Tricker board roles; listed ASX 4th edition and reporting approach; APRA, ISO, coops, ACNC and NFP frameworks | 01 | 02,06,07 |
| C04 | GOV 46-49; 82-83; RISK 16-18; BE 79 | Aboriginal/First Nations governance references in core curriculum; dual accountabilities, cultural legitimacy, stakeholders, risk framing, deliberation/consensus | 07 | 01,02,03 |
| C05 | GOV 52-59; GSH 24-25 | Board essential roles, reserved powers, governance-management boundary, size, composition, independence, board as social system | 01 | 02,06,07 |
| C06 | GOV 59-79; GAPP 13-19 | Transparency, accountability, board reports and agendas, calendars, meetings, minutes, committees, charters, delegations, advisory boards, director information rights | 02 | 01,08 |
| C07 | GOV 80-88 | Stakeholder mapping, shareholders/members, employees, consumers, investors, governments, First Nations and communities, engagement and legitimacy | 01 | 02,06,07 |
| C08 | GOV 89-99; GSH | Ethics, performance/risk/safety/integrity/remuneration cultures, tone from top, culture measurement, trust | 02 | 01,03,06,07 |
| C09 | GOV 103; GSH 17-19 | Positive Impact Centre and Costa Group board composition and development examples | 08 | 02,06 |
| C10 | LEG 11-17; LSH 7 | Constitutions, contractual obligations, CEO contract, delegation instruments, policies and internal compliance architecture | 01 | 02,06,07,08 |
| C11 | LEG 18-25 | Pre-appointment diligence, statutory directors/officers, duties owed to whom, legal and fiduciary sources, personal accountability | 01 | 06,07 |
| C12 | LEG 25-37; LSH 8-13 | Good faith and proper purpose, best interests and stakeholder considerations, subsidiaries, conflicts and related parties, misuse of position/information, insider trading, phoenix risk | 01 | 06,07,08 |
| C13 | LEG 38-46; LSH 15-18 | Objective care/diligence, reliance/advice, collective vs individual duties, business judgment rule, case law including Centro and James Hardie | 01 | 05,08 |
| C14 | LEG 47-54; LSH 19-21 | Insolvent trading, safe harbour, relevant defences and limits, NFP/government overlays, prudent documentary conduct | 01 | 04,06,07,08 |
| C15 | LEG 55-73; LAPP 1-4 | Compliance and speak-up culture; compliance lifecycle; civil/criminal consequences and relief; D&O insurance, deeds of access/indemnity, record access | 01 | 02,08 |
| C16 | LEG 75-89; LSH | Workplace health and safety incl psychosocial hazards, industrial relations/wages, modern slavery, discrimination/harassment, whistleblower protections | 01 | 02,03,06,07,08 |
| C17 | LEG 90-102; LAPP 6-8 | Anti-bribery, environment, climate law, IP, competition, consumer law, unfair contracts, Indigenous consumer protection, continuous disclosure | 01 | 03,05,06,07 |
| C18 | LEG 103-112; RAPP 3-7 | Privacy, data protection and retention, cyber controls and breaches, AI governance, digital disruption, technology oversight | 03 | 01,02,06,07,08 |
| C19 | LAPP 5; 9-14 | Comparative incorporated-association statutes and CATSI, government and charity legal distinctions; verify jurisdiction by jurisdiction | 01 | 06,07 |
| C20 | LEG 117-121 | Loca Soft Drinks, GBH Mining, Workplace Resolution hypotheticals | 08 | 01,02,03 |
| C21 | RISK 11-18; RSH 5-7 | Integrating strategy, risk, performance, culture; oversight vs management; First Nations approaches | 03 | 07 |
| C22 | RISK 19-37; RSH 8-14 | Defining strategy; organisational purpose and value; long-run integrated choices; business model; strategic board; competitive position and five strategic choices | 03 | 06,07 |
| C23 | RISK 38-62; RAPP 8-13 | Plan-to-plan and strategic development; horizon scanning, external/internal assessment, trends, scenarios, foresight, board-management workshops, stakeholder value | 03 | 08 |
| C24 | RISK 63-70; RSH 20-22 | Strategy approval, alternatives, due diligence, capital/people/data/operational readiness, analytical and ethical decision gates | 03 | 04,08 |
| C25 | RISK 71-86; RSH 22-25 | Strategy execution, organisational alignment, leading/lagging performance measures, dashboard, strategic review triggers, board decisions | 03 | 04,08 |
| C26 | RISK 87-110; RSH 12-24 | Risk definitions, uncertainty, classifications, materiality, appetite/capacity/tolerance, linked thresholds and governance reporting | 03 | 01,06,07,08 |
| C27 | RISK 111-145; RAPP 14-22 | ERM ISO 31000/COSO; three lines model; committees, risk ownership, controls, assurance, aggregation, reporting and escalation | 03 | 05,08 |
| C28 | RISK 146-166; RAPP 1-7 | Risk culture/maturity, crisis command, business continuity, resilience, recovery/lessons, emerging tech, cyber and environmental risks | 03 | 02,06,07,08 |
| C29 | RAPP 23-35 | NFP strategy and government/public-sector risk and strategy nuances; adapt to charity/CATSI contexts without importing public-sector obligations | 03 | 06,07 |
| C30 | RISK 173-184 | Biscuit Makers of Australia gluten-free/keto case and CBA/APRA prudential inquiry case | 08 | 03,02 |
| C31 | FIN 11-22; IFS 5-11; FSH 5-8 | Director financial literacy, board information, three-way forecasts, management/statutory accounts, control environment | 04 | 05,08 |
| C32 | FIN 23-37; IFS 5-7; FSH 9 | Entity reporting duties, annual report, directors report/declaration, consolidated disclosure, true/fair, financial-sign-off cases | 05 | 01,04,06,07 |
| C33 | FIN 38-44; FSH 10 | Internal audit, external audit, independence, audit/risk committees, assurance limitations, audit reports | 05 | 02,08 |
| C34 | FIN 45-49 | Mandatory climate reporting and sustainability disclosures, phased entity scope, assurance, law changes since curriculum | 05 | 03,06,07 |
| C35 | FIN 50-79; IFS 12-38 | Assets, liabilities, equity, accruals, profit, operating cash, statement linkages, consolidation, impairments, inventory, lease liabilities, tax, intangible assets, ratios, notes | 04 | 05,08 |
| C36 | FIN 80-89; FAPP 1-6; GLOSS | Liquidity, efficiency, gearing, profitability, NFP ratios; numerator/denominator logic, interpretation and benchmarks | 04 | 06,07,08 |
| C37 | FIN 90-100; IFS 27-34 | Distress warnings, cash insolvency, creditor exposures, safe harbour, restructuring, administration, liquidation, directors' options | 04 | 01,06,07,08 |
| C38 | FIN 105-126; NICK; FSH 13-25 | Nick Scali two analyses, Godfreys distress, 2024 company report and worked 2021-24 trends | 08 | 04,05 |
| C39 | IFS 39-71; DISC; HEALTH; METHOD | Knowledge-check answers, fictional Discount Depot financials, financial health checklist, balance sheet 7-step/income 4-step/cash 5-step interpretation | 08 | 04,05 |
| C40 | FAPP 7-14 | Surf Life Saving Queensland 2024 statements: NFP revenue, grants, cost, liquidity, reserves, financial analysis | 06 | 04,05,08 |
| C41 | BE 9-32 | Board effectiveness and value, cognitive blind spots, self-awareness, unconscious bias, intuition, reasoned deliberation and director contribution | 02 | 08 |
| C42 | BE 33-71 | Board as team; psychological safety and diversity of thought; inclusion, chair-CEO relationships, teamwork, communication styles, conflict/groupthink | 02 | 07,08 |
| C43 | BE 72-88 | Complexity and decision frameworks, ethics, deliberation, consensus, decisions under uncertainty, AI and digital practice | 02 | 03,07,08 |
| C44 | BE 89-104 | Meeting debriefs, formal board and committee assessments, individual effectiveness, culture audits and remediation | 02 | 06,07,08 |
| C45 | BE 107-111 | Early Gifts Limited and XYZ Sport governance/group-effectiveness cases | 08 | 02,06 |
| C46 | GAPP 20-31 | Slater & Gordon and HIH failures as historical governance/compliance/financial accountability examples | 08 | 01,03,04,05 |
| C47 | GAPP 11-19; LAPP 1-8; RAPP 14-22 | Membership conduct, governance charter, meeting technology, past legal sanctions, disclosure and example appetite/maturity guidance | 01 | 02,03,08 |
| C48 | TOOL 3-139; FIFTY 1-12 | All 48 director tools, model decisions, financial-sign-off and board processes (see complete tool ledger below) | 08 | 01-07 |
| C49 | EXEMP 1-4; ASSESS 1-24 | Director-mindset issue analysis, scenario decision, influencing others; 2025/26 assessment context and academic integrity | 08 | 00 |

**Coverage rule:** C01-C49 is a traceable first-pass register, not the final subheading-by-subheading reconciliation. At drafting, every AICD course numbered subsection and each slide/appendix distinct topic must gain an entry in the lower-level coverage ledger with one `canonical section` and at least one full, pinpoint AICD citation. Administrative copyright/learning-objective pages can be marked `metadata`, not omitted silently.

### C1. Complete director-tools coverage ledger

Every item below receives a practical, **original** reconstruction of its intended function in `08`, with pinpoint attribution and a link to its substantive explanation. The original template is not duplicated. Page is the start page in the 139-page PDF; the next tool's start page establishes its end boundary. Preserve the exercises on the final page.

| No. | TOOL printed page | Named tool / topic | Concept owner | Practical destination |
|---:|---:|---|---|---|
| 01 | 3 | Annual board calendar | 02 | 08.T01 |
| 02 | 12 | ASIC's suggested questions for large ASX boards | 03 | 08.T02 |
| 03 | 14 | Assessing board composition checklist | 02 | 08.T03 |
| 04 | 16 | Assess your risk maturity | 03 | 08.T04 |
| 05 | 17 | Audit committee charter | 05 | 08.T05 |
| 06 | 24 | Board meeting agenda | 02 | 08.T06 |
| 07 | 27 | Board meeting debrief | 02 | 08.T07 |
| 08 | 29 | Board meeting preparation/observer instructions | 02 | 08.T08 |
| 09 | 30 | Board questions on risk appetite statements | 03 | 08.T09 |
| 10 | 31 | Bullying checklist | 01/02 | 08.T10 |
| 11 | 32 | Competition law | 01 | 08.T11 |
| 12 | 33 | Cybersecurity checklist | 03 | 08.T12 |
| 13 | 34 | Decision stages framework | 02 | 08.T13 |
| 14 | 36 | Delegations schedule, matters reserved to board | 01/02 | 08.T14 |
| 15 | 39 | Developing strategy in turbulent times | 03 | 08.T15 |
| 16 | 41 | Director and officer insurance checklist | 01 | 08.T16 |
| 17 | 42 | Evaluating an organisation before joining | 01 | 08.T17 |
| 18 | 47 | Fifty matters before financial sign-off | 05 | 08.T18 |
| 19 | 53 | Financial health checklist | 04 | 08.T19 |
| 20 | 58 | Financial ratios for NFP entities | 04/06 | 08.T20 |
| 21 | 60 | General duties of directors | 01 | 08.T21 |
| 22 | 66 | Generic questions to ask yourself as director | 01 | 08.T22 |
| 23 | 68 | Governing organisational culture | 02 | 08.T23 |
| 24 | 81 | Guide to preparing a board skills matrix | 02 | 08.T24 |
| 25 | 89 | Headline risk questions for the board | 03 | 08.T25 |
| 26 | 91 | Establishing risk appetite and tolerance | 03 | 08.T26 |
| 27 | 93 | Intellectual property types/checklist | 01 | 08.T27 |
| 28 | 95 | Lessons from James Hardie and Centro | 01/05 | 08.T28 |
| 29 | 97 | Managing uncomfortable debate | 02 | 08.T29 |
| 30 | 98 | Privacy checklist | 01/03 | 08.T30 |
| 31 | 100 | Processes to aid decision-making | 02 | 08.T31 |
| 32 | 102 | Pro forma strategic plan | 03 | 08.T32 |
| 33 | 104 | Questions to understand culture | 02 | 08.T33 |
| 34 | 105 | Questions on disruptive risks | 03 | 08.T34 |
| 35 | 106 | Sexual harassment prevention/response questions | 01/02 | 08.T35 |
| 36 | 108 | Quick guide to financial ratios | 04 | 08.T36 |
| 37 | 109 | Remuneration committee charter | 02 | 08.T37 |
| 38 | 113 | Risk committee charter | 03 | 08.T38 |
| 39 | 118 | Sample board minutes | 02 | 08.T39 |
| 40 | 121 | Sample board paper | 02/03 | 08.T40 |
| 41 | 124 | Solvency key questions for directors | 04 | 08.T41 |
| 42 | 125 | Sustainability committee charter | 03/05 | 08.T42 |
| 43 | 128 | Testing your risk personality | 02/03 | 08.T43 |
| 44 | 129 | AICD Corporate Governance Framework | 01 | 08.T44 |
| 45 | 131 | Director styles, 'Convincer' strategies | 02 | 08.T45 |
| 46 | 133 | What is your risk competency? | 03 | 08.T46 |
| 47 | 136 | What is your strategic competency? | 03 | 08.T47 |
| 48 | 139 | Work health and safety actions | 01 | 08.T48 |

### C2. Case-study and worked-example coverage ledger

| Case ID | Source pinpoint | Context and practical learning | Canonical file |
|---|---|---|---|
| CASE-01 | GOV p103 | Positive Impact Centre Limited: governance/organisation situation | 08.C01; 01/06 cross-reference |
| CASE-02 | GSH pp17-19 | Costa Group Holdings: scaling, board composition and skill needs | 08.C02; 02 cross-reference |
| CASE-03 | GAPP pp20-25 | Slater & Gordon: listed-company governance/financial conduct | 08.C03; 01/05 cross-reference |
| CASE-04 | GAPP pp26-31 | HIH: board oversight, risk and reporting failure | 08.C04; 01/03/05 cross-reference |
| CASE-05 | LEG p117; LSH pp14 | Loca Soft Drinks: duties, conflicts, commercial claims/greenwashing | 08.C05; 01 cross-reference |
| CASE-06 | LEG p119; LSH pp18 | GBH Mining: business judgment/diligence | 08.C06; 01/03 cross-reference |
| CASE-07 | LEG p121 | Workplace Resolution Limited: workplace governance and compliance | 08.C07; 01/02 cross-reference |
| CASE-08 | RISK pp173-179; RSH p24 | Biscuit Makers of Australia: strategy and product risk decisions | 08.C08; 03 cross-reference |
| CASE-09 | RISK pp180-184; RSH p8 | Commonwealth Bank/APRA prudential inquiry: accountability, culture, risk | 08.C09; 03/02 cross-reference |
| CASE-10 | RAPP pp14-17 | CQUniversity risk appetite example: application, limitations and measurement | 08.C10; 03/06 cross-reference |
| CASE-11 | FIN pp105-112; FSH pp13-25 | Nick Scali exercise 1 and the 2024 report, including 2021-24 trends | 08.C11; 04/05 cross-reference |
| CASE-12 | FIN pp113-114 | Nick Scali exercise 2 | 08.C12; 04/05 cross-reference |
| CASE-13 | FIN pp115-126 | Godfreys Group: financial position and distress | 08.C13; 04 cross-reference |
| CASE-14 | IFS pp51-55; DISC pp1-5 | Discount Depot hypothetical FY2024 integrated statements | 08.C14; 04 cross-reference |
| CASE-15 | FAPP pp7-14 | Surf Life Saving Queensland FY2024: NFP financial sustainability | 08.C15; 06/04 cross-reference |
| CASE-16 | BE pp107-108 | Early Gifts Limited: NFP/board effectiveness | 08.C16; 02/06 cross-reference |
| CASE-17 | BE pp109-111 | XYZ Sport: board effectiveness | 08.C17; 02 cross-reference |
| CASE-18 | TOOL pp95-97, LAPP pp1-4 | James Hardie/Centro court outcome lessons; clearly distinguish cases from fictional studies | 08.C18; 01/05 cross-reference |
| CASE-19 | EXEMP pp1-4 | SM Productions assignment exemplar: issue/rationale/question/recommendation/outcome/influence method, not an authoritative model answer | 08.C19 |

**Case-writing rule:** A legal reported case needs its holding, procedural history and judicial pinpoint verified against a court judgment. A fictional AICD case needs explicit `Teaching hypothetical` labelling. A historic annual report is an example of a period, not an endorsement of the company's present position. Respect AICD's copyright when explaining the situation, and do not reproduce the full exercise fact pattern or published suggested responses.

## D. Authoritative public source acquisition and update register

### D1. Authority hierarchy and editorial treatment

| Class | Type / example | Evidentiary use | Authority status |
|---|---|---|---|
| A | Enacted Act and operative regulation / ASX Listing Rule / binding APRA prudential standard for supervised entity | Determine legal obligation and scope | Binding for identified entities only; check amendments and commencement |
| B | Reported court judgment | Determine legal interpretation or authoritative illustration | Binding only with jurisdiction, ratio, subsequent treatment and facts considered |
| C | ASIC, ACNC, ORIC, state regulator formal guidance | Interpret administration, reporting, expectations, relief and practical compliance | Regulatory guidance, not itself a general statute |
| D | AASB standards and Australian auditing standards | Determine applicable measurement, reporting or assurance requirement | Binding to the extent applicable law/adoption imposes them |
| E | ASX Corporate Governance Principles; AICD NFP principles; ISO; COSO; AIGI toolkit | Good-practice and culturally informed design | Recommendations/principles; do not call universal law |
| F | AICD 2025/26 course notes, appendices, slides and tools | Evidence of what was taught and practical pedagogy | Historical/private curriculum; not updated legal authority |
| G | Editorial reasoning and example numbers | Explain trade-offs, construct original tools and worked examples | Clearly labelled analytical interpretation/illustration |

**Snapshot, not perpetual currency:** Links below were checked for existence/relevance on 27 October 2026. Before publishing a legal proposition, verify its exact section, commencement, amendments, prospective provisions, exemptions, regulator updates and interpretation. Log the date and version used. An online compilation marked `latest` can change and is not a substitute for a version identifier.

### D2. Mandatory foundation: statutes and legal systems

| Source ID | Primary law / authority | Verified official starting point and current marker | Where needed |
|---|---|---|---|
| LAW-CORP | `Corporations Act 2001` (Cth) | https://www.legislation.gov.au/C2004A00818/latest ; as at review compilation **C2026C00432, C149, 19 Sep 2026**. Relevant ss 9, 180-184, 191-195, 198A, 248A, 295, 296-307, 344, 588G, 588GA, 588H, 588V, 674/675, 1317 etc; exact applicability to be checked | 01,04,05,06 |
| LAW-CORPREG | `Corporations Regulations 2001` | https://www.legislation.gov.au/F2001B00274/latest ; relevant rules and forms after section verification | 01,05 |
| LAW-CATSI | `Corporations (Aboriginal and Torres Strait Islander) Act 2006` | https://www.legislation.gov.au/C2006A00124/latest ; compilation **C2025C00681, C27, 5 Dec 2025**; corporate governance, director duties, rule books, meetings, reporting, related-party and solvency regimes | 01,04,06,07 |
| LAW-CATSIREG | Regulations and rules made under CATSI | Locate through official CATSI Act authorised instruments and ORIC; verify title and operative text rather than inferring Companies Act provisions | 07 |
| LAW-ACNC | `Australian Charities and Not-for-profits Commission Act 2012` | https://www.legislation.gov.au/C2012A00168/latest ; compilation **C2025C00665, C11, 5 Dec 2025** | 01,05,06,07 |
| LAW-ACNCREG | `Australian Charities and Not-for-profits Commission Regulations 2022` | https://www.legislation.gov.au/F2022L01301/latest ; includes Governance Standards and External Conduct Standards; compilation **F2023C01018, C01, 1 Nov 2023** | 06,07 |
| LAW-NATIVE | `Native Title Act 1993` (Cth) | https://www.legislation.gov.au/C2004A04665/latest ; check operative version at drafting | 07 |
| LAW-PBC | `Native Title (Prescribed Bodies Corporate) Regulations 1999` | https://www.legislation.gov.au/F1999B00146/latest ; **F2024C00961, C05, 14 Oct 2024** as at review; decision/consent/certification context | 07 |
| LAW-WA-ASSOC | `Associations Incorporation Act 2015` (WA), related Regulations 2016 | https://www.legislation.wa.gov.au/legislation/statutes.nsf/main_mrtitle_13715_homepage.html and https://www.legislation.wa.gov.au/legislation/statutes.nsf/main_mrtitle_13764_homepage.html ; Act current consolidated from 23 Aug 2025 and regulations from 1 Jul 2026 | 01,05,06 |
| LAW-8-ASSOC | State and territory incorporated-association regimes | NSW `Associations Incorporation Act 2009`; Victoria `Associations Incorporation Reform Act 2012`; Queensland `Associations Incorporation Act 1981`; ACT `Associations Incorporation Act 1991`; Tasmania `Associations Incorporation Act 1964`; Northern Territory `Associations Act 2003`; South Australia `Associations Incorporation Act 1985`; WA as above. **Independently verify each current version** | 01,06 |
| LAW-WHS-EMP | Work health and safety, employment, discrimination and whistleblower regimes | Verify applicable Commonwealth and each state/territory WHS scheme, Safe Work Australia model laws, Fair Work Act 2009, WHS industrial manslaughter, psychosocial risk regulations, Fair Work Ombudsman, human rights/equality, Corporations Act whistleblower provisions | 01,02,06,07 |
| LAW-COMPLIANCE | Operations/consumer/information regimes | `Competition and Consumer Act 2010` incl Australian Consumer Law; `Privacy Act 1988` incl Notifiable Data Breaches; `Modern Slavery Act 2018`; foreign bribery criminal law; environmental protection, IP, anti-discrimination, data-security regulations as relevant | 01,03,06,07 |

**Legislation notes:** The 2025/26 AICD course groups many obligations together as general director governance principles. The corpus must not claim statutory duties of Australian company directors automatically bind every association office-holder or CATSI director under the same section. Separately check directorship, committee membership, trustee status and charity Responsible Person status. For a charity limited by guarantee, check the ACNC-registered charity modifications/disapplications to general Corporations Act civil duties and the continued application of relevant criminal/general law rules; do not merely state `all Corporations Act duties apply`.

### D3. Primary regulators, governance and standards

| Source ID | Authoritative source and URL | Scope and publication assignment |
|---|---|---|
| REG-ASIC-FIN | ASIC Information Sheet 183, Directors and financial reporting: https://asic.gov.au/regulatory-resources/financial-reporting-and-audit/directors-and-financial-reporting/ | Financial literacy, personal sign-off and auditor relations, 04/05 |
| REG-ASIC-INSOLV | ASIC Regulatory Guide 217, duty to prevent insolvent trading (issued Dec 2024): https://asic.gov.au/regulatory-resources/find-a-document/regulatory-guides/rg-217-duty-to-prevent-insolvent-trading-guide-for-directors/ | Corporations Act safe harbour, distinction from CATSI/association issues, 01/04 |
| REG-ASIC-CLIMATE | ASIC Regulatory Guide 280, sustainability reporting (issued Mar 2025): https://www.asic.gov.au/regulatory-resources/find-a-document/regulatory-guides/rg-280-sustainability-reporting | Scope/phasing/ASIC approach, 05 |
| REG-ASIC-FOCUS | ASIC 2026/27 focus areas: https://www.asic.gov.au/regulatory-resources/financial-reporting-and-audit/financial-reporting-and-audit-focus-areas | Reporting estimates, asset valuation, provisions, audit and climate, 05 |
| REG-ASX-PRIN | ASX governance principles: https://www.asx.com.au/about/regulation/corporate-governance-principles-and-recommendations | **Fourth edition operative as at 27 Oct 2026**; fifth edition 2026 consultation draft not yet operative, 01/02/05 |
| REG-ASX-RULES | ASX Listing Rules, Guidance Notes 8 and 9 and Appendix 4G, accessible from ASX listed-entity rules pages | Rules 3.1, 4.10.3, disclosure and governance explanations; record relevant version, 01/05 |
| REG-ACNC-GOV | ACNC Governance Standards 1-6: https://www.acnc.gov.au/for-charities/manage-your-charity/governance-hub/governance-standards | Registered charities only, explain Standard 5 obligation on charity to take reasonable steps with Responsible People, 06 |
| REG-ACNC-SIZE | ACNC charity size: https://www.acnc.gov.au/tools/topic-guides/charity-size | As at 2026 small `<$500k` revenue; medium `$500k-<$3m`; large `>=$3m`; assess exceptions, 06/05 |
| REG-ACNC-REP | ACNC annual reporting and audit: https://www.acnc.gov.au/for-charities/manage-your-charity/obligations-acnc/reporting-annually-acnc | Medium reviewed or audited and large audited; distinguish ORIC reporting substitution, Basic Religious Charity and exemptions, 06 |
| REG-ORIC-SIZE | ORIC size criteria: https://www.oric.gov.au/for-corporations/corporate-governance/corporation-size | Two of three size tests: income, assets, staff; not equal to ACNC revenue classification, 07 |
| REG-ORIC-REPORT | ORIC reporting navigator: https://admin.oric.gov.au/for-corporations/reporting-and-stakeholders/annual-reporting/what-reports-you-need-lodge | Size **plus consolidated gross operating income**; general/financial/audit/directors report; exemptions and grant accommodation, 07/05 |
| REG-ORIC-RNTBC | ORIC 2026 decision-making in RNTBCs: https://www.oric.gov.au/for-corporations/decision-making/decision-making-RNTBCs | Decision authority: native title and compensation versus corporate/operational; common law holder consultation and consent, certificate; updated 12 Oct 2026, 07 |
| REG-ORIC-HOLD | ORIC native title common law holders: https://admin.oric.gov.au/for-corporations/roles-and-responsibilities/native-title-common-law-holders | Some common law holders are not corporation members but retain participation rights in native title decisions; 07 |
| GOV-AIGI | AIGI Indigenous Governance Toolkit: https://aigi.org.au/toolkit/effective-indigenous-governance | Four named principles: **customised; culturally legitimate; two-way accountability; evolving**; guidance not universal cultural law, 07/01/02/03 |
| GOV-AICD-NFP | AICD 2024 NFP Governance Principles (3rd edition): https://www.aicd.com.au/corporate-governance-sectors/not-for-profit/studies/2024-not-for-profit-governance-principles.html | Eight principles, not statutory obligations, 06 |
| GOV-ASISO-COSO | AS ISO 31000 Risk management; ISO 37000 Governance of organisations; COSO Enterprise Risk Management; IIA Three Lines | Explain origin, version, conceptual status and practical limitations; verify licensing and avoid reproducing proprietary figures, 01/03/05 |
| GOV-APRA | APRA Prudential Standards (notably CPS 220 Risk Management, CPS 230 Operational Risk Management, CPS 234 Information Security, governance standards as applicable) at https://www.apra.gov.au/ | Binding only for applicable regulated entities, distinguish from voluntary risk frameworks, 01/03 |
| GOV-STATE-WA | WA Consumer Protection INC Guide and reporting: https://www.consumerprotection.wa.gov.au/inc-guide-incorporated-associations-western-australia/accounts-and-auditing | Western Australian incorporated association governance and financial tiers, 06 |
| GOV-STATE-NAT | NSW Fair Trading, Consumer Affairs Victoria, QLD Office of Fair Trading, SA Consumer and Business Services, ACT Access Canberra, Tasmania CBOS, NT Licensing, WA Consumer Protection | Eight jurisdiction matrices, confirm 2025-26 changes and ACNC charity harmonisation for each, 06 |
| AASB-CORE | Australian Accounting Standards Board, official current standards: https://standards.aasb.gov.au/ | AASB 101, 102, 107, 108, 110, 115, 116, 136, 137, 138, 15, 16, 9, 1058, 1060 and conceptual framework when applicable, 04/05/06/07 |
| AASB-18 | AASB 18: https://standards.aasb.gov.au/aasb-18-jun-2024 | Prospective generally 1 Jan 2027 for for-profit Tier 1, 1 Jan 2028 NFP; confirm Tier 2/transition; 04/05 |
| AASB-CLIMATE | AASB S2 versioning and applicability: https://standards.aasb.gov.au/ and https://aasb.gov.au/research-resources/knowledge-hub/aasb-s2-knowledge-hub/aasb-s2-frequently-asked-questions/general-faqs/ | Groups 1/2/3 from annual periods starting 1 Jan 2025 / 1 Jul 2026 / 1 Jul 2027 subject to Corporations Act criteria. Original AASB S2 applies to years starting before 2027, revised compilation from 2027; S1 generally voluntary, 05 |
| AUASB-AUDIT | Auditing and Assurance Standards Board: https://www.auasb.gov.au/standards-guidance/ | ASA 200/240/315/330/500/570/700/705/706/720 etc according to issues; clarify auditor work versus board responsibility, 05 |
| AUASB-CLIMATE | ASSA 5000 and ASSA 5010: https://www.auasb.gov.au/standards-guidance/auasb-standards/standards-on-sustainability-assurance/ | Mandatory/voluntary assurance and staged climate assurance timeline, 05 |

**Notable update tests already identified:**

- ASX confirmed fourth-edition recommendations remain operative; the **21 July 2026 fifth-edition consultation**, closed **14 September 2026**, is a prospective policy watchlist, not law.
- ASIC's current financial-review areas include material estimates, asset impairment, revenue and provisions, with added **decommissioning/site-restoration provision disclosures** in 2026/27. Do not recycle a 2025 surveillance priority as if it is latest.
- Climate reporting applies only to entities meeting the Corporations Act Chapter 2M scope and staged thresholds; **2026 is not an automatic reporting date for all charities, NFPs or Indigenous corporations**. Record original versus revised AASB S2 applicable accounting periods.
- ORIC reporting is governed by CATSI size and income categories, and an ORIC-registered charity generally reports through ORIC rather than submitting a duplicate ACNC Annual Information Statement. Confirm case-specific exceptions.
- WA associations legislation changed after the March 2024 AICD comparative table, so no old table cell should be reused unverified.

### D4. Authoritative court judgments and factual inquiries to acquire

For reported law, obtain the **official court judgment**, use paragraph citations and independently verify procedural posture, ratio, scope and subsequent appellate treatment. At minimum:

1. `ASIC v Healey [2011] FCA 717` (Centro), financial statements, personal review and current/non-current classifications. Official Federal Court summary: https://www.fedcourt.gov.au/about/corporate-information/annual-reports/2011-12/ar2012.pdf (secondary to judgment).
2. `ASIC v Hellicar [2012] HCA 17`, James Hardie, misleading ASX announcement and board minutes: https://www.hcourt.gov.au/cases-and-judgments/judgments/judgments-1998-current/australian-securities-and-investments-commission-v-hellicar .
3. `Shafron v ASIC [2012] HCA 18`, duties of company secretary/general counsel as an officer: https://www.hcourt.gov.au/cases-and-judgments/judgments/judgments-1998-current/shafron-v-australian-securities-and-investments-commission .
4. `ASIC v King [2020] HCA 4`, functional test of an officer's capacity to significantly affect financial standing: https://www.hcourt.gov.au/cases-and-judgments/judgments/judgments-1998-current/australian-securities-and-investments-commission-v-king .
5. Additional authoritative AICD-mentioned cases on delegation, misuse, insolvency and conflicts to be selected from actual LEG/LAPP citations and then checked individually against court sources. **Do not invent holdings, paragraph numbers or cite media reports as the court.**
6. CBA's APRA Prudential Inquiry and other official Royal Commission/inquiry reports should be referenced as **regulatory inquiries**, not court holdings. Source the inquiry report itself, related responses and dates if available.

### D5. Six entity-applicability gateways to use throughout the corpus

| Organisation and governing capacity | Direct legal framework to check first | Overlay / limitation that must not be omitted |
|---|---|---|
| ASX-listed Australian company | Corporations Act, ASX Listing Rules, constitution; sector-specific law | ASX 4th principles operate on disclose-or-explain basis; mandatory Listing Rules are different in status; APRA only if regulated |
| Ordinary unlisted proprietary or public company | Corporations Act, constitution or replaceable rules, industry law | No automatic ASX or APRA duties; financial lodgement depends on statutory entity and circumstances |
| ACNC-registered company limited by guarantee | ACNC Act, ACNC Regulations/Governance Standards, constitution, and continuing applicable Corporations Act provisions | Charity registration changes application of some Chapter 2D civil duties; do not treat ACNC Standard 5 as an identical personal penalty section; taxation/DGR separate |
| Incorporated association, charity or non-charity | Relevant state/territory Associations Act and constitution/rules | If charity, add ACNC standards and check specific charity reporting exemptions/harmonisation; association duties and financial tiers vary by jurisdiction |
| CATSI corporation (charity or non-charity) | CATSI Act and rule book; ORIC reporting/enforcement | If ACNC charity add relevant ACNC governance overlay; reporting generally goes to ORIC rather than duplicate ACNC AIS; check native-title role separately |
| RNTBC/PBC | CATSI Act + Native Title Act + PBC Regulations + rule book | Distinguish corporate members from affected common law native title holders (who may not be members); native title decisions need additional statutory consent/consultation and certification |

**Non-equivalence rule:** Aboriginal and Torres Strait Islander ownership or leadership does not, by itself, mean an organisation is registered under CATSI. Determine its actual legal vehicle. Likewise, not every NFP is a registered charity, and not every CATSI corporation is an RNTBC.

### D5. Context-source and copyright safeguards

- Government/regulator sources carry legal or administrative authority **only for their scope and date**.
- Australian Indigenous Governance Institute (AIGI) guidance should be attributed, not recast as a claim about all Aboriginal and Torres Strait Islander communities. For any specific group, nation, Traditional Owners or language, rely on public community-authorised material where possible and otherwise record the need for local verification.
- The Indigenous governance chapter must include the distinction between **membership rights**, **common law native title holder rights**, **native title rights and interests**, **corporate powers**, **trustee obligations**, **grant conditions** and **funding relationships**.
- Do not import a US governance model or a public-sector standard as binding Australian corporation law without a statutory or contractual hook.
- Keep data and source text within the user's private workspace; do not republish source PDFs or long extracts to a public repository. The Markdown is an original derivative explanation, not a substitute facsimile.

## E. File-by-file specifications and detailed hierarchical outlines

### Shared file specification

Each file begins with: exact filename; version; date of law check; curriculum vintage; scope; entity applicability tags; core evidence sources; status (`draft/verified`); and a link to the central register. Each file ends with a concise source list, intra-corpus links, completeness log and any unresolved legal questions. Sections use stable identifiers (e.g., `[01.04.03]`) in plain headings to improve Notebook retrieval; references always link to both an identifier and the exact filename. Use consistent source descriptors and entity categories. The word budgets below are **planning limits**, not targets that should override evidence or completeness.

### `00_Master_Index_and_Source_Register.md`

**Purpose:** Navigation, epistemic controls, legal applicability key, source register, glossary and change log, rather than a chapter-length summary. Suggested 6,000-9,000 words, updated only after drafts 01-08 reconcile.

- `00.01` Purpose, covered jurisdictions and date of legal validity; how to use privately in Gemini Notebook.
- `00.02` The nine-file navigation table, 30-second topic finder, who-should-read-what guide and query examples.
- `00.03` Corporate and community governance entity classification: Corporations Act listed; other companies; company limited by guarantee; registered charity; incorporated association (WA and other jurisdictions); CATSI corporation; ORIC-registered charity; PBC/RNTBC. Explicitly represent overlapping types rather than assuming all categories are mutually exclusive.
- `00.04` Distinction between law, listing rule, case law, regulator guidance, accounting standards, voluntary best practice, Indigenous cultural principles and the author's analysis.
- `00.05` Definitions of director, officer, Responsible Person, management committee, member, common law holder, native title rights and interests, charity, NFP, solvency, assurance, business judgment, stewardship.
- `00.06` Source register: 24 original PDFs, aliases, printed/PDF page conventions, SHA-256, duplicate status, curriculum vintage and source function.
- `00.07` Public source register: primary legislation official URL/compilation; regulator page date; AASB/ASSA versions; AIGI/ASX/AICD voluntary guidance; primary judgments and pinpoint citations.
- `00.08` Curriculum-to-section coverage index (C01-C49 plus expanded subheading ledger) and case/tool index (T01-T48; C01-C19).
- `00.09` Conflict-of-authority decision rules, historical-versus-current law reconciliation, unresolved issue register.
- `00.10` Alphabetical technical glossary, abbreviations, formula index, legal citation glossary and jurisdiction matrix.
- `00.11` Version history, verified-on dates, validation results, watchlist and correction protocol.
- `00.12` Copyright/source treatment and boundaries: not legal advice or community authority; original explanatory writing.

### `01_Governance_and_Directors_Duties.md`

**Purpose:** Foundational model of legal identity, governance powers, duties, liability and the board's internal/external legal setting. Suggested 18,000-24,000 words. Main sources GOV, LEG, GAPP, LAPP, GSH, LSH; live primary law and reported cases.

- `01.01` Why organisations incorporate: separation of legal personality, perpetual succession, limited liability, ownership/control, stakeholder legitimacy.
- `01.02` Entity-specific legal architecture: listed/public/proprietary companies, company limited by guarantee, cooperatives/mutuals, statutory and unincorporated entities, incorporated associations, CATSI corporations; scope map.
- `01.03` Where governance authority resides: statutes, constitutions/replaceable rules, rule books, contracts, charters, member resolutions, board resolutions and delegations; meaning and limits of each.
- `01.04` What a director/officer is: valid appointment; alternate, de facto and shadow director; executive/non-executive/independent/nominee; statutory definition of officer; chair, CEO, company secretary and committee member.
- `01.05` Appointment, eligibility, pre-joining investigation, conflicts register, onboarding, indemnities/insurance, access to records, removal, resignation, continuing obligations, disqualification.
- `01.06` To whom duties are owed: corporate best interests, purposes, creditor considerations in distress, charity purposes, duties to members/common law holders under different regimes, stakeholder effects without inventing direct duties.
- `01.07` Care and diligence: objective standard in context; information, attendance, reading accounts, ongoing enquiry, outside advice, reliance and board challenge.
- `01.08` Good faith, proper purposes, fiduciary loyalty, conflicts of duty/interest, material personal interests and conflict management; related-party transactions.
- `01.09` Misuse of information/position, insider trading, corporate opportunities, confidential information, phoenixing, improper financial advantages.
- `01.10` Business judgment rule: statutory elements, decision threshold and scope; not a blanket defence to omissions or compliance failure.
- `01.11` Delegation and reliance; individual responsibility versus collective resolutions; committees cannot extinguish board responsibility.
- `01.12` Insolvent trading and safe harbour under Corporations Act; relationship to charity, incorporated association and CATSI obligations; cross-ref 04.
- `01.13` Disclosure and market-conduct obligations for listed entities; ASX Listing Rules, governance reporting, materiality, insider information and market announcements.
- `01.14` Regulatory environment: ASIC, ACNC, ORIC, ASX, APRA, ACCC, AUSTRAC, ATO, state regulators; which apply to whom.
- `01.15` Employment/industrial relations, WHS/psychosocial safety, harassment, whistleblowers, privacy/data, competition/consumer, modern slavery, corruption, environment/climate and intellectual property as board-oversight domains.
- `01.16` Compliance management architecture: legal register, delegation matrix, standards, escalation, assurance, reporting and tone from top.
- `01.17` Legal remedies and sanctions: civil/criminal standard and penalties as dated, compensation/disqualification, indemnification, D&O policy exclusions, advice privilege, documents and insurance limits.
- `01.18` Case-law comparison with original facts, legal issue, ratio and limits: Centro, James Hardie, officers and further cases source-verified.
- `01.19` `Applies differently`: tabular rules for ASX company, unlisted company, CLG charity, incorporated association by state, CATSI corporation, RNTBC; source cross-links to 06/07.
- `01.20` Director action tests: before joining, conflicts, legal non-compliance, event escalation, disclosure, and decisions under financial distress.

### `02_Board_Effectiveness_Leadership_and_Culture.md`

**Purpose:** Individual and collective behaviour; board mechanics; decision quality, leadership and culture. Suggested 13,000-18,000 words. Main sources GOV, BE, GSH, GAPP, TOOL.

- `02.01` Board effectiveness: compliance, performance, value creation/mission, trust and how effectiveness differs from efficiency.
- `02.02` AICD Corporate Governance Framework, Tricker's conformance/performance and external/internal perspectives as competing but complementary models (source attribution retained).
- `02.03` Chair/CEO/director relationships and the productive boundary between board oversight and management.
- `02.04` Individual capabilities: independence of mind, ethical courage, curiosity, financial/legal literacy, reflective practice, skill portfolios and director development.
- `02.05` Cognitive and social psychology: intuition, heuristics, bias, overconfidence, anchoring, confirmation, status and authority dynamics; use as interpretation rather than diagnosis.
- `02.06` Real-team characteristics: mutual accountability, bounded membership, compelling purpose, collective efficacy, group cohesion, role clarity.
- `02.07` Board composition: skills matrix, lived experience, stakeholder legitimacy, independence, diversity, succession and skills refresh.
- `02.08` Inclusive leadership: psychological safety, culturally responsive communication, language needs, participation and respectful disagreement.
- `02.09` Constructive challenge: questioning styles, managing uncomfortable debate, groupthink, bad-news flow, power asymmetry and chair facilitation.
- `02.10` Decision processes: agenda framing, decision rights, evidence quality, alternatives, bias checks, ethical lenses and decision-stage framework.
- `02.11` Complex and uncertain decisions: reversibility, scenario testing, dissent, minority views, in-camera discussions and documentation.
- `02.12` Meeting design: board calendar, pre-reads, reports, agenda, minutes, actions, access to advice, committees and escalation.
- `02.13` Committee governance: audit, risk, nominations, remuneration, sustainability; proportionate design for small charities/CATSI entities.
- `02.14` Culture: ethics, speak-up, safety, performance, risk, compliance, reward systems and organisational legitimacy; measurable signals and incentive effects.
- `02.15` CEO oversight: appointment, performance, remuneration, accountability, succession and absence/emergency plans.
- `02.16` Evaluation: chair, directors, committees, board self-assessment, meeting debriefs, external facilitation and credible improvements.
- `02.17` Cultural governance: what inclusivity and authority mean in Indigenous contexts; consensus and community-designed process without assuming universal traditions.
- `02.18` Practical board diagnostic, pre-meeting questions, decision-quality checklist; links to 08 and case exercises.

### `03_Strategy_Risk_and_Organisational_Resilience.md`

**Purpose:** An integrated strategy/risk/capital allocation model; strategic monitoring, enterprise risk, crises and emerging threats. Suggested 16,000-22,000 words. Main sources RISK, RAPP, RSH, LEG digital sections, TOOL.

- `03.01` Organisational purpose, mission, strategy and business/value model; for-profit return versus NFP mission and Indigenous value/rights/custodianship.
- `03.02` Strategy as integrated choices: where/how to compete or deliver services; alternative frameworks, theory of change, strategic horizons and material trade-offs.
- `03.03` Board and management roles in the strategy cycle: intelligence, strategic development, planning, approval, implementation, review and strategic decisions.
- `03.04` External landscape and internal capability: stakeholders, political/legal/economic/technology, industry competition, strengths/limitations, foresight and uncertainty.
- `03.05` Strategy options and strategic risks: pathways, assumptions, opportunity cost, option value, reversibility, institutional capacity and explicit no-go criteria.
- `03.06` Board strategy workshops, management submissions and evaluation models; critique assumptions, unrealistic growth, dependency and concentrated risk.
- `03.07` Capital allocation and strategic financial resilience: financial capacity, return versus capital cost, hurdle rates, liquidity constraints, mission efficiency, donor restrictions and native-title resource stewardship; analytic tools clearly not automatically AICD curriculum.
- `03.08` Risk definitions, taxonomy and the distinction between risk, uncertainty, hazard, control deficiency, opportunity and exposure.
- `03.09` Appetite, capacity and tolerance: dimensions, strategic alignment, measurable thresholds and key escalation triggers; distinguish risk heat maps from quantified risk.
- `03.10` Risk framework designs: ISO 31000, COSO ERM, risk identification/assessment/control/monitoring, inherent/residual risk, owner and assurance.
- `03.11` Board/committee/management/internal audit responsibilities and the three-lines model; prioritisation and line-of-sight.
- `03.12` Risk indicators and reporting: leading/lagging KRIs, scenario sensitivities, distributions, aggregations, control reliability, exceptions, action closure.
- `03.13` Strategy execution, adaptive monitoring, KPIs, learning loops, leading signals, trigger-based pivots and formal board reviews.
- `03.14` Risk culture and incentives: risk blindness, misplaced zero-appetite statements, speak-up behaviour, accountability and measurement.
- `03.15` Operational resilience and crisis governance: roles, continuity, emergency powers, time-critical decision-making, communications, recovery and after-action review.
- `03.16` Emerging/disruptive risks: privacy/cyber, generative AI, automation, climate/nature, geopolitical disruption, supply chains, reputational and workforce pressures.
- `03.17` AICD First Nations risk and strategy examples, NFP/public-sector strategy and adaptation for CATSI/PBC without imposing external purposes.
- `03.18` Worked strategic risk cases: Biscuit Makers, CBA, risk appetite diagnostics, ready/willing/able assessment; full case exercise in 08.

### `04_Financial_Literacy_Performance_and_Solvency.md`

**Purpose:** Financial statements as economic evidence; board decisions on performance, capital, liquidity and solvency. Suggested 15,000-20,000 words. Main sources FIN pp11-22, 50-100; IFS; FAPP; FSH; METHOD; HEALTH; GLOSS; financial cases.

- `04.01` Financial statements, management accounts, audit reports, budgets and forecasts: purpose, timing, bases, key limitations.
- `04.02` Accounting equations and four primary financial statements; accrual versus cash and relevant notes.
- `04.03` Balance sheet: asset/liability classification, working capital, trade flows, inventory, leases, debt, intangibles, goodwill, provisions, equity and net assets.
- `04.04` Income and performance: revenue recognition, expenses, operating margins, gross profit, EBIT, EBITDA, NPAT, other comprehensive income, underlyings/one-offs and adjustments.
- `04.05` Cash flow: operating/investing/financing, cash conversion, debt and lease cash flows, capex, free cash flow, distributions, liquidity and accounting-profit reconciliation.
- `04.06` Statement of changes in equity, tax, retained earnings, reserves, dividends and restricted accumulated funds.
- `04.07` Consolidation and reporting boundaries: subsidiaries, control, intercompany balances, joint arrangements and economic exposure versus accounting ownership.
- `04.08` Accounting judgements: impairments/recoverable amount, fair values, depreciation/amortisation, useful life, expected losses, going concern, provisions and contingent liabilities.
- `04.09` Integrated three-way budgets: profit, balance sheet, cash, forecast roll-forward and covenant model; financial controls.
- `04.10` Financial metrics and formulas: liquidity (current/quick/cash, working capital); efficiency (turnover, debtor/inventory/creditor days); solvency (debt-to-equity, net debt/EBITDA, cover); profitability (gross/EBIT/EBITDA/net margin, ROA/ROE/ROIC); cash conversion and economic return; clearly define variants and caveats.
- `04.11` Performance interpretation: historical/peer/budget analysis, cyclicality, inflation, acquisition effects, alternative profit measures, management incentives, measurement traps.
- `04.12` Distinct NFP/CATSI metrics: unrestricted liquidity, income concentration, restricted grants, service outcomes, cost per outcome, funding continuity, native title trust money, funds controlled for third parties.
- `04.13` The historical IFS 7-step balance sheet, 4-step income and 5-step cash review methods, reframed as analytical heuristics and tested against exceptions.
- `04.14` Cash-solvency test, insolvency risk, forecasts, creditor protection, warning signs, dividends and safe-harbour legal distinctions.
- `04.15` Financial distress responses: turnaround, refinance, recapitalise, restructure, administration/liquidation, source of funding; entity-specific legal thresholds.
- `04.16` Board dashboards, reporting requests, risk scenarios, variance explanations, working-capital forecast and financial sign-off links to 05.
- `04.17` Worked calculations from Nick Scali, Discount Depot, Godfreys and Surf Life Saving Queensland, with source-year context; full cases in 08.

### `05_Financial_Reporting_Audit_and_Assurance.md`

**Purpose:** What directors approve, sign, question and obtain assurance over, and how requirements differ by entity, period and reporting regime. Suggested 13,000-18,000 words. Main sources FIN pp23-49, 50-79; IFS, NICK, FIFTY, TOOL; statutes, ASIC, AASB and AUASB.

- `05.01` Reporting purposes and audiences; board accountability versus accounting team/external auditor responsibilities.
- `05.02` Applicability gateway: financial reporting by ordinary companies, ASX issuers, registered charities/companies limited by guarantee, state associations, CATSI corporations, RNTBCs and ORIC-registered charities.
- `05.03` Annual and half-year reports, directors' report and declaration, corporate governance statements, consolidated entity disclosure statement, filings and deadlines; verify legal trigger for each.
- `05.04` Financial statement completeness and true-and-fair view; four statements, notes, materiality, judgements and disclosure quality.
- `05.05` Accounting framework and basis: general versus special purpose financial reports where allowed, Tier 1/Tier 2, NFP-specific standards, AASB 18 changes by period.
- `05.06` Major accounting policy decisions: revenue, assets, impairment, contingent liabilities, provisions, related parties, debt classifications, group entities, subsequent events, going concern.
- `05.07` Directors' procedural responsibilities: challenge management, compare with known operations, accounting papers, source assurance, CEO/CFO representations and minuted inquiry.
- `05.08` Internal control framework, fraud risk, governance of accounting records and deficiencies; whistleblower and third-party risks.
- `05.09` Internal audit, audit committee purpose/membership/charter, internal versus external assurance, management action-tracking.
- `05.10` External audit: appointment, independence, audit scope, reasonable assurance versus review, materiality, audit opinions and modified reports, auditor communications.
- `05.11` Climate and sustainability: Corporations Act phased 2025/2026/2027 entry dates, AASB S2 versions, AASB S1 voluntary status, climate-related judgements, directors' declarations, assurance stages and value-chain issues.
- `05.12` ACNC/ORIC/state association financial submission and audit/review regimes, statutory exemptions and supplementary grants/accountability.
- `05.13` ASX reporting integrity, unaudited releases, continuous disclosure, governance statements and related assurance.
- `05.14` 50-matters financial sign-off framework: reconstruct original grouped questions and modernise for 2026; mark 2016 version historical.
- `05.15` Cases: Centro financial classification, Nick Scali annual-report checklist, Surf Life Saving Queensland, plausible 2026 climate reporting issues, plus cross-reference 08.
- `05.16` Pre-signing gates: 30/14/7 days before board approval; independent questions, evidence packs, red flags, exceptions, escalation and minuted actions.

### `06_Not_for_Profit_and_Charity_Governance.md`

**Purpose:** Full standalone NFP/charity/association handbook, not merely an application note to commercial governance. Suggested 15,000-21,000 words. Main sources GOV/GAPP/GSH, LEG/LAPP, RAPP 23-26, FIN/FAPP, BE, TOOL; ACNC, state laws and AICD 2024 NFP principles.

- `06.01` NFP versus charity: legal structure, charitable purpose, eligibility, for-profit prohibition versus allowable surplus, public benefit and mission protection.
- `06.02` Choosing legal vehicle: unincorporated association, incorporated association, company limited by guarantee, trust, cooperative, CATSI corporation; comparative consequences for liability, capital, membership and fundraising.
- `06.03` Registration and rules: constitution, charitable purposes/objects, beneficiaries, membership rights, general meetings, amendment and wind-up distribution, directors/committee roles.
- `06.04` ACNC Act and six Governance Standards, especially Standard 5; distinguish charity's reasonable-steps duty, applicable Corporations Act duties and state association duties.
- `06.05` Charity Responsible People, conflict management, related parties, private benefit, related business, trustee role and gifts/financial oversight.
- `06.06` Company limited by guarantee reporting and ASIC/ACNC interaction; directors, members, guarantees, charity modifications, annual meetings.
- `06.07` Incorporated associations: eight state/territory laws, mandatory rules, powers, committees, disclosures, dispute resolution, financial thresholds, regulator filings and local charity harmonisation. Provide **WA detailed worked example**, then compare other states with verified changes.
- `06.08` ACNC annual reporting: revenue thresholds, reviewed versus audited financial statements, exclusions/waivers, Basic Religious Charities and ORIC-registered charity treatment.
- `06.09` Tax/concession boundary: ACNC registration versus Australian Taxation Office charity tax concessions and deductible gift recipient (DGR) endorsement; no assumption of automatic DGR status.
- `06.10` Mission strategy: purpose/vision, theory of change, stakeholder/service-user voice, service mix, social value, mission drift and board capital allocation.
- `06.11` NFP financial stewardship: unrestricted/restricted reserves, grant funding, donated services, fundraising economics, liquidity/runway, buffers and fraud controls.
- `06.12` Funding, government contracts, fundraising laws, donor restrictions, sponsorship, volunteers, safeguarding vulnerable beneficiaries, child safety where relevant.
- `06.13` Culture, community legitimacy, diversity and volunteer oversight; board-management boundary where executives are part-time or absent.
- `06.14` Eight AICD 2024 NFP Governance Principles and their practical director questions; non-binding status.
- `06.15` Distress, restructuring, charity cancellation/winding up, protected assets and responsibilities; jurisdiction-specific checks.
- `06.16` Overlap with Indigenous charities/CATSI entities; link to 07 rather than assimilating their specific governance.
- `06.17` Cases: Positive Impact Centre, Early Gifts, Surf Life Saving Queensland and an original, clearly hypothetical WA incorporated-association scenario.
- `06.18` NFP 12-month board work plan, registration review and audit/solvency checklists, tailored to small volunteer associations and large charities.

### `07_Aboriginal_Corporations_and_Indigenous_Governance.md`

**Purpose:** Full standalone CATSI/RNTBC law and practical Indigenous governance, protecting the distinction between cultural legitimacy, corporate duties and native title-holder rights. Suggested 17,000-23,000 words. Main sources GOV 46-49 and 82-83, LEG/LAPP p5 and pp9-14, RISK 16-18, BE 79, TOOL; CATSI, Native Title Act, PBC Regulations, ORIC and AIGI.

- `07.01` Diversity of Aboriginal and Torres Strait Islander peoples, organisations and governance systems; why there is no universal cultural protocol.
- `07.02` Aboriginal corporate forms: CATSI corporation and its different legal possibilities (including charity registration), association/company/trust alternatives, prescribed body corporate role.
- `07.03` CATSI statutory architecture and ORIC regulation: registration, corporate powers, constitution-like rule book, governance requirements, records, member rights and enforcement.
- `07.04` CATSI governance and director/officer duties: care, good faith, proper purpose, conflicts, transactions, disclosure, reliance, solvency, accountability, meetings, remedies; precise CATSI section pinpoint.
- `07.05` Membership and representation: eligibility, different membership models, nominations/board composition, removal, elections, group representation and grievance processes under the rule book.
- `07.06` AIGI four principles in original wording: customised; culturally legitimate; two-way accountability; evolving. Distinguish principle from law and from a specific group's authority.
- `07.07` Cultural authority, organisational governance and relationships with Elders, Traditional Owners, community, land councils and external funders; practical, non-prescriptive questions.
- `07.08` Governance of country, culture and data: confidentiality, Indigenous data sovereignty, intellectual property, cultural heritage, free/prior/informed consultation concepts where legally or culturally appropriate; avoid invented universal legal demands.
- `07.09` RNTBC/PBC foundations: Native Title Act, trustee versus agent PBC, determination area, native title claim group, common law holders and corporations.
- `07.10` Crucial legal distinction: RNTBC corporation members versus non-member common law holders; who is entitled to decide and be consulted on specific native title matters.
- `07.11` Decision taxonomy: corporate/operational matters; native title decisions; compensation applications; agreements and other transactions; authority, consultation, consent, certification and records; exceptions/standing instructions only where permitted.
- `07.12` Agreements and interests: Indigenous Land Use Agreements (ILUAs), future acts and section 31 agreements, trust funds/royalties/compensation, land use and project counterparties; benefits/rights distinction.
- `07.13` Corporate strategy, risk, financial governance, grants, related parties, subsidiaries, procurement, investment policy, conflicts and duty to act for the corporate purpose.
- `07.14` ORIC reporting: corporation size two-of-three test, consolidated gross operating income, financial and audit reports, charity overlaps, exemptions and record-keeping.
- `07.15` Board practice: access/translation, meeting design, community engagement, conflict handling, chair facilitation, decision logs and consent proof; local verification requirement.
- `07.16` Legitimate disagreement and disputes: rule-book processes, internal complaint routes, ORIC support and external proceedings as appropriate; culturally safe practice without presuming one dispute-resolution method.
- `07.17` Public, community-authorised case examples, AIGI work and decision tree; name the specific source, group and context; never fabricate Indigenous examples as fact.
- `07.18` RNTBC board decision process and due-diligence tool for proposed native title agreement: who holds rights, authority test, alternatives, cash/assets, legal advice, consent evidence, ethical implications, board record and monitoring.
- `07.19` Future legal developments and unresolved jurisdictional issues; review native-title decisions with experienced independent advice where needed.

### `08_Directors_Toolkit_Cases_and_Practical_Applications.md`

**Purpose:** Director-ready tools, cases, calculations, decision templates and tests. Original methods, with explicit adaptation to the three contexts. Suggested 18,000-26,000 words. Main sources TOOL pp3-139, all case notes/handouts, FIFTY, METHOD, HEALTH, EXEMP.

- `08.01` How to use: advisory tool versus mandatory legal steps; source link, director role, organisational adaptation.
- `08.02` Scenario triage: establish legal entity, relevant governing document, board duty, decision threshold, time sensitivity and missing information.
- `08.03` Appointment and onboarding: board-entry diligence, integrity, conflicts, skills, appointment documentation, insurance, charter review.
- `08.04` Board operations: charter, annual calendar, meeting pack, agenda, board paper, reserved powers, delegation register, minutes, action tracker and committee interface.
- `08.05` Board effectiveness: board skills matrix, communications, debriefs, difficult conversations, ethics, decision stages, bias checks and evaluations.
- `08.06` Strategy and capital: strategic plan, options table, decision gates, linked strategy-risk-capacity, lead/lag KPI pack and no-go thresholds.
- `08.07` Risk: risk maturity, appetite/tolerance, heat-map limitations, risk indicators, control assurance, cyber/data/AI, crisis rehearsal and resilience.
- `08.08` Finance: integrated accounts, ratios, working capital, solvency, cash self-generation, source-value checks, sensitivity cases and director's question prompts.
- `08.09` Financial reporting: annual sign-off enquiry, 2016 vs current Fifty Matters crosswalk, assurance map, audit/remuneration/risk/sustainability committee draft structures.
- `08.10` Entity-context kits: ASX large listed; small/medium CLG charity; WA incorporated association; CATSI charity; RNTBC. Each has different legal applicability.
- `08.11` Complete T01-T48 tool catalog: each entry has purpose, procedure, triggers, limitations, AICD source page, public-law update and applicable regimes; link to section owner.
- `08.12` Complete CASE-01 to CASE-19 catalog: source-vintage-labelled exercise; issue/risk; questions; alternative board actions; reasoning/outcomes; case-law boundaries.
- `08.13` Three original integrated capstone scenarios: (a) listed company disclosure/cyber/reporting; (b) NFP funding distress and governance; (c) RNTBC/native title agreement and consent. Do not use invented community customs; define fictional organisation and facts transparently.
- `08.14` Self-checks and role-play: board vs executive questions, red-team decision checklist, short scenario quizzes with explanations for self-learning; not answers to any actual AICD assessment.
- `08.15` Formula directory and sample calculation audit; rounding, units, source trace, interpretations and limitations.
- `08.16` Model evidence/action record with date, legal authority, independent advice, alternative options, votes/abstentions, consent and monitoring.

### E1. Suggested distribution and anti-duplication

Primary owners: law/duties (`01`), behaviour/board mechanics (`02`), risk/strategy (`03`), management finance/economics (`04`), statutory reporting/audit (`05`), charity/association legal practice (`06`), CATSI/RNTBC/Indigenous governance (`07`), original applied tools and case evaluations (`08`), source and navigation metadata (`00`). The two specialist files `06` and `07` should independently explain what their readers need while cross-linking detailed generic theory, rather than being mere lists of exceptions. Content budgets are elastic; completeness is checked by traceability, not word count.

## F. Source, citation, terminology and version-control protocol

### F1. Claim classification is mandatory

Before writing a consequential proposition, classify it in the drafting evidence ledger as one of:

- `LAW` = operative legal requirement from a section/regulation, with entity, jurisdiction and date;
- `CASE` = holding or established principle from a judgment, with pinpoint paragraph;
- `BINDING-REG` = exchange/prudential/assurance standard binding only for defined recipients;
- `REG-GUIDANCE` = regulator's explanation or position, distinguish from the enabling law;
- `GOOD-PRACTICE` = voluntary ASX/AICD/ISO/COSO framework or nonmandatory process;
- `CULTURAL` = culturally informed governance principle or evidence from a named Indigenous author/organisation, not a universal protocol;
- `CURRICULUM` = AICD 2025/26 teaching and its pedagogical formulations;
- `ANALYSIS` = original inference, calculation, decision framework or practical recommendation.

A proposition can have multiple classifications, but every classification should remain visible. Example: a charity should manage conflicts (`ACNC Governance Standard 5` is a binding duty on the charity to take reasonable steps; a suggested conflicts register is recommended practice; a more stringent constitution rule may bind through that rule).

### F2. Two-layer citations at every substantive point

**Private AICD original**: cite `AICD[GOV, 2025/26 V1, pp. 35-40]`, `AICD[LEG, 2025/26 V1, p. 47]`, `AICD[TOOL, 2025/26 V1, pp. 30-31]`, `AICD[IFS, 2025/26 V1, p. 27]`, `AICD[FIFTY, 3rd ed., 2016, pp. 9-11]` or matching alias. The printed page is primary; append `(PDF page X)` only if numbering differs or the original report excerpt has different pagination. For FIN's appended Nick Scali 56-page extract, cite the original annual report's *printed report page* with the FIN PDF-page correspondence recorded in 00. A missing exact page must be labelled `PAGE TO VERIFY`, not guessed.

**Public law/regulator source**: use precise authority and date, e.g. `Corporations Act 2001 (Cth) s 180(1), compilation C2026C00432 (19 Sep 2026), verified 27 Oct 2026; https://www.legislation.gov.au/C2004A00818/latest`, or `ORIC, Decision-making in RNTBCs, updated 12 Oct 2026, [URL], accessed 27 Oct 2026`. For judicial claims use `ASIC v Hellicar [2012] HCA 17 at [pinpoint paragraph after verification]`. For principles use `AICD 2024 NFP Governance Principles, Principle 5, [URL]`.

Do **not** use a marketing webpage as proof of a statutory obligation when an operative section exists. Do **not** rely on a search snippet alone for subsection wording. Do **not** use a bare link or `ibid.` without a source title; each section should be independently recoverable.

Each important definition, legal rule, ratio, framework, case and table has citations close to the relevant statement. Do not overburden trivial transition sentences. Where a full discussion appears elsewhere, link to its file and `[section-ID]` and include a one-sentence independent definition for local retrieval.

### F3. Canonical retrieval structure per section

Use this section structure flexibly (do not add irrelevant empty subheadings):

```
### [03.09.02] Risk capacity, appetite and tolerance
**Scope:** ASX companies / charities / CATSI corporations / RNTBCs
**Claim type:** CURRICULUM; GOOD-PRACTICE; LAW only where separately sourced
**As taught in 2025/26:** ... with AICD printed-page reference.
**Current legal/regulatory position (verified YYYY-MM-DD):** ... or "No uniform statutory requirement identified; check regulator and constitution."
**How it works:** precise definitions, assumptions, distinctions and steps.
**Differences by entity:** short labelled comparison, including RNTBC rights where relevant.
**What directors should do:** evidence to request, challenge questions, escalation triggers.
**Worked illustration:** labelled example; arithmetic independently checked.
**Limits and exceptions:** caveats, failure modes, historical-vs-current differences.
**Sources:** exact AICD pages; authority/section; official URLs, access dates.
**See also:** [other stable section-ID] in [exact filename].
```

Aim for self-contained sections of approximately 500-1,200 words where warranted. Split legal tests or complex cases into smaller subsections rather than adding giant, multi-topic sections. Avoid an arbitrary universal paragraph cap; a reliable threshold and contextual fact pattern may require more detail. Prefer tables for cross-entity differences, calculations and legal eligibility tests.

### F4. Naming and reference controls

- Exact nine filenames and section IDs from E are immutable without an approved version change.
- First use: `Australian Securities and Investments Commission (ASIC)`, `Australian Charities and Not-for-profits Commission (ACNC)`, `Office of the Registrar of Indigenous Corporations (ORIC)`, `Corporations (Aboriginal and Torres Strait Islander) Act 2006 (CATSI Act)`, `registered native title body corporate (RNTBC)`, `prescribed body corporate (PBC)`, `Australian Accounting Standards Board (AASB)`, `Australian Auditing and Assurance Standards Board (AUASB)`.
- Distinguish `director` (corporation); `committee member` (association); `Responsible Person` (ACNC term); `director` under CATSI; `trustee`, `member`, `common law holder`, and `native title holder` whenever legally relevant.
- Distinguish `charity` (ACNC registered), `NFP` (distribution and purpose model), `company limited by guarantee` (vehicle), `incorporated association` (state/territory vehicle) and `CATSI corporation` (federal vehicle). These descriptors can overlap.
- Financials: always define currency, thousands/millions, period end, consolidation boundary, tax treatment, leases, source and denominator. Avoid using `cash profit` as an automatic synonym for operating cash flow without qualification.
- Use `as taught in 2025/26`, `as at 27 Oct 2026`, `proposed` and `illustrative` labels explicitly, never synonyms that hide status.
- For native title rights, distinguish ordinary member voting, affected common law holder decision rights, PBC statutory obligations, separate native title agreement authorisation and personal/cultural authority.

### F5. Changes in law, temporal applicability and governing documents

Each legally relevant source receives fields:

```
source_id | title | issuer | URL/primary identifier | authority_class |
entity_scope | jurisdiction | legal_section/rule | commencement_date |
operative_period_or_reporting_period | exemptions/transitional_rules |
version_or_compilation_id | verified_date | AICD_vintage_reference |
status [current/superseded/draft/unverified] | unresolved_questions
```

Where a reporting rule phases in by financial-year starting date, write the *starting date* and applicable group, not simply `from 2026`. For standards such as AASB S2 and AASB 18, record original and subsequent versions and their effective accounting periods. For the March 2024 AICD state-association table, preserve the table as a reference to historical pedagogy, create a new fully verified 2026 jurisdiction matrix and mark any material difference.

Version rules: `MAJOR` changes the nine-file architecture or legal model; `MINOR` adds verified material, cases or material legal amendments; `PATCH` corrects text, citation or arithmetic without changing claims. Each finished file has `version`, `law_as_of`, `curriculum_vintage`, `sources_verified_at`, `last_editorial_audit`, `change_summary`. The 00 register tracks one master version and section-level updates. Never change original source IDs or rewrite historic course statements to make them appear current.

### F6. Mandatory legal and practical distinction tests

Review every statement through these checks:

1. Which legal person and governing document applies?
2. Is the actor director/officer, responsible person, trustee, committee member, member or common law holder? Are these roles concurrent?
3. Is this a direct statutory duty, a law-derived fiduciary duty, a regulatory expectation or recommended governance practice?
4. Is the source legally applicable to the entity, jurisdiction, time and event?
5. Which party owns the decision, signs, votes, abstains or gives consent? Can a committee or manager act on a delegation?
6. Who has consultation or approval rights apart from the board: shareholders, members, beneficiaries, donors, funders, regulators or affected common law native title holders?
7. What evidence and record would make the decision reviewable later?
8. What does the board do if information is incomplete, advice is uncertain, consent is disputed or solvency cannot be established?

## G. Verification and acceptance framework

### G1. Mandatory release gates

| Gate | Acceptance test | Evidence retained | Fail rule |
|---|---|---|---|
| G0 Inventory | Exactly 24 PDFs logged; all open, page counts and full hashes; one exact duplicate flagged and equivalent segments mapped | Source manifest and PDF audit | Unexamined file or unacknowledged duplicate |
| G1 Curriculum | 100% of numbered course-note subsections, 48/48 director tools, 19/19 registered case entries and all substantive appendix/slide topics mapped to a substantive destination | C01-C49 and expanded item-level coverage ledger | Any unmarked course heading or tool |
| G2 Source trace | Each major concept has page-level AICD locator; legal claims also have authoritative external support | Automated citation scanner plus manual spot-check | Unverified invented page or law proposition |
| G3 Legal applicability | All cited duties tested for vehicle, status, jurisdiction, date, exclusions, commencement, operating period and decision-maker | Entity-by-law matrix | Applying Corporations Act/ACNC/CATSI/ASX rules indiscriminately |
| G4 Law currency | Relevant laws, 2026 public regulator updates and prospective amendments correctly separated from 2025/26 teaching | Legal delta register, verified dates, compilation IDs | Draft fifth ASX edition stated as operative or 2024 state table passed off as current |
| G5 Financial/technical | All numeric examples independently recomputed; definitions and ratios specify correct formulas; accounting estimates and cash/solvency distinctions checked | Calculation test notes, source cell/page and reviewer signoff | Inconsistent units, misreported numbers, ratio definitions or blanket thresholds |
| G6 Indigenous governance | AIGI principles named correctly; CATSI and RNTBC decision rights distinguished; no community practices invented; culturally authorised cases attributed | Two-way governance and RNTBC consent test sheet | Confusing member votes and native title holder consultation/consent |
| G7 NFP governance | ACNC Standard 5 formulation correct; thresholds and reporting exceptions checked; eight jurisdictions addressed; charity/DGR/nonprofit differentiated | NFP applicability and filing matrix | Treating all charities as companies or making universal audit demands |
| G8 Practical use | Every topic states director decision relevance, questions, triggers and evidence; 48 tools have original usable counterparts or explanation | Scenario tests by entity type | Dense abstract summary without application |
| G9 Retrieval | Self-contained, unique stable IDs, source attribution local, acronyms introduced, no broken filenames/links, no unnecessary duplication | Markdown linter and simulated search queries | Ambiguous heading, orphan sections, untraceable assertions |
| G10 Copyright | Original narrative, no substantial verbatim course copying or diagrams/tables reproduced as facsimiles, course and copyright provenance retained | Editorial originality review | Excessive source substitution or copied exercises |
| G11 Consistency | Cross-file legal/financial definitions and dates reconciled; complete 00 index produced last | Link/cross-reference check and consistency report | Conflicting statement of law in files 01,06 and 07 |
| G12 Release | Exactly nine validated files; hashes and version metadata; upload/ingest test succeeds | Release manifest, summary QA report | Missing file, unverified file or wrong filename |

### G2. Compulsory adversarial tests

**Legal / entity distinctions:**

- Compare five fact patterns: an ASX company; a small proprietary company; an ACNC charity limited by guarantee; a non-charity WA incorporated association and an ACNC-registered association; a CATSI corporation with ACNC charity registration; and an RNTBC seeking to sign an ILUA where some affected common law holders are not members. The corpus must not return a single generic statute or filing regime for all.
- Query ACNC Governance Standard 5 and ask whether the obligation is a duty imposed on the charity to take reasonable steps or identical to every Corporations Act civil penalty duty. Record the nuances.
- Query ASX governance edition as of October 2026; test fourth operative, fifth consultation draft.
- Query AASB S2 for periods starting 1 July 2026 and 1 January 2027; test correct version and in-scope entity conditions; avoid invented universal NFP obligations.
- Query PBC consent and compare ordinary corporate budget approval with surrender of native title rights; include non-member common law holder rights and record-of-consent.
- Query risk-appetite `zero tolerance` and distinguish aspiration from a measurable capacity, operational risk limit and prohibition.

**Financial / practical:**

- Independently calculate balance sheet identity and cash flow reconciliation for Discount Depot 2024, Nick Scali 2024 and Surf Life Saving Queensland 2024; distinguish original source inconsistencies from arithmetic errors. Verify source units and prior-year comparators.
- Test whether a reported profit but negative operating cash flow implies insolvency: corpus must discuss cash forecasts, due debts, timing, facilities and risks, not equate any one ratio with legal insolvency.
- Test FIFTY 2016 `special purpose financial reports` and later Australian reporting reforms for whether old advice remains applicable; do not simply copy.
- Test current ratio 1.5, revenue growth and negative investing cash flow examples: explain they are instructional heuristics, not universal health tests.
- Test board reliance on external audit against Centro: a clean audit does not transfer the director's financial-review obligation.
- Test charity surplus and restricted reserves: NFP status does not require break-even or prohibit surpluses; funds restrictions affect fungibility.

**Retrieval / synthesis:**

- Run 25-40 representative Gemini Notebook questions split approximately evenly across the three governance contexts; sample both simple definitions and multidimensional decisions.
- Assess correctness, attribution, temporal accuracy, entity scope, practical recommendation and whether the answer can be located to an exact file/section.
- Attempt contradictory prompts (e.g., `all charities must lodge audited accounts`, `CATSI rules are the same as the Corporations Act`, `all native title holders must be RNTBC members`) and confirm the corpus rejects false premises.

### G3. Test scorecard and decision thresholds

Acceptance is **binary** for critical errors: any uncited high-stakes legal duty, invented cultural protocol, wrong current law, missing substantive course unit, or material financial error blocks release. For noncritical retrieval and polish issues: target 100% coverage ledger items, 100% tools/cases, 100% section IDs, zero broken file references and zero unexplained source-version conflicts. Maintain a high-priority open-questions log, not a cosmetic numeric accuracy score.

## H. Production protocol and sequencing

### H1. Stages, dependencies and deliverables

| Phase | Production activity | Output and gate |
|---|---|---|
| P0, now | Review this controlling blueprint | Approved version 1.0.0; **do not draft 01-08 before approval** |
| P1 | Source freeze: full hashes, printed-to-PDF page offsets, slide concept extraction, expanded heading/tool/case ledger | Finalised G0/G1 inventory and the detailed coverage ledger |
| P2 | Legal research snapshot: primary laws, AICD-current deltas, ORIC/ACNC/state jurisdiction matrices, Indigenous source and case-law validation | Verified external source register and applicability decision trees |
| P3 | Draft 01 legal foundation in independently citable sections | Section-level source and applicability review |
| P4 | Draft 07 CATSI/RNTBC and 06 NFP/charity early, to expose legal and cultural assumptions before generic chapters are fixed | Specialist review; reconcile 01 to both |
| P5 | Draft 02 board effectiveness and 03 strategy/risk | Concept and case-coverage review; no duplicate expositions |
| P6 | Draft 04 finance and 05 reporting/audit; independently check all figures and effective accounting periods | Calculation and legal audit |
| P7 | Draft 08 practical tools and cases, incorporating 48-item and 19-case ledgers | Scenario utility audit |
| P8 | Finalise 00 index, glossary, source register, cross-references, legal deltas, version log | Cross-file and retrieval audit |
| P9 | Independent red-team and controlled release of exactly nine `.md` files | G0-G12 passed; file hashes and changelog |

### H2. Drafting-by-section discipline

1. Start with one file's full heading outline, coverage ledger slice and public legal-source inventory.
2. Draft **one bounded group of coherent sections at a time** (roughly 2,500-5,000 words per drafting pass, or smaller for complex law). Do not truncate an authority discussion to meet an arbitrary batch size.
3. After each section group, run citation pinpoints, applicability, stale-law, duplicate-text and formula checks; update the source ledger and issue log.
4. Retain each approved section as a separate temporary working fragment (e.g., `work/01/01.01-01.03.md`) with exact IDs. Fragments are **production intermediates**, not Notebook inputs and are removed or archived outside the nine-file deliverable at release.
5. Consolidate groups in approved outline order, reconcile repeated definitions, remove duplicate explanations but preserve links to specialist treatment and local disclaimers.
6. When all sections pass review, process the entire file end-to-end for legal inconsistency, narrative flow, cross-context parity and broken section links.
7. Freeze each file's version/hash and only then prepare 00. If subsequent QA changes a file, refresh 00 affected references and release manifest.
8. Test finished files together in the intended Gemini Notebook. Nine files, with no redundant PDF attachments, are the intended consumption set. Keep originals available privately for independent cross-check, not necessarily ingest them alongside the curated knowledge base.

**Completion criteria per file:** all assigned curriculum items marked `covered`; every law statement checked; enough depth to function as a standalone reference; no substantive claims supported only by a conversational summary; case and tool references resolved; and a signed QA record. Avoid estimating file size before evidence complexity is known; keep headings and passages navigable rather than artificially compressing content.

### H3. Editorial control registers

Maintain temporary, machine-checkable ledgers during production:

- `source_manifest`: 24 PDF fingerprints, printed page maps, OCR/text accessibility, duplicate clusters.
- `coverage_ledger`: `source_id,printed_page,topic,unique_finding,canonical_file,section_id,secondary_links,status`.
- `authority_ledger`: law/regulatory case as-of version/section/jurisdiction/source URL.
- `claim_ledger`: `claim_id,claim_text,type,source_locator,source_date,entity_scope,review_status`.
- `calculation_ledger`: case, page, input numbers, units, formula, independently recomputed output and rounding.
- `issues_log`: criticality, affected sections, current decision, unresolved facts, reviewer decision.
- `release_manifest`: exact nine filenames, version, word/token counts, hashes, QA date and crosslinks.

These control registers may be maintained as temporary files or text tables during authoring, but the **Notebook release remains exactly nine Markdown files**. The compact final registers belong in `00`.

## I. Reusable controlled production prompt

Use for **one substantive file or a deliberately bounded section group**. Set `MODE=OUTLINE`, `MODE=DRAFT_SECTIONS`, `MODE=VERIFY`, or `MODE=CONSOLIDATE`. Only use `DRAFT_SECTIONS` after this blueprint is approved.

```text
ROLE
You are the Research Architect, lead legal/financial fact-checker and Managing Editor
of a private Australian Corporate Governance and Directorship research corpus.
Write substantive, original, source-grounded knowledge for retrieval by Gemini Notebook.

CONTROLLING SPECIFICATION
AICD_Governance_Corpus_Production_Blueprint_v1.0.md (the version approved by the user).
Do not modify the nine-file architecture or canonical section identifiers without approval.

TASK SETTINGS
MODE = {OUTLINE | DRAFT_SECTIONS | VERIFY | CONSOLIDATE}
TARGET FILE = {exact filename 01-08}
SECTION IDS = {bounded section identifiers; do not draft other sections}
LAW AS-OF DATE = {YYYY-MM-DD}
CURRICULUM VINTAGE = AICD CDC 2025/26 V1, except separately dated publications
GOVERNANCE CONTEXTS = Corporations Act companies including ASX entities;
 NFPs/charities/incorporated associations; CATSI corporations and RNTBC/PBCs.
APPROVED OUTLINE = {paste target outline}
SOURCE SLICE = {AICD aliases, exact PDF and printed pages, source extracts/locators}
EXTERNAL SOURCES = {verified statutes, compiled versions, regulator pages, cases,
 dates, AASB/AUASB/ASX requirements, AIGI sources}
COVERAGE ROWS = {C codes and expanded subheading/tool/case entries assigned}
ALREADY APPROVED SECTIONS = {previous fragments or summaries with stable IDs}
PENDING QUESTIONS = {known gaps; do not guess missing answers}

NON-NEGOTIABLE RULES
1. Cover all assigned substantive AICD concepts in depth, not as a high-level summary.
2. Organise by governance idea and director's responsibility, not course order.
3. Clearly distinguish curriculum-as-taught from current operative law, draft changes,
 regulatory guidance, voluntary best practice, Indigenous cultural governance
 principles and editorial analysis.
4. Verify every legal claim against current authoritative law, including legal entity,
 actor, jurisdiction, affected parties, commencement, exceptions and reporting year.
 If verification is not available, write [UNVERIFIED; DO NOT RELY ON] and log the gap.
5. Distinguish company, charity, association and CATSI/RNTBC legal rights and duties.
 Native title decision rights of affected common law holders are NOT identical to
 membership rights in the RNTBC. Do not invent community-specific custom.
6. Use original wording. Do not reproduce copyrighted AICD chapters, long lists,
 published templates, copyrighted graphics, proprietary case solutions or extended quotes.
7. Preserve exact names and short attributed framework descriptions. Retain technical
 distinctions, conditional tests, ratios, legal standards and consequential examples.
8. Cite precise AICD source aliases and printed pages; cite official external URLs,
 operative statutory sections, court holdings and verification dates where material.
9. For finance, supply formulas, definitions, assumptions, dates, units, appropriate
 comparators and independently recalculated values. Separate heuristic from legal test.
10. Practical application: after material theory, give board-level questions, evidence
 to seek, decisions reserved to board, red flags, limits and escalation triggers.
11. Keep each subsection independently legible for Notebook search. Spell out acronyms,
 use stable heading IDs, exact filenames in crossrefs, and keep citations nearby.
12. Never hide source conflicts. If the 2025/26 curriculum differs from the law verified
 for the as-of date, state both and place the delta in the change log.
13. Do not write course assessment answers on the user's behalf. Cases are learning
 examples, and the exemplar is pedagogical rather than an authorised universal answer.
14. When unable to access an assigned source, STOP that assertion and record it as
 a gap; continue with verified available sections. Never manufacture page numbers.

WORKFLOW
A. Confirm that the relevant primary AICD pages and external authorities are accessible.
B. Make a micro-coverage map: every assigned heading and unique claim -> section ID.
C. Extract exact definitions, formulas, legal conditions, exception structures and cases.
D. Identify contradictions, vintage issues and jurisdictional differences.
E. Write each requested section under its stable ID using original explanatory prose.
F. Add context comparisons, decision questions, evidence needs and original examples.
G. Run a legal/citation/financial/cultural-governance adversarial check and correct.
H. Produce a compact coverage status and unresolved-items report.

OUTPUT FORMAT
For MODE=OUTLINE: deliver section tree, coverage mapping, external-source queue, gaps.
For MODE=DRAFT_SECTIONS: deliver only the complete requested Markdown sections,
 followed separately by a short coverage/citation/gaps audit. No unrequested file drafting.
For MODE=VERIFY: deliver a structured claims-and-citations audit, numerical rechecks,
 application errors, stale-law warnings and corrections; do not silently redraft sections.
For MODE=CONSOLIDATE: assemble only approved section fragments into the exact target
 filename; check IDs, reference links and duplicates; maintain full substance.

FINAL SELF-CHECK
- Every assigned AICD topic covered? - All 3 governance contexts addressed appropriately?
- Every consequential legal claim in scope and dated? - Every threshold/reporting date checked?
- No cultural protocol invented? - Formulas and calculations independently verified?
- Source pages and primary URLs traceable? - No copied source chapters or templates?
- Retrieval-ready headings, crosslinks and self-contained sections?
If any critical answer is no, mark the output NOT RELEASE READY with exact blockers.
```

## J. Stage-one review decisions and next production authorisation

The blueprint is ready for review on the following explicit choices:

1. **Nine-file allocation:** The dedicated 06 and 07 guides have standalone legal and operational depth, not simply overlay tables. The 01 file is the common foundation with clear regime limits. Approve or adjust this balance.
2. **Law-as-of policy:** 27 October 2026, with primary-law compilation and accounting period tags; never silently translate the 2025/26 curriculum into a 2026 law statement.
3. **Full-depth source model:** 49 crosswalk rows, 48 practical tools and 19 case/example register entries, with a more granular heading-by-heading ledger to be completed before drafting.
4. **No invented cultural content:** AIGI principles and published ORIC/National Native Title frameworks, attribution to community-specific authorised sources, and unresolved questions marked rather than inferred.
5. **Production order:** Confirm legal foundations and specialist entity contexts before integrated board, strategy and finance chapters; final 00 built last.
6. **Release gate:** Nine named Markdown files only after individual section audits and comprehensive red-team QA; all material gaps and exceptions visible to the Notebook user.

**Approval hold:** Stage 1 concludes at this blueprint. Do not begin drafting files `01` through `08` (or producing the final `00`) until review/approval. Any changes to the blueprint will be incorporated into its next version before production begins.
